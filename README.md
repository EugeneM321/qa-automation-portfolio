# QA Automation Portfolio | Web, API & Mobile

I'm a QA Engineer with 5+ years of experience in web, API, and mobile testing, including JavaScript-based automation, REST API validation, SQL, CI/CD, and mobile debugging. I'm targeting QA Automation Engineer, Software QA Engineer, Automation Test Engineer, and select SDET roles.

### Start here · [E-commerce QA Portfolio](https://github.com/EugeneM321/ecommerce-qa-portfolio)

A shopper whose payment confirmation is interrupted needs to recover the original order without a duplicate paid order or inventory deduction. Playwright with TypeScript covers browser recovery. REST API tests synchronize two overlapping retries at the handler, and read-only SQLite checks independently verify one paid order and one deduction. Payments are synthetic.

**Verified** · 14 historical manual passes, 7 API/SQLite tests and 4 Playwright tests passed on main. Includes trace-based failure investigation. [Passing CI run](https://github.com/EugeneM321/ecommerce-qa-portfolio/actions/runs/46077689281)

### [Mobile Recovery QA Portfolio](https://github.com/EugeneM321/mobile-recovery-qa-portfolio)

A community feed must stay usable after interruption and keep newer content when an older response arrives late. A local HTTP harness controls response order. Node.js host tests use controlled timers and injected storage for timeout, Retry, cache restoration, invalid responses, and storage errors.

**Verified** · 4 API tests and 9 client-state tests passed on main. A separate historical manual run recorded 12 passes on a Pixel 3a Android 14 emulator. iOS and physical-device coverage remain unverified. [Passing CI run](https://github.com/EugeneM321/mobile-recovery-qa-portfolio/actions/runs/46077696582)

### [Tournament QA Portfolio](https://github.com/EugeneM321/tournament-qa-portfolio)

An invalid score must leave the stored match result and standings intact. Postman/Newman exercises the form and HTML HTTP contract and reads back both views after invalid input, accepted score limits, draws, and repeated writes. Cypress verifies keyboard navigation, Space activation, and error focus after HTTP 422. Roles are synthetic and state is held in memory.

**Verified** · 12 historical manual passes, 49 Newman requests with 181 passing assertions, and 6 Cypress specs passed on Ubuntu. The controlled failure produced JUnit, a screenshot, and a demo log. Local Windows Cypress startup remains blocked. [Passing CI run](https://github.com/EugeneM321/tournament-qa-portfolio/actions/runs/46077658866) · [Controlled failure](https://github.com/EugeneM321/tournament-qa-portfolio/actions/runs/46076125123)

### Technology

**Demonstrated in the portfolio** · JavaScript, TypeScript, Cypress, Playwright, Postman/Newman, REST API testing, SQL/SQLite, GitHub Actions, Android Studio, and ADB.

**Additional professional experience** · Selenium WebDriver, Jira, TestRail, Cucumber/Gherkin, and Charles Proxy.

These independent projects use synthetic data. They contain no employer or client source code, production data, credentials, private logs, or proprietary assets.
