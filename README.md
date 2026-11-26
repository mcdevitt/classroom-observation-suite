# Classroom Observation Suite

Practical, browser-based tools to help researchers, instructors, faculty developers, and program evaluators decide **how often to observe**, evaluate **what observation protocols actually capture**, and collect clean classroom observation data without server setup.

> **Status:** Early active build. Currently live on GitHub Pages with an observation planning prototype (`observation planer.html`), expanding into dedicated per-protocol HTML tools and companion accuracy/variance utilities.

---

## Why This Suite Exists

Researchers and practitioners often ask a straightforward question—*how many sessions or windows do I need to observe?*—only to get bogged down in dense statistical jargon or rigid rules of thumb that break down when courses vary across topics, schedules, or units.

At the same time, real-world constraints (observer availability, single-day scheduling, skipping exam/push weeks, partial-class visits) are common, and seemingly harmless shortcuts can quietly distort course-wide estimates. Finally, different observation protocols measure very different constructs and have distinct blind spots—so a single one-size-fits-all form rarely fits how each community actually works.

This repository aims to give users:
1. **A clear answer and plain-English reasoning up front** (with deeper assumptions tucked behind optional toggles).
2. **Protocol-aware construct checks** so teams verify fit and blind spots before collecting data.
3. **Standalone, zero-server HTML tools** that can be opened directly via GitHub Pages or downloaded individually.

---

## Current & Planned Tools

### Available Now
* **Observation Planner (`observation planer.html`):** Helps plan how many class sessions to observe given course length, expected session-to-session variation, practical access limits, and study goals, while inspecting protocol constructs/blind spots and generating a copyable rationale.

### Planned Roadmap (Protocol-Specific & Companion Tools)
* **Protocol-Specific Data Collection Apps (Standalone `.html` files):** Tailored interfaces for individual protocols rather than a lowest-common-denominator form—starting with **COPUS** (bridging familiar COPUS spreadsheet workflows with cleaner logging and export) and expanding to other protocols (such as LA-COPUS, TDOP, RTOP, 3D-LOP, UTOP, PLATO, CLASS, Danielson FFT, or custom setups).
* **"What-If" Estimate Accuracy Checker:** Helps evaluate how wide the plausible uncertainty band is around data you have *already* collected—especially when samples are small, clustered, or affected by practical scheduling compromises.
* **Variance & Design Justification Simulator:** Explores course rhythms (e.g., shifting norms, end-of-semester pushes, alternating/biweekly routines), activity clumping, and observer fatigue to support deeper methodological justifications for papers, grants, and reviews.

---

## How to Use

* **Via GitHub Pages:** Open the deployed pages link from this repository once enabled in **Settings → Pages** (no installation or server required).
* **Download a single HTML file:** Download any `.html` file from the repository and open it directly in a modern web browser (Chrome, Edge, Firefox, Safari). Everything runs locally in your browser.

---

## Scope & Disclaimer

* **Decision & Planning Support:** Recommendations and protocol notes are intended to support research planning, instructional reflection, and program evaluation—not to replace formal statistical consultation, IRB review, or local institutional policy.
* **Independent Open-Source Project:** Shared openly under the repository's **MIT** license for educational and research use.

---

## Updating This README

As new protocol-specific HTML apps, simulators, or exports are added to `mcdevitt/classroom-observation-suite`, this file will be updated to document each tool, its inputs/outputs, and how they connect.
