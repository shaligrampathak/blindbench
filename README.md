# BlindBench

A private, offline-first workbench for comparing AI model or prompt outputs side by side. Run blind pairwise reviews on the same test cases, record why an answer won, and export a JSON report.

## Why this exists

Student AI demos often show a few hand-picked outputs. BlindBench helps make comparison more repeatable: keep prompts fixed, hide candidate identities during judging, record ties and failures, and save the rationale alongside each decision.

## Run it

1. Open index.html in a modern browser.
2. Choose Load the example set, or import a CSV with prompt, response_a, and response_b columns.
3. Name the candidates in the left panel. Names stay out of the blind review.
4. Judge each case as A, B, Tie, or Both poor. Add a short reason when useful.
5. Download the JSON report when finished.

No server, account, API key, dependencies, or network connection is needed. Session data is saved in the browser local storage. Use Clear this session on a shared device.

## Limits

- Results are directional human judgments on the supplied cases, not a general model ranking.
- Candidate order is randomized for each case; the app does not score outputs automatically.
- No network calls are made. Text is stored only in this browser unless you export the report.

## License

No license is included yet. Add a license that matches how you want others to use, modify, and resell the project before publishing.
