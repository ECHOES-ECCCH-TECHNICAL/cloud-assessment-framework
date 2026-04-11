# Software E2E Testing Tools

End-to-end testing tools.

## Summary

- **Selenium WebDriver** — Widely used open-source framework for automating web browsers and performing functional end-to-end tests using the W3C WebDriver standard.
- **Playwright** — Modern cross-browser end-to-end testing framework maintained by Microsoft, designed for reliable automation of web applications.
- **Cypress** — JavaScript-first end-to-end testing framework that runs inside the browser, aimed at modern single-page applications and rich frontends.
- **Puppeteer** — Node.js library for controlling Chromium and other browsers via DevTools or WebDriver BiDi, often used for lightweight end-to-end tests and browser automation.
- **WebdriverIO** — Open-source automation framework for Node.js that wraps WebDriver and WebDriver BiDi, supporting web, mobile and component testing.
- **TestCafe** — End-to-end testing framework for web applications that does not require WebDriver or browser plugins and runs on Node.js.
- **Nightwatch.js** — Integrated end-to-end testing framework for web applications based on the W3C WebDriver API, with built-in test runner.
- **Galen Framework** — Framework focused on testing layout and responsive design in addition to functional behavior, built on top of Selenium.
- **Appium** — Open-source automation framework for testing native, hybrid and mobile web applications on iOS, Android and other platforms using the WebDriver protocol.

## Selenium WebDriver

- **ID:** `SOFTWARE_E_E_SELENIUM_WEBDRIVER`
- **Dimensions covered:** Functionality (E2E testing).
- **Description:** Widely used open-source framework for automating web browsers and performing functional end-to-end tests using the W3C WebDriver standard.
- **Link:** https://www.selenium.dev

### Additional properties

- **Adoption Likelihood:** High.
- **Type of tool:** End-to-end framework.
- **Interactions:** Mouse clicks, typing into inputs, selecting from menus, form submission, navigation across pages, scrolling, handling alerts and frames.
- **Supported languages (not exhaustive list):** Java, Python, JavaScript, C#, Ruby and others.
- **Target:** Web applications.
- **Advantages:** It is the industry standard, so is extremly matured.
- **Open Source:** It is open-source.
- **Limitations:** Selenium IDE add-on not compatible with some browsers (e.g. Chrome); Selenium IDE add-on might generate volatile event IDs. 
Slower than modern tools.

## Playwright

- **ID:** `SOFTWARE_E_E_PLAYWRIGHT`
- **Dimensions covered:** Functionality (E2E testing).
- **Description:** Modern cross-browser end-to-end testing framework maintained by Microsoft, designed for reliable automation of web applications.
- **Link:** https://playwright.dev

### Additional properties

- **Adoption Likelihood:** High.
- **Type of tool:** End-to-end framework.
- **Interactions:** Mouse clicks and double-clicks, hover, drag and drop, typing, file uploads, multi-tab and multi-page scenarios, mobile emulation.
- **Supported languages (not exhaustive list):** TypeScript, JavaScript, Python, Java, .NET.
- **Target:** Web applications.
- **Advantages:** Fast, reliable, modern API,
It has Auto-waiting and contextual actions.
- **Open Source:** It is open-source.
- **Limitations:** It has a smaller community than others but rapidly growing,
It is primarily JS/TS-centric.

## Cypress

- **ID:** `SOFTWARE_E_E_CYPRESS`
- **Dimensions covered:** Functionality (E2E testing).
- **Description:** JavaScript-first end-to-end testing framework that runs inside the browser, aimed at modern single-page applications and rich frontends.
- **Link:** https://www.cypress.io

### Additional properties

- **Adoption Likelihood:** Low.
- **Type of tool:** End-to-end framework.
- **Interactions:** Clicks, typing, selecting options, navigation, network request stubbing, assertions on DOM state, screenshots and video recording.
- **Supported languages (not exhaustive list):** JavaScript, TypeScript.
- **Target:** Web applications.
- **Advantages:** It has a very friendly developer experience,
It has Auto-waiting,
Tests run in real browser context.
- **Open Source:** It has a free/open-source core but a paid Dashboard for advanced test insights.
- **Limitations:** Doesn't support multiple real tabs/windows well.

## Puppeteer

- **ID:** `SOFTWARE_E_E_PUPPETEER`
- **Dimensions covered:** Functionality (E2E testing).
- **Description:** Node.js library for controlling Chromium and other browsers via DevTools or WebDriver BiDi, often used for lightweight end-to-end tests and browser automation.
- **Link:** https://pptr.dev

### Additional properties

