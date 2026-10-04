# TOFIX

Findings from a code scan on 2026-10-04.

## Low

- `README.md:2` - the README only says "demos for the chrome web browser"; the repo's single demo, `run_chrome_headless.sh`, is not mentioned, nor what to point at the debugging port (lighthouse/puppeteer per `run_chrome_headless.sh:3-4`). Document the script and its usage.
