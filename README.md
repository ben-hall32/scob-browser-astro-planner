# SCOB Night-Sky Dashboard v3.6 - Astronomy Planning Web App 2026

> **A compact web dashboard for astronomy and stargazing sessions, made for browser use, PWA installation, and offline access in version 3.6.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v3.6-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ben-hall32/scob-browser-astro-planner?style=flat-square)](https://github.com/ben-hall32/scob-browser-astro-planner)

---

<p align="center">
  <a href="https://ben-hall32.github.io/scob-browser-astro-planner/">
    <img src="https://img.shields.io/badge/Download-SCOB%20Night-Sky%20Dashboard%20Latest-brightgreen?style=for-the-badge" alt="Download SCOB Night-Sky Dashboard">
  </a>
</p>

> **[Direct Download - SCOB Night-Sky Dashboard v3.6](https://ben-hall32.github.io/scob-browser-astro-planner/)**

---

[Download Latest Build](https://ben-hall32.github.io/scob-browser-astro-planner/)

---

## What is SCOB Night-Sky Dashboard?

SCOB Night-Sky Dashboard is a browser-first astronomy planning tool that helps stargazers assemble the key details for an observing run in one compact place. It combines weather outlooks, object context, and visibility planning so you can assess the night before leaving home.

It works well for observers who want a quick, lightweight way to check conditions, compare possible targets, and prepare a simple observing summary. Thanks to offline operation, PWA support, and a single-file style layout, it suits both mobile and desktop setups where fast access is important.

---

## What you get

- Offline single-file dashboard for convenient browser use
- Live weather forecast with cloud timeline for session planning
- Sky map covering planets, the Moon, the Sun, and constellations
- Moon phase information with rise/set and terminator details
- Deep-sky target ranking with visual and imaging verdicts
- ISS and satellite pass predictions for pass timing
- Print-friendly briefing and session run-sheet output
- PWA install support with cached offline access

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/ben-hall32/scob-browser-astro-planner.git
2. Open the project folder and launch the main HTML file in a web browser.
3. If you prefer app-like access, install it as a PWA from the browser when prompted or through the browser menu.

For the hosted build, use the download link above and open the latest version in your browser.

---

## How to use it

Open the dashboard before an observing session to review weather, cloud cover, and sky visibility at a glance. Use the sky map and object panels to compare planets, the Moon, the Sun, constellations, and deep-sky targets while planning your route through the night sky.

Typical workflow:

1. Check the forecast and cloud timeline.
2. Review moon phase, rise/set, and terminator position.
3. Inspect deep-sky target rankings for visual or imaging goals.
4. Look for ISS or satellite passes if you want to include them in the session.
5. Print or save the session briefing for later use in the field.

---

## Configuration

Most settings are expected to live in the dashboard itself or in browser storage used by the app. If you are self-hosting or customizing the file, review the HTML content and any embedded script values for location, observation preferences, and display behavior.

A simple example of the sort of app-side settings you may adjust:

    {
      "location": "your observing site",
      "timeFormat": "local",
      "targets": "deep-sky, moon, planets",
      "offlineMode": true
    }

---

## Requirements

- A modern web browser
- HTML support for opening the dashboard locally or from a hosted page
- Enough local storage or browser cache space for offline and PWA use
- Internet access for live weather and updated pass data when using online features

---

## FAQ

**How do I update the dashboard?**  
Swap in the newest build for your local copy, or reopen the hosted version if you are using the published link.

**Does it work offline?**  
Yes. After the first load, the dashboard is built for cached offline use, including PWA installation where the browser supports it.

**Where are my settings saved?**  
Persistent preferences are expected to stay in the browser or the app's local storage, depending on how the dashboard is deployed.

**What should I do if weather or pass data does not load?**  
Verify your connection, reload the page, and make sure the data source or browser cache is reachable. If you are offline, only cached content will be available.

**Can I use it for printing observing notes?**  
Yes. The project includes a print-friendly briefing and session run-sheet format intended for field use.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
