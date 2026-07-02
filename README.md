<div align="center">

# Hassan Al Jabaal

**Founder & CTO — ThunderByte Digital Solutions**

*Penetration Tester · SOC Analyst · Full-Stack Engineer*

[![Website](https://img.shields.io/badge/thunderbyte.co.tz-0d1117?style=for-the-badge&logo=google-chrome&logoColor=00ff88)](https://thunderbyte.co.tz)
[![TikTok](https://img.shields.io/badge/Al_Jabaal_|_Cyber_Security-0d1117?style=for-the-badge&logo=tiktok&logoColor=white)](https://tiktok.com)
[![Instagram](https://img.shields.io/badge/Al_Jabaal_|_Cyber_Security-0d1117?style=for-the-badge&logo=instagram&logoColor=E1306C)](https://instagram.com)
[![Location](https://img.shields.io/badge/Dar_es_Salaam%2C_Tanzania-0d1117?style=for-the-badge&logo=googlemaps&logoColor=00ff88)](#)

---

> *"I break systems for a living and build them on weekends."*
>
> **Security by day. SaaS by night. East Africa's digital frontier.**
 </div>

---

## About

I'm Hassan Al Jabaal — a cybersecurity practitioner and software engineer operating out of **Dar es Salaam, Tanzania**. As Founder and CTO of [ThunderByte Digital Solutions](https://thunderbyte.co.tz), I lead offensive and defensive security engagements while simultaneously building production-grade SaaS platforms serving the East African market.

My work spans the full stack: from Burp Suite sessions hunting IDOR chains and hardcoded AES keys in client-side JavaScript, to shipping multi-tenant SaaS products on Next.js 14 with PostgreSQL backends. I also share cybersecurity content to a growing audience under **Al Jabaal | Cyber Security** on TikTok and Instagram.

My Kali machine's hostname is `sub-zero`. That tells you everything.

---

## Technical Skills

**Offensive Security**

**Defensive Security / SOC**

**Security Tooling**

**Full-Stack & Infrastructure**

---

## Projects

### BarberOS — Barbershop SaaS Management Platform

Full-stack SaaS platform built for the East African market. Handles appointment booking, staff management, client records, and business analytics for barbershops across Tanzania. Production-deployed on hardened Ubuntu VPS with Nginx reverse proxy and PM2 process management.

### KODIA — AI-Powered Rent Collection & Property Management SaaS

End-to-end platform for property managers and landlords in Tanzania. Automates rent collection workflows, tenant communications, lease tracking, and financial reporting using AI-assisted decision pipelines. Stack: Next.js 14, Prisma ORM, PostgreSQL.

### Cinaix — Cinema + AI Discovery App

Cross-platform mobile application (Expo / React Native) combining the Claude API with TMDB for intelligent, context-aware movie discovery. Delivers AI-curated recommendations tuned to user mood, genre, and regional screening availability.

### ThunderByte Multi-Agent Management System (TBMS)

Internal AI orchestration platform for ThunderByte operations. Built on Next.js 14 with React Three Fiber for 3D agent visualization and monitoring. Manages multi-agent pipelines across security automation, client workflows, and intelligence aggregation tasks.

---

## VAPT Experience

Penetration testing engagements spanning web applications, REST APIs, and network infrastructure. Selected critical findings from client assessments:

| Finding | Severity |
|---|---|
| Hardcoded AES encryption keys exposed in client-side JavaScript | Critical |
| Unauthenticated API endpoints exposing user PII | Critical |
| Insecure Direct Object Reference (IDOR) across multi-tenant boundary | High |
| CORS misconfiguration allowing cross-origin credential leakage | High |
| Exposed admin/debug pages with zero authentication | High |
| SSL/TLS misconfigurations — weak cipher suites, expired chains | Medium |
| Outdated software stacks with publicly known CVEs | Medium |

Reporting pipeline: Automated security report generation using a Node.js + docx pipeline — findings go from raw notes to formatted, client-ready deliverables in minutes.

---

## SOC Triage — Threat Intelligence

Blue team analysis and triage of real-world advanced threat activity, including:

- **BPFDoor** — Linux passive backdoor using BPF packet filtering for covert C2 communication
- **APT41 LOWKEY** — Passive implant detection and IOC correlation
- **Mozi Botnet** — P2P IoT malware network traffic analysis and containment
- **IngressNightmare** — Kubernetes Ingress-NGINX RCE chain (CVE-2025-1974 series)
- - **Log4Shell** — JNDI injection detection and log-based containment
      - - **Kernel Thread Spoofing** — Detecting process masquerading via anomalous kernel thread behavior
      - - **Fokirtor SSH Backdoor** — Linux process hollowing via LD_PRELOAD interception
