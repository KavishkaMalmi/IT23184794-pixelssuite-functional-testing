# Playwright Test Automation Project - IT23184794

This project contains automated end-to-end tests for image preview functionality using Playwright, specifically for the Pixelssuite image converter.

## Prerequisites

- Python 3.8 or higher
- Google Chrome (recommended) or Playwright Chromium

## Installation

1. Install the required Python packages:
   ```bash
   pip install playwright openpyxl
   ```

2. Install Playwright browsers:
   ```bash
   python -m playwright install
   ```

## Running the Tests

To run the image preview tests and generate results:

```bash
python IT23184794_image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --png IT23184794_sample.png --csv IT23184794_execution_results.csv
```

The execution results will be saved to `IT23184794_execution_results.csv` and screenshots will be stored in the `results` directory.

## Repository Link

The full project repository can be found at:
[https://github.com/KavishkaMalmi/IT23184794-pixelssuite-functional-testing](https://github.com/KavishkaMalmi/IT23184794-pixelssuite-functional-testing)
