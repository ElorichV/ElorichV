# 👋 Hi, I'm Axel Alberto Linares

**He/Him** | Backend & QA Automation Engineer | .NET • Clean Architecture • AWS • Applied AI & Cybersecurity | Mexico City

> *"Clean code doesn't just work—it speaks volumes about who built it."*

---

## 🌟 About Me

I'm a **Software Engineer** specializing in **Backend Architecture (.NET 8/9)**, **QA Automation**, **Applied AI Systems**, and **Cybersecurity**. I design resilient, high-throughput enterprise applications, AI-integrated workflows, and automated testing infrastructures built for reliability, data integrity, and scalability under pressure.

### 🎯 Core Philosophy & Focus

> 🔹 **Clean Backend Architecture:** Domain-Driven Design (DDD), Clean Architecture, REST APIs, and microservices in C# / .NET 8 & 9.  
> 🔹 **Zero-Defect Quality Assurance:** End-to-End (E2E) automation and robust regression test harnesses with Playwright Sharp & NUnit.  
> 🔹 **Applied AI & Edge Vision:** Real-time multimodal pipelines (MediaPipe, Three.js 3D avatar IK, local LLMs with Ollama/Gemma 4, OpenAI API).  
> 🔹 **Security & Cloud by Design:** AppSec (OWASP Top 10), native rate limiting, RFC 7807 problem details, and cloud-native architectures on AWS.

### 💼 Professional Journey

