# Awesome AI Testing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI tools, open-source libraries, practice sites and research for software testing and QA.

AI now explores apps, writes tests, repairs broken locators and checks the output of other AI systems. This list collects the tools and resources that QA engineers and developers can use today. Entries are described by what they do, not by price, because prices change too often to keep accurate.

*Maintained by the [TestOptim team](https://github.com/TestOptim-AI). TestOptim is one of the products listed below; it gets one entry in alphabetical order, like everything else.*

## Contents

- [AI QA agents](#ai-qa-agents)
- [Managed QA services](#managed-qa-services)
- [AI-assisted test automation platforms](#ai-assisted-test-automation-platforms)
- [Mobile testing](#mobile-testing)
- [Visual testing](#visual-testing)
- [Open-source AI testing libraries](#open-source-ai-testing-libraries)
- [API and unit test generation](#api-and-unit-test-generation)
- [Testing LLM features](#testing-llm-features)
- [Test automation frameworks](#test-automation-frameworks)
- [Practice sites](#practice-sites)
- [Papers](#papers)
- [Communities and learning](#communities-and-learning)
- [Related lists](#related-lists)

## AI QA agents

Platforms where an agent explores an app, or works from a goal, then produces or runs tests.

- [agent-qa](https://vostride.com) - Runs plain-language tests for web, Android, and iOS through CLI and MCP, with persistent memory and validated self-improvement.
- [AnyTest](https://anytest.dev/) - Agents explore a URL and leave end-to-end tests for review.
- [Autosana](https://autosana.ai/) - Natural-language end-to-end tests for mobile and web, built to work alongside coding agents.
- [Detektra](https://detektra.ai/) - Autonomous QA agent that tests user journeys starting from a URL.
- [KaneAI](https://www.testmuai.com/kane-ai/) - Testing agent from TestMu AI (formerly LambdaTest) that writes and runs tests from natural language on web and mobile.
- [Momentic](https://momentic.ai/) - AI QA agent and agentic tests for web and mobile, with a CLI and an MCP server.
- [QA.tech](https://qa.tech/) - Goal-based AI agents for exploratory and pull-request testing.
- [SanityCheck](https://www.sanitycheck.dev/) - Describe a test in one sentence and an agent runs it in a cloud browser.
- [Spur](https://www.spurtest.com/) - AI testing agents aimed at e-commerce and consumer brands.
- [TestOptim](https://www.testoptim.com/) - Explores a web app from its URL, generates test cases, runs them and files issues with steps, screenshots, video and Playwright traces.
- [TestSprite](https://www.testsprite.com/) - Plans, generates and runs tests from a URL or product spec, with an MCP server for coding agents.
- [Validate.QA](https://validate.qa/) - Generates a Playwright suite from a URL that you keep and run yourself.

## Managed QA services

AI-generated tests with people in the loop who review, maintain or triage them.

- [Bug0](https://bug0.com/) - Managed AI QA with a forward-deployed engineer.
- [Checksum](https://checksum.ai/) - AI-generated Playwright and API tests, verified by human engineers.
- [QA Wolf](https://www.qawolf.com/) - Maps, writes and runs Playwright and Appium tests as a service.

## AI-assisted test automation platforms

Low-code and no-code platforms that use AI for authoring, maintenance or self-healing.

- [ACCELQ](https://www.accelq.com/) - Codeless test automation across web, API, mobile and packaged apps such as Salesforce.
- [Functionize](https://www.functionize.com/) - Builds, runs and maintains tests against a live application.
- [Katalon](https://katalon.com/) - Test platform for manual, automated and AI-generated tests across web, mobile, API and desktop.
- [mabl](https://www.mabl.com/) - Low-code, agentic test automation for enterprise teams.
- [Testim](https://www.testim.io/) - AI-assisted UI and functional test authoring with self-healing locators, part of Tricentis.
- [testRigor](https://testrigor.com/) - End-to-end tests written in plain English.
- [Testsigma](https://testsigma.com/) - Agentic platform that generates, runs, heals and diagnoses tests.
- [Virtuoso QA](https://www.virtuosoqa.com/) - Enterprise test automation that records evidence of what each test covered.

## Mobile testing

- [GPT Driver](https://www.mobileboost.io/) - AI test steps for mobile apps that run inside XCUITest, Espresso and Appium.
- [Maestro](https://maestro.dev/) - Open-source end-to-end UI testing for iOS, Android and web, written as YAML flows.
- [QApilot](https://qapilot.io/) - Explores mobile apps, generates coverage and repairs broken tests for iOS, Android and Flutter.

## Visual testing

- [Applitools](https://applitools.com/) - Visual AI for end-to-end tests, plus no-code authoring.
- [BackstopJS](https://github.com/garris/BackstopJS) - Open-source visual regression testing with screenshot diffs.
- [Chromatic](https://www.chromatic.com/) - Visual, interaction and accessibility testing for UI components, from the Storybook maintainers.
- [Percy](https://percy.io/) - Visual testing and review platform from BrowserStack.

## Open-source AI testing libraries

Libraries, agents and MCP servers you can run yourself. Check each licence; not all are OSI-approved.

- [agent-browser](https://github.com/vercel-labs/agent-browser) - Browser automation CLI for AI agents, from Vercel Labs.
- [Browser Use](https://github.com/browser-use/browser-use) - Python library for AI agents that control a browser.
- [Bug0 AI](https://github.com/bug0inc/qa-agent) - Playwright library for AI regression tests that caches AI steps between runs (source-available, FSL licence).
- [Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp) - Gives coding agents Chrome DevTools for debugging and performance checks.
- [Healenium](https://github.com/healenium/healenium-web) - Self-healing locators for Selenium tests.
- [Midscene.js](https://github.com/web-infra-dev/midscene) - Vision-driven UI automation and end-to-end tests in natural language.
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - MCP server that lets AI agents drive a browser through Playwright.
- [Playwright Test Agents](https://playwright.dev/docs/test-agents) - Planner, generator and healer agents built into Playwright Test.
- [Shortest](https://github.com/antiwork/shortest) - Natural-language end-to-end tests run with Playwright and an LLM.
- [Skyvern](https://github.com/Skyvern-AI/skyvern) - Automates browser workflows with LLMs and computer vision.
- [Stagehand](https://github.com/browserbase/stagehand) - SDK that combines AI actions with code for browser automation.

## API and unit test generation

- [Keploy](https://github.com/keploy/keploy) - Records API traffic and turns it into tests and mocks.
- [Tusk](https://www.usetusk.ai/) - Generates unit, API and integration tests for pull requests.

## Testing LLM features

For teams whose product includes LLM features that need their own tests.

- [DeepEval](https://github.com/confident-ai/deepeval) - Evaluation framework for LLM apps, written like unit tests.
- [garak](https://github.com/NVIDIA/garak) - Scans LLMs for vulnerabilities such as prompt injection and data leakage.
- [Giskard](https://github.com/Giskard-AI/giskard-oss) - Evaluation and testing library for LLM agents.
- [promptfoo](https://github.com/promptfoo/promptfoo) - Tests prompts, agents and RAG pipelines, including red-teaming.
- [Ragas](https://github.com/vibrantlabsai/ragas) - Evaluation metrics for LLM and RAG applications.

## Test automation frameworks

The foundations most AI testing tools build on or generate code for.

- [Appium](https://appium.io/) - Cross-platform automation for mobile, desktop and other apps over WebDriver.
- [Cypress](https://www.cypress.io/) - JavaScript end-to-end and component testing in the browser.
- [Playwright](https://playwright.dev/) - Browser testing and automation for Chromium, Firefox and WebKit.
- [Selenium](https://www.selenium.dev/) - Browser automation project behind the W3C WebDriver standard.
- [WebdriverIO](https://webdriver.io/) - Node.js framework for browser and mobile automation.

## Practice sites

Public apps built for practising test automation. They are also a safe place to try an AI testing tool before pointing it at your own app.

- [Automation Exercise](https://automationexercise.com/) - E-commerce site with listed test cases and API practice endpoints.
- [DemoQA](https://demoqa.com/) - Forms, widgets, interactions and a book store app.
- [Expand Testing](https://practice.expandtesting.com/) - Practice pages for UI, API and common web patterns.
- [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/) - Public demo of the open-source HR system, with published credentials.
- [ParaBank](https://parabank.parasoft.com/) - Demo online bank from Parasoft.
- [Practice Software Testing](https://practicesoftwaretesting.com/) - Tool shop app with a web UI and a REST API.
- [Restful Booker](https://restful-booker.herokuapp.com/) - Hotel booking REST API for API testing practice.
- [Sauce Demo](https://www.saucedemo.com/) - Demo store from Sauce Labs, with test users that trigger specific bugs.
- [The Internet](https://the-internet.herokuapp.com/) - Pages that reproduce tricky web UI patterns.
- [UI Testing Playground](http://uitestingplayground.com/) - Pages that reproduce automation pitfalls such as dynamic IDs and delayed elements.

## Papers

- [An Empirical Evaluation of Using Large Language Models for Automated Unit Test Generation](https://arxiv.org/abs/2302.06527) - Schäfer et al., 2023. Generates and evaluates unit tests for JavaScript packages with an LLM.
- [Automated Unit Test Improvement using Large Language Models at Meta](https://arxiv.org/abs/2402.09171) - Alshahwan et al., 2024. Reports on LLM-improved unit tests deployed at Meta.
- [Make LLM a Testing Expert](https://arxiv.org/abs/2310.15780) - Liu et al., 2023. Uses an LLM to drive human-like mobile GUI testing.
- [Software Testing with Large Language Models: Survey, Landscape, and Vision](https://arxiv.org/abs/2307.07221) - Wang et al., 2023. Survey of LLM use across testing tasks.

## Communities and learning

- [Association for Software Testing](https://associationforsoftwaretesting.org/) - Non-profit community for testers, which runs the CAST conference.
- [Ministry of Testing](https://www.ministryoftesting.com/) - Testing community with forums, courses and TestBash conferences.
- [r/QualityAssurance](https://www.reddit.com/r/QualityAssurance/) - Reddit community for QA practitioners.
- [r/softwaretesting](https://www.reddit.com/r/softwaretesting/) - Reddit community for software testing.
- [Software Quality Assurance & Testing Stack Exchange](https://sqa.stackexchange.com/) - Questions and answers about testing.
- [Test Automation University](https://testautomationu.applitools.com/) - Free test automation courses, hosted by Applitools.

## Related lists

- [Awesome Test Automation](https://github.com/atinfo/awesome-test-automation) - Test automation frameworks and tools, grouped by language.
- [Awesome Testing](https://github.com/TheJambo/awesome-testing) - General software testing resources.

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md) first.
