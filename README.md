# Pattern Bench — Day 10

Test JavaScript regular expressions against text, inspect matched values and capture groups, and preview replacements before using them in code.

## Use it

Open `index.html` or use the live demo. Enter a JavaScript regular expression, set flags, and paste sample text. Select **Test pattern** to review matches. Add optional replacement text to preview the output, then copy or download the result.

## Features

- JavaScript `RegExp` syntax with global, case-insensitive, multiline, dotAll, and Unicode flags.
- Match values, character offsets, positional captures, and named groups.
- Replacement preview with JavaScript replacement tokens.
- Copy the matches or replacement output; download replacement text.
- Runs in a temporary browser Web Worker with a time limit to keep slow patterns from freezing the page.
- No account, uploads, analytics, network requests, or external libraries.

## Privacy and limits

Patterns and sample text stay in the browser. Input is limited to 100,000 characters and the result list to 500 matches. Very slow expressions are stopped after a short timeout. This tool uses JavaScript regular-expression behavior, which may differ from other regex engines such as PCRE or Python. It is a debugging aid, not a security scanner.

## GitHub Pages

This is a static single-file app. GitHub Pages can serve it from the repository's `main` branch and root folder.

## Built with

HTML, CSS, JavaScript, and the browser's Web Worker API. MIT License.
