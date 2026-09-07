### System Engineering Student · DevSecOps · Backend · Offensive Security

Focused on building, deploying and security-testing production systems. I work across the full lifecycle: architecture, implementation, deployment, hardening, testing and controlled exploitation.

```text
Build → Deploy → Test → Break → Harden
```

---

## About Me

* Systems Engineering student, focused on **DevSecOps, backend engineering and offensive security**.
* Building production-oriented apps with **Next.js, Node.js and PostgreSQL**, implementing JWT, RBAC, PostgreSQL RLS and multi-tenant architectures.
* Interested in **application security, red teaming, Active Directory and cloud security**, backing development with SAST/DAST and automated testing.
* Exploring **AI Engineering**: agentic systems, MCP and multi-agent orchestration.
* Based in **Peru**.

---

| **Category**          | **Technologies** |
| ---------------------- | --------------- |
| **Languages**          | `TypeScript` `JavaScript` `Python` `Go` `Rust` `Java` `C#` `Kotlin` |
| **Backend**            | `Node.js` `Express` `NestJS` `Hono` `FastAPI` `Flask` `Spring Boot` |
| **Web**                | `Next.js 16` `React` `App Router` `Server Actions` `REST APIs` `WebSockets` `Socket.IO` |
| **Mobile**             | `React Native` `Android` `Kotlin` |
| **Desktop**            | `Java` `C#` `Electron` |
| **Database**           | `PostgreSQL` `MySQL` `SQL Server` `MongoDB` `Redis` `SQLite` `Firebase` `Supabase` `DuckDB` `ClickHouse` |
| **Message Queues**     | `RabbitMQ` |
| **Deployment**         | `Docker` `Kubernetes` `GitHub Actions` `Jenkins` `Terraform` `Nginx` `Vercel` `AWS` `GCP` `Azure` |
| **Cloud Services**     | `EC2` `Fargate` `S3` `Lambda` `RDS` `CloudWatch` `Cloudflare Tunnel` |
| **App Security**       | `OWASP Top 10` `JWT` `OAuth2` `RBAC` `RLS` `SAST` `DAST` `Hardening` `Multi-Tenant Security` |
| **Offensive Security** | `Burp Suite` `Nmap` `Metasploit` `Impacket` `Wireshark` `FFUF` `Gobuster` `Wfuzz` `WPScan` `SearchSploit` `Hydra` `John` `Bash` |
| **AI Engineering**     | `Claude Code` `OpenAI` `Gemini` `Open-Source LLMs` `MCP` `n8n` `OpenClaw` |

### Application Security

Secure authentication and authorization (JWT via secure cookies, OAuth2, server-side RBAC), deny-by-default PostgreSQL RLS, multi-tenant isolation, OWASP Top 10 mitigation, and SAST/DAST integrated into regression testing with a focus on vulnerability reproducibility.

### Offensive Security

Web app pentesting (SQLi, XSS/DOM XSS, CSRF, SSRF, XXE, IDOR, race conditions, HTTP request smuggling, cache deception, host header injection), WebSocket security, Active Directory/Kerberos attacks, AWS/Azure/GCP security (IAM and storage), and MITRE ATT&CK-based assessments.

---

# Certifications

### Offensive Security & Red Team

| Certification                            | Issuer            | Year |
| ----------------------------------------- | ------------------ | ---: |
| **Certified Red Team Analyst (CRTA)**    | CyberWarfare Labs  | 2026 |
| **Multi-Cloud Red Team Analyst (MCRTA)** | CyberWarfare Labs  | 2026 |
| **Web Red Team Analyst**                 | CyberWarfare Labs  | 2026 |

Currently pursuing: **Burp Suite Certified Practitioner — PortSwigger**

### Infrastructure & Cybersecurity

| Certification                            | Issuer     | Year |
| ----------------------------------------- | ---------- | ---: |
| **ISC2 Certified in Cybersecurity (CC)** | ISC2       | 2023 |
| **Linux Administrator LPIC-1**           | LPI / PCM  | 2023 |
| **Digital Forensics**                    | PCM        | 2023 |
| **Linux Essentials**                     | PCM        | 2023 |
| **SQL Intermediate**                     | HackerRank | 2025 |
| **Advanced Program of English**          | ICPNA      | 2023 |

---

# Featured Projects

## Multi-Tenant Agricultural Management

Production-oriented full-stack platform for livestock management.

**Stack:** `Next.js 16` `PostgreSQL` `TypeScript` `JWT` `RLS` `RBAC`

