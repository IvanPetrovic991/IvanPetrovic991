<h1 align="center">Hi, I'm Ivan 👋</h1>
<h3 align="center">Senior QA Automation Engineer · Performance Engineer · QA Lead</h3>
<p align="center">
  I work across the full testing stack — end-to-end &amp; API automation, visual regression,
  and performance/load testing — building CI-native suites that enforce quality on every
  change. Quality gates should fail builds, not people.
</p>
<p align="center">
  Currently leading QA and performance at <b>Senthorion</b>, a multi-tenant cybersecurity SaaS.
</p>

<p align="center">
  <a href="https://ivanpetrovic.dev"><img src="https://img.shields.io/badge/portfolio-ivanpetrovic.dev-5ecfa8?style=for-the-badge&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/ivan-petrovic-me/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:ivannkpetrovic@gmail.com"><img src="https://img.shields.io/badge/Email-333333?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### 🧰 Tech & tools

<p>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Locust-44b349?style=flat-square&logo=python&logoColor=white" alt="Locust" />
  <img src="https://img.shields.io/badge/JMeter-D22128?style=flat-square&logo=apachejmeter&logoColor=white" alt="JMeter" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
</p>

### 🔬 Focus areas

- **E2E UI automation** — Playwright, TypeScript, Page Object Model, self-healing locators
- **Visual regression** — Playwright pixel baselines, cross-browser & responsive snapshots, scalable registry
- **Performance & load testing** — Locust, JMeter, SLA gates, soak & memory-leak detection
- **CI/CD for tests** — GitHub Actions, sharded matrices, quality gates, PR annotations
- **API & accessibility testing** — API-level canaries, axe-core WCAG scans
- **Security-platform testing** — vulnerability-scanner results, role-based access, multi-tenant data isolation
- **Observability** — Prometheus + Grafana dashboards for live test insight

### 📌 Featured projects

**[self-healing-playwright-framework](https://github.com/IvanPetrovic991/self-healing-playwright-framework)** — Playwright + TypeScript E2E framework built around a **self-healing locator engine**: ordered selector fallbacks that heal, persist across runs, and then report the override on every subsequent run so a green-via-fallback suite can never hide rot. Proven against the live booking.com (Stays, Flights, Cars, Attractions), with axe-core accessibility and API-level checks on sharded, shuffled GitHub Actions CI. Tracks every Playwright release (currently 1.65) and logs what it adopted, and what it deliberately left out.

**[visual-comparison](https://github.com/IvanPetrovic991/visual-comparison)** — Visual regression testing on Playwright's built-in pixel diffing (no Percy/Applitools). Records baselines from a clean build and proves it catches UI regressions by diffing an intentionally buggy one — with a CI guard that fails the build if the suite *stops* catching them. A data-driven registry is designed to scale from 6 scenarios to 1000+ snapshots without new test code. **[→ live Allure dashboard](https://ivanpetrovic.dev/visual-comparison/)**

**[locust-performance-lab](https://github.com/IvanPetrovic991/locust-performance-lab)** — Code-first load-testing lab: distributed Locust, live Grafana monitoring, and automated SLA / regression / memory-leak gates that fail the CI build when latency budgets are breached. The gate scripts are themselves unit-tested, and the load job is blocked behind that suite — untested judges are worse than no judges. The nightly regression gate judges against the median of the last five runs, and a nightly self-test proves the leak gate still fires on a deliberately leaking build.

### 📫 Get in touch

- 🌐 Portfolio: **[ivanpetrovic.dev](https://ivanpetrovic.dev)**
- 💼 LinkedIn: **[ivan-petrovic-me](https://www.linkedin.com/in/ivan-petrovic-me/)**
- ✉️ Email: **ivannkpetrovic@gmail.com**
- 📍 Podgorica, Montenegro 🇲🇪
