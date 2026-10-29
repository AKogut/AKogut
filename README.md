<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=235&section=header&text=Andrii%20Kohut&fontSize=70&fontColor=E6F1F5&fontAlignY=40&desc=AQA%20LEAD%20%E2%80%A2%20SENIOR%20SDET%20%E2%80%A2%20WARSAW%2C%20POLAND&descSize=16&descAlignY=62&animation=fadeIn" width="100%" alt="Andrii Kohut — AQA Lead / Senior SDET" />

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=21&duration=3200&pause=900&color=2A9D8F&center=true&vCenter=true&width=760&lines=I+build+test+systems+teams+can+trust.;Slow+feedback%3F+Flaky+suites%3F+Untrusted+builds%3F;TypeScript+%C2%B7+Playwright+%C2%B7+WebdriverIO+%C2%B7+Appium+%C2%B7+CI%2FCD;Quality+is+an+engineering+problem%2C+not+a+phase." alt="I build test systems teams can trust" />

<br/><br/>

<img src="https://img.shields.io/badge/ROLE-AQA_LEAD_%C2%B7_SENIOR_SDET-1a7f74?style=for-the-badge&labelColor=0d1117" alt="Role: AQA Lead / Senior SDET" />
<img src="https://img.shields.io/badge/EXPERIENCE-8%2B_YEARS_IN_QA-1a7f74?style=for-the-badge&labelColor=0d1117" alt="Experience: 8+ years in QA" />
<img src="https://img.shields.io/badge/FOCUS-SCALABLE_TEST_AUTOMATION-1a7f74?style=for-the-badge&labelColor=0d1117" alt="Focus: Scalable Test Automation" />
<img src="https://img.shields.io/badge/SCOPE-WEB_%C2%B7_MOBILE_%C2%B7_API-1a7f74?style=for-the-badge&labelColor=0d1117" alt="Scope: Web, Mobile, API" />

<img src="https://img.shields.io/badge/DOMAINS-B2B_SAAS_%C2%B7_FINTECH-e9c46a?style=for-the-badge&labelColor=0d1117" alt="Domains: B2B SaaS, Fintech" />
<img src="https://img.shields.io/badge/LOCATION-WARSAW,_POLAND-e76f51?style=for-the-badge&labelColor=0d1117" alt="Location: Warsaw, Poland" />

<br/><br/>

<a href="https://www.linkedin.com/in/andrii-kohut/"><img src="https://img.shields.io/badge/LinkedIn-andrii--kohut-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:a.kogut01@gmail.com"><img src="https://img.shields.io/badge/Email-a.kogut01%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

## 🧭 whoami

- 🎯 **AQA Lead / Senior SDET (TypeScript / JavaScript)**, Warsaw. 8+ years in software quality, 5+ of them in hands-on test automation. I design test systems that let teams ship without fear: test architecture, CI/CD quality gates, mobile device farms, test observability.
- 👥 Today I lead a QA team that owns the quality of a core part of a B2B SaaS product: manual + automated test strategy, a web & mobile framework built from scratch (Playwright, WebdriverIO, Appium), an in-house iOS/Android device farm, and **Claude Code agentic workflows** that give the whole team one entry point for AI-assisted testing.
- 🌍 Domains: **B2B SaaS and fintech** — on web, mobile web, native iOS and Android (React / React Native apps under test).
- 🚀 I'm building two products of my own, end to end: **[Forma](https://github.com/forma-finance)** — a financial operating system for freelancers, and **[Zagaday](https://github.com/zagaday)** — AI-personalized party games.
- 🚧 In the open, I'm building **[Flakemetry](https://github.com/AKogut/flakemetry)** (test runs as traces) and **[Sentra](https://github.com/AKogut/ai-flaky-test-triage)** (AI triage for CI failures) — and pushing **AI-assisted quality engineering** well past autocomplete.

## 🎯 Problems I solve

