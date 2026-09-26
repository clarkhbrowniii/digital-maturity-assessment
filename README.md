# Digital Maturity Index

A browser-based assessment for the flexible workspace industry, delivered as a single HTML file.

## Run

Open `digital-maturity-index.html` directly in Chrome or Firefox. No server, installation, or build step is required. An internet connection is needed to load Chart.js from its CDN.

## Assessment

- 20 questions across five capability dimensions
- Completion tracking and submission after all questions are answered
- Dimension averages, maturity stages, deterministic profiles, and a radar chart
- Two lowest-scoring dimensions, with ties resolved in assessment order
- Retake control that clears the current responses

Responses exist only in memory. The application uses no backend, cookies, or browser storage.

## Edit the framework

Questions, stages, profiles, and matching rules are placeholders. Edit the `dimensions`, `stageDefinitions`, `maturityProfiles`, and `profileMatchingRules` data structures in the HTML file. Scoring and rendering functions are kept separately.

`Week 5 Mockup.png` is the visual design reference.

## Validation

JavaScript syntax, question structure, scoring, invalid-response rejection, stage thresholds, profile selection, fallback behavior, and tie handling were checked. Direct-file browser and visual verification remain pending because the automated browser security policy blocked local-file navigation.