* Architecture built on **Next.js 16 App Router**, separating presentation, domain and data-access concerns.
* **207 RPC functions**, PostgreSQL with **28 versioned migrations**, and atomic multi-tenant transactions.
* Tenant isolation via **deny-by-default RLS** + server-side validated **RBAC**.
* Secure JWT authentication using HTTP cookies.
* **341 unit tests** (Vitest) and **29 E2E tests** (Playwright), integrated into CI/CD.
* Query profiling and **TTFB** performance analysis.

## Perú Informado — News Aggregator + AI

Full-stack news aggregation platform with automated content processing and AI-assisted analysis.

**Stack:** `Next.js` `Node.js` `PostgreSQL` `Supabase` `Clerk` `LLM` `Playwright`

* Server-side RSS ingestion and parsing, authentication with **Clerk**, persistence on **Supabase/PostgreSQL**.
* **LLM**-based news analysis pipeline and tiered subscriptions.
* Automated performance benchmarking with **Playwright**.

**Live application:** https://peru-informado.vercel.app

---

# Security Engagements

*All security activities described below were performed in authorized environments.*

**Engagement 1** — Found an exposed repository with source code, business logic and plaintext secrets; identified a **critical authentication backdoor** caused by an embedded master credential. Reproduced via controlled PoC, designed the remediation, and integrated security testing into the dev workflow through SAST and reproducibility testing.

**Engagement 2** — Exploited a **blind SQL injection** in an authorized environment, demonstrating database-level data exposure, plus a directory listing exposing ~**16,000 customer-related documents**. Documented attack surface and impact, with remediation proposed (input validation, authorization controls, backend hardening).

---

# Security Labs & Tools

| Project | Description |
| ------- | ------------ |
| **[Dorking Tool](https://0xincainsider.github.io/dorktool/)** | Generates advanced Google Dork queries for security research and reconnaissance. |
| **[CSRF PoC Generator](https://0xincainsider.github.io/CSRF-POC-GENERATOR/)** | Generates CSRF PoCs for authorized security testing. |
| **[Hackbar — Firefox Extension](https://addons.mozilla.org/en-US/firefox/addon/0xhaise-hackbar/)** | Firefox extension for manipulating HTTP requests during web security testing. |
| **[Firefox Security Toolkit](https://github.com/0xincainsider/firefox-security-toolkit-in-bash)** | Bash tooling for Firefox privacy and web app testing workflows. |
| **[2FA Bypass Labs](https://github.com/0xincainsider/2fa-bypass-labs)** | Intentionally vulnerable lab for studying 2FA/authentication security. |
| **[DOM Dojo](https://0xincainsider.github.io/DOM-Dojo/)** | Hands-on vulnerable lab focused on DOM-based XSS. |
| **[Burp Suite Extensions](https://0xincainsider.github.io/BurpsuiteExtensions/)** | Searchable, categorized directory of Burp Suite extensions. |

---

# DevSecOps Philosophy

Security as an engineering concern, not a final-stage audit:

```text
Requirements → Architecture → Secure Development → Automated Testing
→ SAST / DAST → CI/CD → Deployment → Monitoring → Security Testing → Remediation
```

**Principles:** Security by design · Least privilege · Deny by default · Defense in depth · Automate repetitive work · Test security continuously · Measure before optimizing · Reproduce vulnerabilities before fixing them · Infrastructure as code · Prefer explicit authorization over implicit trust.

---

# Education

**Systems Engineering** · 2022 — Present

`Software Engineering` `Databases` `OOP` `UML` `Computer Networks` `Operating Systems` `Web Development` `Mobile Development` `Information Security` `Software Quality`

**Languages:** Spanish (Native) · English (Advanced)

---

# GitHub & Development

<a href="https://github.com/0xincainsider">
  <img src="https://img.shields.io/badge/GitHub-0xincainsider-black?style=for-the-badge&logo=github" alt="GitHub">
</a>

<a href="https://gitroll.io/profile/u9QN0iJW8SzWU8TpIxqfeq630Il52">
  <img src="https://gitroll.io/api/badges/profiles/v1/u9QN0iJW8SzWU8TpIxqfeq630Il52?theme=light" alt="GitRoll Profile Badge">
</a>

---

## GitHub Metrics

[<img align="left" width="390" alt="📗 Classic" src="./metrics.classic.svg">](#)
[<img align="right" width="390" alt="🌸 Anilist " src="./metrics.plugin.anilist.svg">](#)

[<img align="left" width="390" alt="📅 Isometric calendar" src="./metrics.plugin.isocalendar.svg">](#)

[<img width="100%" height="1" alt="separator" src="https://gist.githubusercontent.com/lowlighter/3c6eaedf50273adfb7a510822672f570/raw/placeholder.svg">](#)