- **Adoption Likelihood:** Medium.
- **Type of tool:** End-to-end framework.
- **Interactions:** Clicks, typing, scrolling, file uploads, interaction with dialogs, capturing screenshots and PDFs, collecting performance metrics.
- **Supported languages (not exhaustive list):** JavaScript, TypeScript (via Node.js).
- **Target:** Web applications.
- **Advantages:** Simple API with fine-grained browser control,
It is great for automation and crawling.
- **Open Source:** It is open-source.
- **Limitations:** It is focused on Chromium,
It is a straightforward API, but requires your own test tooling.

## WebdriverIO

- **ID:** `SOFTWARE_E_E_WEBDRIVERIO`
- **Dimensions covered:** Functionality (E2E testing).
- **Description:** Open-source automation framework for Node.js that wraps WebDriver and WebDriver BiDi, supporting web, mobile and component testing.
- **Link:** https://webdriver.io

### Additional properties

- **Adoption Likelihood:** Medium.
- **Type of tool:** End-to-end framework.
- **Interactions:** Clicks, typing, element selection, scrolling, drag and drop, navigation, assertions, interaction with native browser dialogs.
- **Supported languages (not exhaustive list):** JavaScript, TypeScript.
- **Target:** Web applications.
- **Advantages:** Built on WebDriver but with modern configuration,
It has highly extensible plugins.
- **Open Source:** It is open-source.
- **Limitations:** It has more complex configurations than others.

## TestCafe

- **ID:** `SOFTWARE_E_E_TESTCAFE`
- **Dimensions covered:** Functionality (E2E testing).
- **Description:** End-to-end testing framework for web applications that does not require WebDriver or browser plugins and runs on Node.js.
- **Link:** https://testcafe.io

### Additional properties

- **Adoption Likelihood:** Medium.
- **Type of tool:** End-to-end framework.
- **Interactions:** Clicks, typing, drag and drop, file upload, navigation, screenshots, execution in multiple local and remote browsers.
- **Supported languages (not exhaustive list):** JavaScript, TypeScript.
- **Target:** Web applications.
- **Advantages:** It has a simple setup,
It has Auto-waiting.
- **Open Source:** It is open-source.
- **Limitations:** It has a small community,
It is less powerful than others.

## Nightwatch.js

- **ID:** `SOFTWARE_E_E_NIGHTWATCH_JS`
- **Dimensions covered:** Functionality (E2E testing).
- **Description:** Integrated end-to-end testing framework for web applications based on the W3C WebDriver API, with built-in test runner.
- **Link:** https://nightwatchjs.org

### Additional properties

- **Adoption Likelihood:** Medium.
- **Type of tool:** End-to-end framework.
- **Interactions:** Clicks, navigation, form filling, assertions on DOM elements, screenshot capture, interaction with iframes and windows.
- **Supported languages (not exhaustive list):** JavaScript, TypeScript.
- **Target:** Web applications.
- **Advantages:** Uses Selenium under the hood, but it has a simple configuration compared to raw Selenium.
- **Open Source:** It is open-source.
- **Limitations:** It is less modern and slower than others.

## Galen Framework

- **ID:** `SOFTWARE_E_E_GALEN_FRAMEWORK`
- **Dimensions covered:** Functionality (E2E testing).
- **Description:** Framework focused on testing layout and responsive design in addition to functional behavior, built on top of Selenium.
- **Link:** http://galenframework.com

### Additional properties

- **Adoption Likelihood:** Low.
- **Type of tool:** End-to-end framework.
- **Interactions:** Clicks, navigation and other Selenium-backed interactions, layout checks for element positions and sizes, responsive viewport testing.
- **Supported languages (not exhaustive list):** Java and JavaScript (plus Galen Specs DSL).
- **Target:** Web applications.
- **Advantages:** It is used for visual layout validation and responsive design.
- **Open Source:** It is open-source.
- **Limitations:** It is not a general E2E tool, because needs integration with other test runners.

## Appium

- **ID:** `SOFTWARE_E_E_APPIUM`
- **Dimensions covered:** Functionality (E2E testing).
- **Description:** Open-source automation framework for testing native, hybrid and mobile web applications on iOS, Android and other platforms using the WebDriver protocol.
- **Link:** https://appium.io

### Additional properties

- **Adoption Likelihood:** Medium.
- **Type of tool:** End-to-end framework.
- **Interactions:** Touches and taps, long presses, swipes, scrolls, typing, multi-touch gestures, navigation, interaction with system dialogs and mobile web views.
- **Supported languages (not exhaustive list):** Java, JavaScript, Python, Ruby, C#, PHP and others via client libraries.
- **Target:** Web, mobile, desktop.
- **Advantages:** It is used for mobile testing and web testing via mobile browsers,
It is based on WebDriver.
- **Open Source:** It is open-source.
- **Limitations:** It has a heavy setup, and does slower tests, so it is less convenient for desktop web.