| The problem | How I solve it | Proof in the open |
|---|---|---|
| *"Our suite is flaky and nobody trusts red anymore."* | Treat every test run as a **trace**, not a pass/fail report. Measure what varied between passing and failing runs, make flakiness **explainable**, and eliminate it with data instead of re-runs. | [Flakemetry](https://github.com/AKogut/flakemetry) |
| *"Engineers burn hours triaging CI failures."* | Put an **AI triage layer** in the pipeline: classify every failure on two orthogonal axes, hypothesise the root cause, post **one** actionable PR comment — and hold the model to a hand-labelled golden dataset and a non-LLM baseline. | [Sentra](https://github.com/AKogut/ai-flaky-test-triage) |
| *"Feedback takes hours — every branch queues for one shared staging env."* | Give every pull request its **own ephemeral environment**: isolated Kubernetes namespace, suite sharded across parallel Indexed Jobs, one aggregated report, and a teardown the pipeline itself proves. | [Ephemeral K8s test envs](https://github.com/AKogut/ephemeral-k8s-test-envs) |
| *"Our E2E suite collapsed as soon as a second person touched it."* | Architecture before scripts: page objects, fixtures and selectors as **separate layers**, suites split by trigger, a global health check that fails fast with a reason. Built for a team to **extend**, not just to run. | [Playwright E2E framework](https://github.com/AKogut/playwright-ecommerce-framework) |
| *"API tests are green, but integrations still break in production."* | Test **contracts, not status codes**: schema validation on every response — including **across services** — consumer-driven contracts with Pact, property-based tests that generate the edge cases nobody hard-codes, and k6 performance budgets. | [Microservices API testing](https://github.com/AKogut/restful-booker-api-testing) |
| *"Appium or native? Everyone argues, nobody measures."* | Test the **same app three ways** — Appium, XCUITest, Espresso — behind one CI pipeline with a combined report, so the trade-off is demonstrated on evidence, not opinion. | [Mobile automation, 3 ways](https://github.com/AKogut/mobile-task-manager-automation) |
| *"We have no automation at all. Where do we even start?"* | Build the framework from scratch, wire it into CI/CD from day one, and mentor the team until the system is **theirs** — I optimise for what keeps working after I leave the room. | every repo here started as an empty folder |

## ⚙️ How I work

1. **Start from the problem, not the tool.** Frameworks, runners and dashboards are consequences. The failure mode you are fighting comes first; the stack follows.
2. **Tests are production code.** Same architecture standards, same code review, same refactoring discipline. A suite nobody can extend is technical debt with a green checkmark.
3. **CI from day one.** A test that doesn't run on every change doesn't exist. Quality gates, sharding and fail-fast health checks are part of the framework, not an afterthought.
4. **Make quality observable.** Reports, traces, metrics. A red build must mean something — flakiness is a signal to measure and eliminate, not noise to re-run.
5. **AI with evals, not vibes.** I use AI for test generation, failure triage and root-cause analysis — and hold it to golden datasets and baselines like any other system in the pipeline.
6. **Prove the boring parts.** Teardown is tested. Reports are published. Docs let the next engineer onboard without me. Done means demonstrated.

## 🚀 Products I'm building

Two products, both mine from A to Z — product thinking, code, infrastructure and quality:

### 🏦 [Forma](https://github.com/forma-finance) · `@forma-finance`

**The financial operating system for freelancers, creators and the self-employed.** Self-employed people don't have a financial system — they have fragments: a spreadsheet, a government portal, an accountant who answers in three days, and their own memory. Forma is the calm, guided layer on top, answering three questions on every screen: *am I okay? what needs attention? what happens next?* Mobile-first (React Native, iOS + Android), built on a deterministic, versioned, source-backed rule engine — Poland first, starting with Ukrainians running a JDG.

**Built from A to Z:** the product itself, the rule engine, the React Native app, the website — and, naturally, the quality system around every release.

**Stage:** 🟡 **pre-release** — the mobile platform and the website are in active development · Ukrainian, Polish and English from day one.

### 🎲 [Zagaday](https://github.com/zagaday) · `@zagaday`

**Party word games, personalized by AI.** An offline-first party word game (explain-the-word, team vs team) with a twist no clone has: type *"Olia's bachelorette party"* or *"IT company offsite"* — and AI generates a word deck that's actually about **your** crowd. Generated once, stored locally, playable offline forever. Ukrainian-first 🇺🇦, decks are never translated — each language gets its own culturally-native content. And no ads mid-round, ever.

**Stage:** 🚧 **building the iOS MVP** — moving along a public six-stage roadmap:

| Piece | Status |
|---|---|
| Product spec, design system, content guidelines | ✅ done — the source of truth |
| iOS app — Swift 6 · SwiftUI · SwiftData · StoreKit 2 | 🚧 in progress → TestFlight, then App Store |
| AI deck generation + Pro (Python/FastAPI backend) | 📋 next — the differentiator |
| Polish & English decks | 📋 planned |
| Android app — Kotlin · Jetpack Compose | 📋 planned — starts after iOS ships |
| Online mode | 🔮 only if traction proves it |

## 📦 Projects & completion status

| Project | What it is | Stack | Status |
|---|---|---|---|
| **[Flakemetry](https://github.com/AKogut/flakemetry)** | OpenTelemetry-native test-intelligence platform — test observability, explainable flaky-test detection, AI root-cause analysis; Playwright, Vitest and Jest reporters published to npm, plus a pytest plugin | TypeScript · OpenTelemetry · Fastify · PostgreSQL · Next.js · Helm | `▓▓▓▓▓▓▓▓░░` ~80% · 🟢 **active — usable today** (M0–M4 & M7 shipped; scale & launch next) |
| **[Sentra — AI flaky-test triage](https://github.com/AKogut/ai-flaky-test-triage)** | AI triage layer for CI failures — two-axis classification, root-cause & fix-suggestion agents, one PR comment; evaluated on a hand-labelled golden dataset vs a non-LLM baseline | TypeScript · Claude API · Zod · Vitest · Playwright · GitHub Actions | `▓▓▓▓▓▓░░░░` ~60% · 🟢 **active — full pipeline runs in replay mode** (baseline scoring, ablations & v1.0 next) |
| **[Ephemeral K8s Test Envs](https://github.com/AKogut/ephemeral-k8s-test-envs)** | Per-pull-request ephemeral environments on Kubernetes — isolated namespaces, 113 API tests sharded across 4 Indexed-Job pods (~3.2× faster), aggregated Allure report, teardown the pipeline proves | TypeScript · Kubernetes · Helm · kind · Docker · Allure | `▓▓▓▓▓▓▓▓▓▓` 100% · ✅ **complete — reference build** |
| **[Playwright E-Commerce Framework](https://github.com/AKogut/playwright-ecommerce-framework)** | Layered E2E framework built for a team to extend — POM, fixtures, selectors, tagged critical / smoke / regression suites, Chromium · Firefox · WebKit CI matrix, Flakemetry reporter, live test-health dashboard | TypeScript · Playwright · GitHub Actions · Allure | `▓▓▓▓▓▓▓▓▓▓` 100% · ✅ **complete — maintained** |
| **[Restful Booker API Testing](https://github.com/AKogut/restful-booker-api-testing)** | Production-grade API automation for a Spring Boot microservices platform — nine test layers: Zod contracts incl. cross-service, Pact consumer contracts, property-based, OWASP-oriented security (ZAP), k6 performance budgets | TypeScript · Vitest · Axios · Zod · Pact · k6 · Docker | `▓▓▓▓▓▓▓▓▓▓` 100% · ✅ **complete** |
| **[Mobile Task Manager Automation](https://github.com/AKogut/mobile-task-manager-automation)** | One React Native app tested **three ways** — Appium vs XCUITest vs Espresso — behind one CI pipeline with a combined live report | TypeScript · Appium · XCUITest · Espresso · WebdriverIO | `▓▓▓▓▓▓▓▓▓▓` 100% · ✅ **complete** |
| **Portfolio website** | Personal site & professional portfolio — Next.js, E2E-tested with Playwright (incl. accessibility checks), shipped via GitHub Actions | Next.js · TypeScript · Tailwind · Playwright | `▓▓▓▓▓▓▓▓▓░` ~90% · 🚀 **launching soon** |

<div align="center"><sub>📊 Live test reports: <a href="https://akogut.github.io/playwright-ecommerce-framework/">E2E</a> · <a href="https://akogut.github.io/restful-booker-api-testing/">API</a> · <a href="https://akogut.github.io/mobile-task-manager-automation/">Mobile</a></sub></div>

## 🛠️ Toolbox

**Automation**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
<img src="https://img.shields.io/badge/WebdriverIO-EA5906?style=flat-square&logo=webdriverio&logoColor=white" alt="WebdriverIO" />
<img src="https://img.shields.io/badge/Appium-663399?style=flat-square&logo=appium&logoColor=white" alt="Appium" />
<img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" alt="Selenium" />
<img src="https://img.shields.io/badge/Cucumber-23D96C?style=flat-square&logo=cucumber&logoColor=black" alt="Cucumber" />

**Languages & runtime**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />

**Mobile**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/XCUITest-147EFB?style=flat-square&logo=apple&logoColor=white" alt="XCUITest" />
<img src="https://img.shields.io/badge/UiAutomator2-3DDC84?style=flat-square&logo=android&logoColor=white" alt="UiAutomator2" />
<img src="https://img.shields.io/badge/Espresso-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Espresso" />
<img src="https://img.shields.io/badge/BrowserStack-FF6600?style=flat-square&logo=browserstack&logoColor=white" alt="BrowserStack" />
<img src="https://img.shields.io/badge/Device_Farm-0d1117?style=flat-square" alt="Mobile Device Farm" />

**API & contracts**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/REST-0d1117?style=flat-square" alt="REST" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="Postman" />
<img src="https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white" alt="Axios" />
<img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" alt="Zod" />
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest" />
<img src="https://img.shields.io/badge/Pact-0d1117?style=flat-square" alt="Pact" />
<img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white" alt="k6" />
<img src="https://img.shields.io/badge/SoapUI-0d1117?style=flat-square" alt="SoapUI" />

**CI/CD & infrastructure**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
<img src="https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white" alt="GitLab CI" />
<img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" alt="Jenkins" />
<img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square" alt="Azure DevOps" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
<img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />

**Observability & reporting**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" />
<img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white" alt="Datadog" />
<img src="https://img.shields.io/badge/Allure_Report-16C7B9?style=flat-square" alt="Allure Report" />

**AI-assisted engineering**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code" />
<img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude" />
<img src="https://img.shields.io/badge/GitHub_Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white" alt="GitHub Copilot" />
<img src="https://img.shields.io/badge/Cursor-0d1117?style=flat-square" alt="Cursor" />
<img src="https://img.shields.io/badge/Devin-0d1117?style=flat-square" alt="Devin" />

## 📫 Reach me

**LinkedIn** — [linkedin.com/in/andrii-kohut](https://www.linkedin.com/in/andrii-kohut/) · **Email** — [a.kogut01@gmail.com](mailto:a.kogut01@gmail.com) · **Portfolio** — launching soon

Always up for a conversation about test architecture, flaky tests, mobile automation, or bringing AI into quality engineering.

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=110&section=footer" width="100%" alt="" />
</div>
