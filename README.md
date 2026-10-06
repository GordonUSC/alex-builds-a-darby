# Alex Builds a Darby

Static, personal OpenClaw guide for Alex Rogers. No build process, third-party scripts, web fonts, analytics, or runtime dependencies.

## Preview

Run `python3 -m http.server 8765 --bind 127.0.0.1` in this directory, then open `http://127.0.0.1:8765`.

The site consists of `index.html`, `style.css`, `app.js`, and `assets/rooster-original.jpg`. Keep these relative paths together when publishing to the existing GitHub Pages location.

## Progress

This edition uses `alex-darby-build-v2` browser storage. It preserves the original `alex-darby-build-v1` records and explains why changed instructions require fresh review. Reset affects only the current edition. No questions, prompts, or account credentials are stored by this page.

## Checks

`node --check app.js`

`node tests/browser.cjs` exercises an existing Playwright runtime and Chrome. Set `PLAYWRIGHT_PATH` and `CHROME_PATH` for another environment. A local server must be running on port 8765. Test evidence is written to the ignored `review/` directory. The original baseline is recovered from git when absent.

Commands on the page are documentation, not executed as part of tests. Documentation checked October 6, 2026. Runtime requirements and provider options can change; linked official guides are authoritative. No install, provider login, credential edit, deployment, or send is part of verification.
