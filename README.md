# VendorMatch AI
A browser-based supplier identity resolution prototype. Upload a CSV or load fictional sample data, compare supplier names, emails and addresses, review flagged pairs and export results.

## Run
Open `index.html` in a browser or deploy the repository root with GitHub Pages. No dependencies.

## Matching
Normalized name edit similarity contributes 55%, exact nonempty email match 30%, and address edit similarity 15%. Default threshold: 70%. Scores are heuristics, not calibrated probabilities. Human review is required. Maximum 500 suppliers per import. No backend or trained ML model is included.

## Manual test
Load sample data, click Find duplicates and expect two flagged pairs at the default threshold. Export the report. Try an invalid CSV and verify an error appears.

## Technology
HTML, CSS and JavaScript. Data is processed locally in the browser.
