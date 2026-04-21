# 👋 Chandan Kumar

**Senior SDET · Playwright (TypeScript) · Selenium (Java) · CI/CD**  
📍 Noida, India · 📧 chandan.kumar1504@outlook.in  
🔗 [LinkedIn](https://www.linkedin.com/in/chandan-kumar-qa) · 💻 [GitHub](https://github.com/chandankumar-qa-ai)

---

## About

Senior SDET with 11+ years of experience, including 6+ in automation. I specialise in designing **scalable, maintainable test infrastructure** — from framework architecture and CI/CD integration to flaky test elimination and team enablement.

My current stack is **Playwright (TypeScript)** for both UI and API automation, with a strong emphasis on fixture-based architecture, parallel execution, and deterministic test runs.

---

## Engineering impact

**Regression speed**  
Reduced cycle time by ~73% (45 min → 12 min) through parallel execution and optimised test architecture — not just running tests faster, but designing them to be independent and parallelisable from the start.

**Automation coverage**  
Scaled to ~75% coverage across critical workflows, with coverage mapped to business risk rather than arbitrary targets. UI automation balanced with API-layer tests following test pyramid principles.

**Flaky test elimination**  
Systematically resolved flaky tests through improved synchronisation strategies, resilient locator design, and targeted retry logic — resulting in stable, trustworthy CI pipelines.

**CI/CD integration**  
Automated quality gates embedded in GitHub Actions and Jenkins pipelines, giving teams immediate feedback on every commit.

**Team enablement**  
Mentored engineers on framework design patterns, test architecture decisions, and automation best practices.

---

## Tech stack

| Layer | Tools |
|---|---|
| UI automation | Playwright (TypeScript), Selenium WebDriver (Java) |
| API testing | Playwright API, Rest Assured, Postman |
| Languages | TypeScript, JavaScript (ES6+), Java |
| Framework design | POM, fixture architecture, data-driven, reusable utilities |
| CI/CD | GitHub Actions, Jenkins, Git |
| Reporting | Allure Reports, Extent Reports |
| Cloud | GCP, AWS (exposure), Docker (basic) |

---

## Featured project — Enterprise Playwright Framework

🔗 [github.com/chandankumar-qa-ai](https://github.com/chandankumar-qa-ai)

A full-stack automation framework built to reflect real enterprise constraints — designed for teams, not solo use.

**Architecture decisions worth noting:**
- Fixture-based design over global setup/teardown for better isolation and parallelism
- POM kept thin — business logic lives in test files, not page objects
- API tests co-located with UI tests for unified reporting and shared utilities
- Network interception used for test stability in async-heavy flows, not just mock data
- Retry logic scoped to known-flaky external dependencies, not applied globally

**CI/CD:** GitHub Actions with Allure reporting on every run

---

## Engineering philosophy

Automation is an engineering problem, not a scripting task.

- Frameworks should be **owned by the whole team** — readable, debuggable, and evolvable without the original author
- **Stability before coverage** — a suite that flakes undermines trust in the entire pipeline
- **API vs UI balance matters** — I apply the test pyramid intentionally, not by convention
- **CI/CD is the delivery mechanism** — automation that doesn't run on every commit doesn't provide real value

---

📩 Open to **Senior SDET / Lead SDET** opportunities · Technical discussions welcome before any formal process
