<h1 align="center">Ahmad Yahea</h1>
<h3 align="center">Software QA Engineer | API, Mobile & Test Automation</h3>

<p align="center">
  <a href="mailto:ahmad.yahea@gmail.com"><img src="https://img.shields.io/badge/Email-ahmad.yahea@gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://linkedin.com/in/ahmad-yahea-7a061364/"><img src="https://img.shields.io/badge/LinkedIn-ahmad--yahea-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---

## 👋 About Me

I'm a Software QA Engineer with 3+ years of experience testing APIs, mobile apps, and web platforms across **ed-tech** and **online grocery delivery**. I build and maintain automation suites that run in CI/CD and gate deployments, and I work across the full test lifecycle: reviewing OpenAPI specs, designing test strategy, automating regression, and triaging defects.

What I care about most:

- **Exhaustive edge-case coverage** over checkbox testing: boundaries, negative paths, race conditions, and failure recovery.
- **Root-cause thinking:** my bug reports include reproduction steps, request/response payloads, environment details, severity, and a root-cause hypothesis.
- **User impact:** before QA, I spent years in customer operations and team leadership, which shapes how I prioritize defects by what real users feel.
- **Asking the bigger question:** not only "does it work?" but "does it solve the right problem?"

## 🧰 Skills & Tech Stack

**API & Protocols**

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![Newman](https://img.shields.io/badge/Newman_CLI-FF6C37?style=flat&logo=postman&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat&logo=openapiinitiative&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat&logo=socketdotio&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-3C873A?style=flat)
![3DS/SCA](https://img.shields.io/badge/3DS_/_SCA-1A1F71?style=flat)

**Test Automation & Performance**

![Appium](https://img.shields.io/badge/Appium_Flutter_Driver-662D91?style=flat&logo=appium&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![JMeter](https://img.shields.io/badge/JMeter-D22128?style=flat&logo=apachejmeter&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat&logo=githubactions&logoColor=white)

**Mobile**

![iOS](https://img.shields.io/badge/iOS-000000?style=flat&logo=apple&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode_Instruments-147EFB?style=flat&logo=xcode&logoColor=white)
![ADB](https://img.shields.io/badge/Android_ADB-3DDC84?style=flat&logo=androidstudio&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)

**Tools & Practices**

![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Agile](https://img.shields.io/badge/Agile_/_Scrum-0052CC?style=flat)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)

**Testing Types:** Functional · Regression · Integration · Security · Performance · Boundary · Negative · Exploratory · UAT

**Certification:** ISTQB Certified Tester, Foundation Level (CTFL)

## 🔍 What I Work On

### Payments & Delivery Platform QA:
- Postman collections for checkout, tokenization, 3DS challenge-response, and SCA flows across 30+ endpoints, using pre-request auth scripts, variable chaining, and layered assertions. Newman runs in CI/CD as a regression gate.
- Validation of the delivery state machine (order → dispatch → fulfillment → cancellation, including reversal paths); boundary and negative testing exposed concurrent slot-booking race conditions.
- OpenAPI review against live behavior: undocumented error codes, missing validation rules, and spec-vs-implementation drift.

### Mobile & API Automation: 
- Designed the mobile E2E framework for a Flutter app using **Appium Flutter Driver**, chosen after evaluating Flutter Integration Tests and Patrol, so test authorship stays with QA.
- **Two-layer architecture:** Appium for UI scenarios (25 prioritized test cases) and Postman/Newman for data-integrity rules the UI can't trigger (duplicate email rejection, age-gate boundaries, phone format validation).
- Postman/Newman regression suite for GraphQL and web APIs covering OAuth2, token refresh/expiry, role-based access, and more. It runs on every CI push and gates every deployment.
- VoIP and WebSocket resilience testing under throttled bandwidth, packet loss, and sudden disconnection.
- Mobile crash and performance analysis with Xcode Instruments and Android ADB across 12+ device/OS configurations.

> Employer projects are proprietary, so the code isn't public. The summaries above describe the approach and scope.
