# COPE: Chrome Extension for LLM Web Interaction

## Overview

COPE is a Chrome browser extension designed to enhance interaction with large language model (LLM) web interfaces, including ChatGPT and Perplexity. The extension enables structured web-based workflows and interface augmentation for research and usability studies.

This repository is provided as an anonymized submission for academic review.

---

## Anonymous Code Repositories

To comply with double-blind review requirements, two separate anonymized repositories are provided:

- ChatGPT-adapted version:  
  https://anonymous.4open.science/r/COPE_anonymous-gpt

- Perplexity-adapted version:  
  https://anonymous.4open.science/r/COPE_anonymous-perplexity

Each version corresponds to platform-specific adaptations of the same core extension architecture.

---

## Build Instructions

Install dependencies:

```bash
npm install
```

Build the extension:

```bash
npm run build
```

After building, a `dist/` directory will be generated.

---

## Installation (Chrome Extension)

To load the extension locally:

1. Open Chrome and navigate to:
   ```
   chrome://extensions/
   ```

2. Enable **Developer Mode** (top right corner)

3. Click **Load unpacked**

4. Select the generated `dist/` folder

The extension will then be installed and available in the browser.

---

## Compatibility Notice

This extension has been developed and tested against the ChatGPT and Perplexity web interfaces as of December 17, 2025.

Due to the rapidly evolving nature of these platforms, future interface or backend changes may introduce incompatibilities or require further adaptation.

---

## Repository Scope

This repository is released solely for academic evaluation under anonymized conditions. Identifying metadata and commit history have been minimized where possible to preserve double-blind review integrity.

---

## License

This project is released under the MIT License.
