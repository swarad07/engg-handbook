---
title: Automated testing
weight: 4
description: Nobody likes repetitive tasks. Human beings are usually bad at reliably performing repetitive tasks. If you want to build, deploy, and generally jump to more exciting tasks soon, write automated tests.
---

# Automated Testing

Nobody likes repetitive tasks. Human beings are usually bad at reliably performing repetitive tasks. If you want to build, deploy, and generally jump to more exciting tasks soon, write automated tests.

Broadly, the types of tests are divided based on the scope of what's being tested. Unit tests deal with single units of code (often, these are classes or single components). Functional tests check a part of the system while isolating it from the overall system as much as possible. End-to-end tests check for correctness across the entire system.

Given our style of work, we mostly write functional or end-to-end tests. For this, we have built significant expertise on Behat and Cypress. Additionally, we maintain a set of [template test scripts](https://github.com/contrib-tracker/backend/tree/main/web/themes/custom/contribtracker/cypress/e2e) that are commonly applicable across our projects. These scripts are tagged thoughtfully, enabling us to automatically execute specific tests based on schedules or triggering actions in CI, streamlining the testing process further.
