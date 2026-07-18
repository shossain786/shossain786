<div align="center">

# Hi there, I'm Saddam Hossain 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=2E9EF7&center=true&vCenter=true&width=650&lines=Senior+SDET+%7C+12%2B+Years+Experience;Creator+of+Selenium+Boot+%E2%80%94+the+Spring+Boot+of+Selenium;Automation+Architect+%7C+Framework+Designer;Building+AI-Native+Testing+Tools)](https://git.io/typing-svg)

![Profile Views](https://komarev.com/ghpvc/?username=shossain786&color=blue&style=flat-square)
[![LinkedIn](https://img.shields.io/badge/-Connect-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/hossain-mdsaddam/)
[![Portfolio](https://img.shields.io/badge/-Portfolio-black?style=flat-square&logo=github&logoColor=white)](https://shossain786.github.io/)
[![Selenium Boot](https://img.shields.io/badge/-seleniumboot.com-2E9EF7?style=flat-square&logo=selenium&logoColor=white)](https://seleniumboot.com)
[![Email](https://img.shields.io/badge/-Email-red?style=flat-square&logo=gmail&logoColor=white)](mailto:saddam.jobs.career@gmail.com)

</div>

---

## 🚀 About Me

> *Transforming Quality Assurance through Intelligent Automation*

With **12+ years** of expertise in **Software Development & Test Automation**, I architect enterprise-grade automation frameworks that drive quality, speed, and reliability across the SDLC.

These days most of my energy goes into **[Selenium Boot](https://seleniumboot.com)** — an open-source Java framework and its surrounding ecosystem of IDE plugins, extensions, and AI tooling.

### 🏢 Current Role
**Senior SDET** at **e2open** | Leading Test Automation & Quality Engineering

### 🎯 Core Competencies

```yaml
Automation Frameworks:  Selenium WebDriver | Cucumber BDD | TestNG | JUnit 5 | Playwright
API Testing:            Rest Assured | Postman | API Automation | Microservices Testing
Languages:              Java | Python | JavaScript | TypeScript
AI & Tooling:           Model Context Protocol (MCP) | LLM-assisted test generation
IDE Platforms:          IntelliJ Platform Plugin SDK | VS Code Extension API
DevOps & CI/CD:         Jenkins | GitHub Actions | Docker | Maven | Gradle | Git
Test Management:        JIRA | TestRail | Zephyr | Quality Metrics
Architecture:           Hybrid Frameworks | Data-Driven | BDD | Page Object Model
Specializations:        Framework Design | Test Strategy | Performance | Accessibility
```

---

# ⚡ Selenium Boot — The Ecosystem I'm Building

<div align="center">

### *The Spring Boot of Selenium — zero setup, smarter defaults, Playwright-inspired APIs, and enterprise features, without hiding Selenium.*

[![Website](https://img.shields.io/badge/Website-seleniumboot.com-2E9EF7?style=for-the-badge&logo=googlechrome&logoColor=white)](https://seleniumboot.com)
[![Docs](https://img.shields.io/badge/Docs-docs.seleniumboot.com-25c2a0?style=for-the-badge&logo=readthedocs&logoColor=white)](https://docs.seleniumboot.com)
[![GitHub Org](https://img.shields.io/badge/GitHub-seleniumboot-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/seleniumboot)

</div>

Selenium Boot isn't a single library — it's a **five-surface ecosystem**, each piece independently built, versioned, and published:

| | Component | What it does | Ships to |
|---|---|---|---|
| ⚡ | **[selenium-boot](https://github.com/seleniumboot/selenium-boot)** | The Java framework — zero-boilerplate Selenium | [Maven Central](https://central.sonatype.com/artifact/io.github.seleniumboot/selenium-boot) |
| 🤖 | **[seleniumboot-mcp](https://github.com/seleniumboot/selenium-mcp)** | MCP server — lets AI drive a real browser & write tests | [PyPI](https://pypi.org/project/seleniumboot-mcp/) |
| 🧩 | **[IntelliJ Framework Plugin](https://plugins.jetbrains.com/plugin/32526)** | Project wizard, YAML schema, run configs | JetBrains Marketplace |
| 🧠 | **[JetBrains MCP Plugin](https://plugins.jetbrains.com/plugin/32516)** | Registers the MCP with JetBrains AI Assistant | JetBrains Marketplace |
| 💻 | **[VS Code Extension](https://marketplace.visualstudio.com/items?itemName=seleniumboot.selenium-boot-mcp)** | One-click MCP setup for Copilot & Claude Code | VS Code Marketplace |

<br />

<table>
<tr>
<td width="50%" valign="top">

### ⚡ Selenium Boot
**Opinionated Java Test Automation Framework**

[![Maven Central](https://img.shields.io/maven-central/v/io.github.seleniumboot/selenium-boot?color=blue&label=Maven%20Central)](https://central.sonatype.com/artifact/io.github.seleniumboot/selenium-boot)
[![License](https://img.shields.io/badge/license-Apache%202.0-green.svg)](https://github.com/seleniumboot/selenium-boot/blob/master/LICENSE)

Add one dependency, extend `BaseTest`, write `@Test` methods — driver lifecycle, waits, retry, screenshots, and CI wiring are already decided. Raw `WebDriver` is always one call away.

**What you get out of the box:**
- 🔧 Never write driver setup/teardown again — thread-safe lifecycle
- ⏱️ Never write `Thread.sleep()` again — auto-waiting `WaitEngine`
- 🎯 Tests survive CSS refactors — accessibility-first locators (`getByRole`, `getByText`, `getByLabel`)
- 🩺 `SmartLocator` + self-healing fallback strategies
- 🔁 Flaky tests stop failing your build — `@Retryable` + Flakiness radar
- 📄 YAML config with environment profiles
- 📊 HTML dashboard report — pass-rate gauge, step timeline, dark mode
- ♿ Accessibility in one line — `accessibility().run()` (axe-core bundled)
- 🌐 UI + API in one suite — `BaseApiTest` + fluent `ApiClient`
- ☁️ BrowserStack & Sauce Labs providers built in
- 📧 Email verification (Mailhog, Mailtrap, Outlook, IMAP)
- 🔒 Test quarantine via committed YAML
- 🥒 JUnit 5 · TestNG · Cucumber — all first-class

```xml
<dependency>
  <groupId>io.github.seleniumboot</groupId>
  <artifactId>selenium-boot</artifactId>
  <version>3.1.1</version>
</dependency>
```

🔗 [GitHub](https://github.com/seleniumboot/selenium-boot) · [Docs](https://docs.seleniumboot.com)

</td>
<td width="50%" valign="top">

### 🤖 seleniumboot-mcp
**AI-Powered Browser Automation via MCP**

[![PyPI](https://img.shields.io/pypi/v/seleniumboot-mcp?color=blue)](https://pypi.org/project/seleniumboot-mcp/)
[![Python](https://img.shields.io/pypi/pyversions/seleniumboot-mcp)](https://pypi.org/project/seleniumboot-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/seleniumboot/selenium-mcp/blob/master/LICENSE)

A Python **Model Context Protocol** server that lets **Claude** or **GitHub Copilot** control a real browser — navigate, interact, assert — then auto-generate complete **Java TestNG / JUnit 5 / Cucumber / pytest** code from the recorded session.

**Key Features:**
- 🛠️ **85 tools** — navigate, click, type, assert, screenshot, mock, audit
- 🚀 Auto-starts Chrome — no ChromeDriver setup needed
- 📝 Generates ready-to-run Java & Gherkin, framework-native
- 🧪 Visual regression, network mocking, device emulation
- 🔍 Page inspector with best-fit CSS selector suggestions
- 🌐 Claude Desktop, Claude Code & VS Code MCP

```bash
pip install seleniumboot-mcp
```

```
> Go to https://myapp.com, log in as admin, then
  generate a TestNG test class for the login flow
```

🔗 [GitHub](https://github.com/seleniumboot/selenium-mcp) · [PyPI](https://pypi.org/project/seleniumboot-mcp/) · [▶ Demo](https://youtu.be/54LoY2HNLrs)

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

### 🧩 IDE Tooling — IntelliJ & VS Code

Two distinct surfaces, both on the marketplaces:

**[Selenium Boot](https://plugins.jetbrains.com/plugin/32526)** *(IntelliJ IDEA plugin)* — the framework experience:
- 🪄 **New Project wizard** — Spring-Initializr style scaffolding of `pom.xml`, `selenium-boot.yml`, `testng.xml`, sample page object + test
- 📘 **JSON-Schema for `selenium-boot.yml`** — completion, validation, hover docs
- ▶️ **Run/debug configuration** — profile, config file, test filter, Maven goals

**[Selenium Boot MCP](https://plugins.jetbrains.com/plugin/32516)** + **[VS Code extension](https://marketplace.visualstudio.com/items?itemName=seleniumboot.selenium-boot-mcp)** — the AI experience: one-click registration of the MCP server with JetBrains AI Assistant, GitHub Copilot, and Claude Code.

</td>
<td width="50%" valign="top">

### 🌐 Web & Docs

- **[seleniumboot.com](https://seleniumboot.com)** — marketing site built with **Astro**, deployed via GitHub Actions
- **[docs.seleniumboot.com](https://docs.seleniumboot.com)** — **Docusaurus** documentation: getting started, configuration, reporting, accessibility, CI, cloud execution, Cucumber, JUnit 5, Gradle, extensibility, recipes

**Engineering surface behind it all:**

![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven_Central-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white)
![Docusaurus](https://img.shields.io/badge/Docusaurus-25c2a0?style=flat-square&logo=docusaurus&logoColor=white)
![Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

### Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

### Automation & Testing
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=for-the-badge&logo=cucumber&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-DC524A?style=for-the-badge&logo=testng&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Rest Assured](https://img.shields.io/badge/Rest_Assured-47A248?style=for-the-badge&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### AI & Developer Tooling
![MCP](https://img.shields.io/badge/Model_Context_Protocol-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![IntelliJ](https://img.shields.io/badge/IntelliJ_Platform-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code_API-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

### DevOps & Build
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![JIRA](https://img.shields.io/badge/JIRA-0052CC?style=for-the-badge&logo=jira&logoColor=white)

### Databases & Cloud
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MSSQL](https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

</div>

---

## 📊 GitHub Analytics

<div align="center">

![](https://github-readme-stats.vercel.app/api?username=shossain786&show_icons=true&theme=radical&include_all_commits=true&count_private=true)

![](https://github-readme-stats.vercel.app/api/top-langs/?username=shossain786&layout=compact&theme=radical&langs_count=8)

![GitHub Streak](https://streak-stats.demolab.com?user=shossain786&theme=radical)

</div>

> 📌 *Note: Statistics include contributions from private repositories, the [seleniumboot](https://github.com/seleniumboot) org, and work with [PanjatanCoders](https://github.com/PanjatanCoders).*

---

## 🏆 Achievements & Highlights

<table>
<tr>
<td width="50%" valign="top">

### 💼 Professional Impact
- 🎯 **12+ Years** of Industry Experience
- 🏗️ **10+ Enterprise Frameworks** Architected
- ⚡ **70% Faster** Test Execution
- 📈 **40% → 90%** Test Coverage Improvement
- 🔄 **15+ CI/CD** Pipeline Integrations
- 👨‍🏫 Mentored **50+ QA Engineers**

</td>
<td width="50%" valign="top">

### 🚀 Open Source & Innovation
- ⚡ Creator of **Selenium Boot** — live on Maven Central
- 🤖 Built **seleniumboot-mcp** — 85-tool MCP server on PyPI
- 🧩 Shipped **2 JetBrains plugins** + **1 VS Code extension**
- 🌐 Designed & shipped **seleniumboot.com** + full docs site
- 📚 Technical writer & open source maintainer

</td>
</tr>
</table>

---

## 💡 What I'm Passionate About

<table>
<tr>
<td width="50%">

### 🔬 Innovation
- Building next-gen automation ecosystems
- Making AI genuinely useful in the test loop
- Developer experience as a first-class feature
- Performance, accessibility & security testing

</td>
<td width="50%">

### 📚 Knowledge Sharing
- Technical mentoring & coaching
- Test automation best practices
- Framework design patterns
- Documentation that respects the reader

</td>
</tr>
</table>

---

## 📈 Current Focus

```python
class CurrentFocus:
    def __init__(self):
        self.building = [
            "Selenium Boot — core framework (Maven Central)",
            "seleniumboot-mcp — AI browser automation server",
            "IntelliJ plugin + VS Code extension",
        ]
        self.improving = ["Docs & discoverability", "Onboarding in under 5 minutes"]
        self.exploring = ["Agentic test generation", "Flakiness prediction", "Visual testing"]

    def goals_2026(self):
        return {
            "framework":  "Grow Selenium Boot into a real community project",
            "ecosystem":  "Ship the VS Code framework extension",
            "content":    "Write the guides I wish existed when I started",
            "mentorship": "Train 100+ engineers in modern automation",
        }
```

---

## 🌐 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Saddam_Hossain-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hossain-mdsaddam/)
[![GitHub](https://img.shields.io/badge/GitHub-shossain786-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shossain786)
[![Selenium Boot](https://img.shields.io/badge/Selenium_Boot-seleniumboot.com-2E9EF7?style=for-the-badge&logo=selenium&logoColor=white)](https://seleniumboot.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Blog-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white)](https://shossain786.github.io/)
[![Email](https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saddam.jobs.career@gmail.com)

</div>

---

<div align="center">

### 💭 Quote I Live By

*"Quality is not an act, it is a habit."* — Aristotle

### Show Some ❤️ by Starring [Selenium Boot](https://github.com/seleniumboot/selenium-boot)!

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer)

</div>
