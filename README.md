# ApexType v2026 - Personality assessment 2026

> **A browser-based strengths assessment that identifies a user's core personality archetype and creates a personalized career-oriented roadmap in ApexType v2026.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/owen-millermbv6811/apextype-archetype-assessment?style=flat-square)](https://github.com/owen-millermbv6811/apextype-archetype-assessment)

---

<p align="center">
  <a href="https://owen-millermbv6811.github.io/apextype-archetype-assessment/">
    <img src="https://img.shields.io/badge/Download-ApexType%20Latest-brightgreen?style=for-the-badge" alt="Download ApexType">
  </a>
</p>

> **[Download ApexType v2026](https://owen-millermbv6811.github.io/apextype-archetype-assessment/)**

---

[Download Latest Build](https://owen-millermbv6811.github.io/apextype-archetype-assessment/)

---

## Overview

ApexType provides an online way to examine personality and natural strengths through a structured, browser-based assessment. Users answer 50 guided questions and receive an archetype based on the assessment's scoring model.

The results go beyond a single category by combining archetype discovery with career-focused guidance and a tailored roadmap. Chart.js visuals help present the outcome clearly, and the scoring logic and relationships between archetypes can be modified for other assessment models.

---

## What It Includes

- A guided assessment containing 50 personality and strengths questions
- Identification of the user's primary core-strengths archetype
- Seven high-level strengths archetypes
- Twenty-one combinations of subtypes for more detailed results
- Personalized roadmap information after completing the assessment
- Chart.js-based result visualizations
- Optional result submission by email through a webhook
- Compatibility with static hosting on GitHub Pages
- Editable scoring logic and archetype relationships

---

## Getting Started

ApexType uses HTML and JavaScript, so it can run as a static web project.

1. Download the repository and enter its directory:

   ```bash
   git clone https://github.com/owen-millermbv6811/apextype-archetype-assessment.git
   cd REPO
   ```

2. Serve the project with a local web server, or publish the repository through GitHub Pages.
3. Open the local server address, or load the deployed GitHub Pages URL in a modern browser.

For a fast local test, run any static file server supported by your system with the repository root as its serving directory.

---

## Running an Assessment

1. Open ApexType in a web browser.
2. Answer all 50 questions.
3. Inspect the resulting strengths archetype and subtype combination.
4. Review the summary generated with charts.
5. Use the roadmap as a basis for career-oriented exploration.
6. When the feature is enabled, send the result using the configured email webhook.

---

## Customization

The assessment's questions, scoring behavior, archetype definitions, and result content can be changed through the project's JavaScript configuration or data definitions. Common adjustments include:

- Question text and available responses
- Values assigned to individual answers
- Archetype thresholds and mapping logic
- Subtype definitions and combinations
- Roadmap wording and other result content
- Settings for the email submission webhook

A configuration may follow this general shape:

```js
const assessmentConfig = {
  questions: [],
  archetypes: [],
  subtypes: [],
  roadmap: {},
  emailWebhook: ""
};
```

When making changes, follow the configuration structure already used by the project. Scoring values and archetype mappings must remain coordinated to ensure that calculated results continue to match the intended categories.

---

## Requirements and Hosting

To use or deploy ApexType, you need:

- A modern web browser
- Support for HTML and JavaScript
- Chart.js for displaying result charts
- Google Apps Script for the email submission workflow, when that workflow is used
- A static hosting service such as GitHub Pages
- Internet access for externally loaded scripts and webhook requests
- No dedicated server for the assessment itself, since it runs in the browser

---

## Frequently Asked Questions

### What kind of user is ApexType designed for?

ApexType is intended for people who want to explore personality traits, strengths, archetypes, and potential career directions with an online guided assessment.

### What files or data should I change to revise the assessment?

Update the question data, scoring rules, archetype mappings, and roadmap content used by the project. Afterward, run through the full question sequence and verify that each result still maps to the expected categories.

### Are the archetype results configurable?

Yes. The scoring system and archetype mappings are intended to be adjusted. This includes both the seven main archetypes and their subtype combinations.

### How does ApexType present the outcome?

The browser displays chart-based result summaries together with personalized roadmap content.

### What is needed for email result submissions?

Set up the project's email submission webhook. If the deployment uses Google Apps Script, confirm the script endpoint and its required configuration before making the assessment available.

### What should I investigate if the page is broken?

Check that the project is being served from the correct directory and that the JavaScript files and Chart.js load successfully. Also verify any configured webhook URL. Browser developer tools can reveal missing assets and JavaScript errors.

### Where can I get newer versions?

Pull current changes from the repository, or use the published build at [Download Latest Build](https://owen-millermbv6811.github.io/apextype-archetype-assessment/).

---

## License

This project is available under the GNU GPL v3.0. See [LICENSE](LICENSE) for the complete license details.
