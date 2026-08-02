# Codebook & Survey Tidier - Survey Data Cleaning and Documentation Tool 2026

> **Codebook & Survey Tidier is a browser-based utility that turns survey exports into cleaner datasets, organized documentation, and SPSS-ready syntax, with file processing performed locally.**

[![Platform](https://img.shields.io/badge/Platform-Browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hayesryan1964/codebook-survey-cleaner?style=flat-square)](https://github.com/hayesryan1964/codebook-survey-cleaner)

---

<p align="center">
  <a href="https://hayesryan1964.github.io/codebook-survey-cleaner/">
    <img src="https://img.shields.io/badge/Download-Codebook%20%26%20Survey%20Tidier%20Latest-brightgreen?style=for-the-badge" alt="Download Codebook & Survey Tidier">
  </a>
</p>

> **[Download Codebook & Survey Tidier](https://hayesryan1964.github.io/codebook-survey-cleaner/)**

---

[Download Latest Build](https://hayesryan1964.github.io/codebook-survey-cleaner/)

---

## Overview

Codebook & Survey Tidier provides a single workflow for making exported survey data more consistent, interpretable, and ready for research use. It is intended for humanities and social science projects and works with survey exports in CSV or XLSX format, including files produced by widely used online form platforms.

The browser application combines data cleanup with documentation generation. It creates usable variable identifiers, preserves the original survey questions as labels, turns checkbox answers into individual fields, and prepares files for analysis and archiving. All processing happens locally in the browser, so survey files do not need to be uploaded to a remote service.

---

## Capabilities

- Reworks survey headers into standardized variable identifiers.
- Retains the full survey questions as variable labels.
- Expands checkbox responses into separate binary columns.
- Builds SPSS syntax containing variable labels and value labels.
- Saves cleaned survey data as CSV.
- Produces Markdown codebooks for human-readable documentation.
- Generates Data Package JSON for structured metadata exchange.
- Flags missing values and columns whose values remain constant.
- Handles survey files in the browser without uploading the data.
- Accepts CSV and XLSX survey exports.

---

## Getting Started

Codebook & Survey Tidier runs directly in a web browser.

1. Open the current build:

   [Launch Codebook & Survey Tidier](https://hayesryan1964.github.io/codebook-survey-cleaner/)

2. Have a CSV or XLSX survey export ready.
3. Import the file through the application.
4. Examine the fields detected by the tool and the resulting cleaning information.
5. Save whichever outputs are required, including the cleaned dataset, codebook, SPSS syntax, or Data Package JSON.

To run a local copy, clone the repository and serve its files through a static web server. Then visit the local address in a modern browser.

---

## Workflow

The usual process is:

1. Export the responses from the relevant form platform.
2. Open Codebook & Survey Tidier in a browser.
3. Load the CSV or XLSX file.
4. Check the generated variable identifiers and the preserved question labels.
5. Review checkbox expansion, missing-value indicators, and constant-column warnings.
6. Export the cleaned CSV.
7. Create a Markdown codebook for project records.
8. Generate SPSS syntax if the dataset will be used in SPSS.
9. Produce Data Package JSON when structured metadata is needed.

This approach keeps the wording of the original questions available as labels while supplying concise identifiers that are easier to use in analysis.

---

## Settings and Processing

The standard browser workflow has no separate configuration file. Choose the input and desired output formats in the application, then inspect the generated results before saving them.

Since the tool operates client-side, the active dataset is processed within the browser during the session instead of being transmitted to an upload service.

---

## Requirements

- A modern browser with JavaScript enabled.
- A survey export in CSV or XLSX format.
- Sufficient browser memory for the dataset size.
- Optional: SPSS to execute the generated syntax.
- Optional: a text editor or Markdown viewer for opening generated codebooks.

---

## Frequently Asked Questions

### Which input formats are supported?

You can import survey data saved as CSV or XLSX.

### What files can the application create?

Available outputs include a cleaned CSV dataset, a Markdown codebook, SPSS syntax containing variable and value labels, and Data Package JSON.

### Can checkbox responses be handled?

Yes. Checkbox questions can be expanded into separate binary columns to support analysis.

### Are my survey files uploaded anywhere?

No upload is required. The cleaning process runs locally inside the browser.

### Is this appropriate for humanities and social science datasets?

Yes. The tool is designed around cleaning, labeling, and documenting research data in those areas.

### What should I check before exporting?

Review the generated identifiers and labels, along with any missing-value flags and constant-column notices, before saving the final outputs.

### How can I find newer versions?

Open the latest build using the link near the top of this README, and consult the repository for subsequent releases or changes.

### Is there a configuration file?

No separate settings file is needed for the normal browser-based workflow. The available choices are made through the application interface.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
