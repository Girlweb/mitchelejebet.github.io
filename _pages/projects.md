---
permalink: /projects/
title: "Projects"
---

## ADS Framework SOAR Platform
**Live:** [ads-soar-platform.onrender.com](https://ads-soar-platform.onrender.com) &nbsp;|&nbsp; **Code:** [GitHub](https://github.com/Girlweb)

Open source Security Orchestration, Automation and Response platform built to eliminate alert fatigue in Security Operations Centers. Commercial SOAR platforms cost hundreds of thousands of dollars annually — this platform delivers the same capability for any organisation.

**How it works:** Ingests alerts from any security tool through a universal connector framework, enriches every alert in real time via VirusTotal API checking IPs, domains and file hashes across 94 security engines, ranks alerts by danger level using a Random Forest ML model, and executes automated playbooks in milliseconds — notifications, ticketing, IP blocking.

Implements Palantir's Alerting and Detection Strategy Framework with full MITRE ATT&CK mapping.

**Tech:** Python, FastAPI, PostgreSQL, Redis, Docker, Scikit-learn, VirusTotal API

**Impact:**
- 84% false positive reduction
- 4 hours → under 15 minutes mean time to respond
- 10x more alerts processed per analyst
- 94 security engines via VirusTotal

---

## FreelancePay Tracker
**Live:** [freelance-tracker-qayl.vercel.app](https://freelance-tracker-qayl.vercel.app) &nbsp;|&nbsp; **Code:** [GitHub](https://github.com/Girlweb/freelance-tracker)

Full-stack web application for freelancers to manage clients, invoices, and payments. Features secure authentication with SHA-256 password hashing, real-time analytics dashboard, multi-user data isolation, and a comprehensive REST API.

**Tech:** Python, Flask, SQLite, JavaScript, HTML5, CSS3, REST API

**Impact:**
- 16 automated test cases — 100% pass rate
- Multi-user data isolation
- Mobile-first responsive design

---

## Network Security & IoT Forensics Tool
**Code:** [GitHub](https://github.com/Girlweb)

Automated network traffic analysis tool for IoT device security assessment. Performs deep packet inspection identifying MQTT vulnerabilities and generates chain-of-custody forensic documentation.

**Tech:** Python, Wireshark, Scapy, MQTT, Network Security

**Impact:**
- 8 hours → 45 minutes analysis time
- 100,000+ packets processed
- 12 critical vulnerabilities identified
- Automated forensic reports with CVSS scoring

---

## DevSecOps Security Assessment Platform
**Code:** [GitHub](https://github.com/Girlweb/devsecops-pipeline-assessor)

Automated security scanner for CI/CD pipelines combining static analysis with ML-based vulnerability detection. Integrates Semgrep for SAST, Trivy for container scanning, and TruffleHog for secrets detection.

**Tech:** Python, Docker, Semgrep, Trivy, TruffleHog, GitLab CI, GitHub Actions

**Impact:**
- 15+ hours saved weekly
- 50+ security issues identified
- 10,000+ code commits analysed

---

## LinkedIn Post Generator
**Code:** [GitHub](https://github.com/Girlweb/linkedin-post-generator)

Production-ready generative AI application processing 1,000+ user requests using LangChain and Llama 3.3 (70B) via Groq Cloud API. Implements robust API authentication, rate limiting, and comprehensive error handling.

**Tech:** Python, LangChain, Llama 3.3, Groq API, Streamlit

**Impact:**
- 1,000+ user requests processed
- 95% user satisfaction
- Production-grade LLM integration