- **Full-Stack Software Engineer @ [Positronica Labs](https://positronicalabs.dev/team)** *(Jan 2026 – Present)*: Development and architectural engineering of .NET backend services and scalable microservices for applied AI and agentic systems. Leading technical QA automation strategy using Playwright Sharp, C#, and CI/CD quality gates ensuring zero-regression deployments.
- **QA Automation Intern @ Sección Amarilla (Agencia Digital ADN)** *(Mar 2026 – Present)*: Leading comprehensive E2E and regression automation suites using C# .NET and Playwright Sharp, reducing bug detection time by 30% across mission-critical digital platforms.
- **Associate Software Engineer I @ Solera** *(Aug 2022 – Feb 2025)*: Engineered backend microservices and full-stack solutions with C#, .NET, Java, and CFML. Optimized SQL Server queries and execution plans (reducing latency by 40%) across high-availability enterprise production systems.
- **Software Systems Engineering & Academia @ UNITEC & Cisco** *(Feb 2025 – Feb 2026)*: Thesis candidate in Computer Vision & Accessibility (LSM). Advanced specialization in Network Defense, Threat Management, and SOC operations under Cisco Networking Academy standards.

### 🚀 Currently Building

| Organization / Initiative | Focus Area |
|---------------------------|------------|
| **[Positronica Labs](https://positronicalabs.dev/team)** | Scalable .NET backend architectures for agentic AI & E2E quality gates |
| **QA Automation @ Sección Amarilla** | Scalable test automation architecture with C# .NET, Playwright Sharp & NUnit |
| **[Voz Abierta](https://github.com/ElorichV/Voz-abierta)** *(Tesis & Hackathon)* | Bidirectional real-time bridge between Mexican Sign Language (LSM) & spoken Spanish |
| **[BenchEngine](https://github.com/ElorichV/hacktoberfest2026)** *(Hackathon)* | Energy telemetry and token/Joule efficiency benchmarking for open LLMs (Gemma 4) |
| **Cloud & Distributed Architectures** | Decoupled full-stack systems deployed on AWS (ASP.NET Core Web API + React SPA) |

---

## 🚀 Tech Stack

### Languages & Frameworks
```
C# / .NET 8 & 9 / ASP.NET Core ████████████████████  Enterprise backend systems, Clean Architecture & RFC 7807
SQL (SQL Server / PostgreSQL)  ██████████████████░░  Query tuning, ACID transactions & relational indexing
React 18 / Vite / TypeScript   █████████████████░░░  Decoupled modern single-page applications (SPA)
Python (FastAPI, OpenCV, ML)   ████████████████░░░░  Computer vision (MediaPipe), AI pipelines & automation
Java / Spring Boot 3.x        ████████████████░░░░  RESTful APIs, enterprise patterns & dependency injection
Swift & SwiftUI (iOS 17+)      ███████████████░░░░░  Native iOS apps, SwiftData & on-device speech processing
C++                            ███████████████░░░░░  Algorithmic optimization & high-performance computing
```

### QA Automation & Testing
```
Playwright Sharp (C# / .NET)   ████████████████████  Modern E2E browser automation & Page Object Model (POM)
NUnit / xUnit                  ██████████████████░░  TDD, unit testing, integration tests & mock isolation
Bogus & Dynamic Fixtures       ██████████████████░░  Synthetic test data generation & deterministic factories
Robot Framework                ██████████████████░░  Keyword-driven acceptance & regression testing
```

### Applied AI, Vision & Cloud
```
Computer Vision & 3D Web       ██████████████████░░  MediaPipe Tasks (Hands, Face, Pose) & Three.js 3D Avatar IK
Local LLMs & Speech Engines    █████████████████░░░  Ollama (Gemma 4), OpenAI API, SFSpeechRecognizer & ElevenLabs
AWS (Elastic Beanstalk, S3)    ████████████████░░░░  Cloud-native deployment, CloudFront CDN, reverse proxies
Docker & CI/CD Pipelines       █████████████████░░░  Containerization, GitHub Actions automated verification
```

---

## 🔥 Featured Projects

### 1. 🌐 [Cloud-Native Interactive Full-Stack Portfolio](https://github.com/ElorichV/AxelLinaresApi)
**Production-grade decoupled web platform deployed on AWS showcasing system architecture & live code demos**

Engineered a decoupled web ecosystem connecting a high-performance **.NET 8 Web API** backend (Entity Framework Core, SQLite, native anti-spam Rate Limiting, strict input validation, and RFC 7807 ProblemDetails) with an interactive **React SPA with Vite**. Deployed on AWS Elastic Beanstalk (Amazon Linux 2023 with Nginx reverse proxy) and CloudFront CDN.

- **Stack:** .NET 8 · C# · React 18 · Vite · TypeScript · SQLite · AWS Elastic Beanstalk · CloudFront · GitHub Actions
- **Key Features:** Native rate limiting (FixedWindow), CRLF / SMTP Header Injection mitigation, and dynamic bilingual content engine (`?lang=es|en`).
- **Status:** 🚀 [Live Portfolio](https://d1xk37jjpjmwph.cloudfront.net/) · 📦 [Backend API Repo (AxelLinaresApi)](https://github.com/ElorichV/AxelLinaresApi) · 📦 [Frontend SPA Repo (cv-react-frontend)](https://github.com/ElorichV/cv-react-frontend)

---

### 2. 🤟 [Voz Abierta — LSM to Speech & 3D Avatar](https://github.com/ElorichV/Voz-abierta)
**🎓 Professional Degree Thesis (UNITEC) & 🏆 AI Hackathon por México × Clara Prototype**

Real-time, bidirectional accessibility bridge between Mexican Sign Language (LSM) and spoken Spanish engineered for the classroom. Enables two-way communication: teacher speech translates to LSM glosses animated by a responsive **Three.js 3D avatar with Inverse Kinematics (IK)**, while student signs captured via camera are tracked through **MediaPipe Tasks (hands, face, pose)** and classified locally via scikit-learn to synthesize real-time voice—running 100% locally on CPU without sending video to the cloud.

- **Stack:** Python 3.11 · MediaPipe Tasks · Three.js · scikit-learn · Web Speech API · Blender Rigging · WebSockets
- **Key Impact:** Solves the one-way communication barrier for deaf students; runs at 60 fps on standard hardware with zero GPU dependency and privacy-by-design.
- **Distinctions:** Official Research/Thesis Protocol (UNITEC Software Systems Engineering) & featured prototype at **AI Hackathon por México × Clara** (Mexico Tech Week 2026).
- **Status:** 📦 [GitHub Repository (Voz-abierta)](https://github.com/ElorichV/Voz-abierta)

---

### 3. 🌱 [BenchEngine (GreenGemma) — LLM Energy Benchmarking](https://github.com/ElorichV/hacktoberfest2026)
**🏆 Hackathon Project: Local Energy & Efficiency Benchmarking Platform for Open LLMs**

Local hardware and energy consumption benchmarking suite for open-source foundation models. Measures electric power in Watts, cumulative energy in Joules, throughput in tokens/sec, and energy efficiency in **tokens/Joule**, benchmarking quantized Gemma 4 variants (`Q4_K_M` vs `Q8_0`) under realistic workloads.

- **Stack:** Python · FastAPI · Gemma 4 + Ollama · Firecrawl · React (Lovable) · MojoAuth OTP · ElevenLabs Voice · n8n Webhooks
- **Key Features:** Multi-sponsor integration pipeline featuring live technical URL scraping (Firecrawl), passwordless audit signing (MojoAuth), executive audio verdict synthesis (ElevenLabs), and automated report dispatch (n8n).
- **Status:** 📦 [GitHub Repository (hacktoberfest2026)](https://github.com/ElorichV/hacktoberfest2026)

---

### 4. 🧪 [Enterprise E2E Test Automation Suite](https://github.com/ElorichV/Playwrigth_Demo)
**Production-grade test automation architecture with C#, .NET 9, Playwright Sharp & NUnit**

Resilient automated end-to-end testing framework engineered for high-traffic digital platforms and React SPAs. Incorporates Page Object Model (POM), data factories with Bogus, asynchronous LocatorHandlers for intercepting transient overlays, and full HAR/trace observability for failure analysis in CI/CD pipelines.

- **Stack:** C# · .NET 9 · Playwright Sharp · NUnit · Bogus · Page Object Model · GitHub Actions CI
- **Key Impact:** Automated 100+ business-critical workflows, reducing defect detection time by over 30% and eliminating flaky tests across production release cycles.
- **Status:** 📦 [GitHub Repository (Playwrigth_Demo)](https://github.com/ElorichV/Playwrigth_Demo)

---

## 🏆 Hackathons & Builder Challenges

| Event / Hackathon | Project | Core Innovation |
|---|---|---|
| **AI Hackathon por México × Clara** *(Mexico Tech Week 2026)* | [Voz Abierta](https://github.com/ElorichV/Voz-abierta) | Bidirectional LSM ↔ Spanish real-time translator with 3D avatar & MediaPipe on CPU |
| **Green AI & Open Source Hackathon** *(Hacktoberfest 2026)* | [BenchEngine (GreenGemma)](https://github.com/ElorichV/hacktoberfest2026) | Energy efficiency telemetric benchmark (Joules & tok/J) for local Gemma 4 with Ollama |
| **Mobile AI Builder Challenge** | [Voice2Task](https://github.com/ElorichV/Voice2Task) | iOS app (SwiftUI + SwiftData) transcribing voice to structured GitHub issues with GPT-4o-mini |

---

## 💼 Additional Engineering Projects

- **🥖 [Sistema de Gestión para Panaderías](https://github.com/ElorichV/Sistema-de-gestion-para-panaderias):** Mission-critical inventory and POS system built with .NET 8 Web API (Clean Architecture, ACID transactional stock deduction) and React 18 + Vite dashboard.
- **⚡ [TaskMaster-API (Modern CFML Showcase)](https://github.com/ElorichV/TaskMaster-API-Modern-CFML-Showcase):** Enterprise RESTful API built with modern CFML (100% cfscript) on Lucee & CommandBox with HMAC-SHA256 JWT auth and OWASP Top 10 mitigation.
- **🧠 [Competitive Programming & Algorithms](https://github.com/ElorichV/Codigos-de-aprendizaje-y-competencia):** High-performance C++ solutions for algorithmic challenges (OMI, Codeforces, HackerRank) featuring Treap, Persistent Segment Tree, and DP.

---

## 📜 Certifications & Honors

- 🛡️ **Cisco:** Cybersecurity Defense Analyst — [Credly Verification](https://www.credly.com/users/axel-alberto-linares-lorrabaquio/badges)
- 🔒 **Cisco:** Cyber Threat Management & Network Defense — [Credly Verification](https://www.credly.com/users/axel-alberto-linares-lorrabaquio/badges)
- ⚡ **C++ Institute:** CPP — Certified C++ Programmer
- 🐍 **Python Institute:** PCAP (Certified Associate in Python Programming) & PCEP
- ☁️ **AWS:** Cloud Practitioner *(CLF-C02)*

---

## 🌍 Community & Engineering Values

- 🧼 **Clean Code Advocate:** Code is read far more often than it is written. Readability, testability, and SOLID principles come first.
- 🧪 **Test-First Mindset:** Automated tests are living documentation and the ultimate safety net for reliable refactoring.
- 🔒 **Security-Conscious:** Defense-in-depth from database query parameterization to input validation and secure headers.
- 📈 **Continuous Growth:** Always exploring applied AI, edge vision, and resilient cloud architectures.

---

## 📫 Connect With Me

<p align="center">
  <a href="https://github.com/ElorichV" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/axel-alberto-linares-lorrabaquio-69a6b31b0" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:axel.a.linares@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://d1xk37jjpjmwph.cloudfront.net/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Interactive Portfolio" />
  </a>
</p>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ElorichV&show_icons=true&theme=dark&hide_border=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ElorichV&layout=compact&theme=dark&hide_border=true" alt="Top Languages" />
</div>

---

## 💡 Open To

- 🤝 Backend Architecture & REST API engineering (.NET 8 & 9 / C# / Cloud)
- 🧪 QA Automation and E2E testing framework design (Playwright Sharp / NUnit)
- 🤖 Applied AI, Computer Vision & Accessibility Engineering (MediaPipe / LLMs)
- ☁️ Cloud migration, microservices & AWS infrastructure
- 🚀 Challenging Software Engineering opportunities (Remote / Hybrid)

---

<p align="center">
  <em>"Clean code doesn't just work—it speaks volumes about who built it."</em>
</p>

<p align="center">
  <sub>⚙️ Backend Engineer • 🧪 QA Automation • 🤖 Applied AI • 🛡️ Cybersecurity • ☁️ AWS Cloud</sub>
</p>
