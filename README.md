1. Title

# package-name

2. Description

1–2 sentences:

what it is

what it’s for

(optional) what it’s not for

3. Compatibility

A small bullet list, always in this order:

Runtimes: Node >= X; Browsers: <notes>; Workers/Edge: <notes>

Module format: ESM/CJS

Required globals / APIs: crypto.subtle, CompressionStream, indexedDB, etc.

TypeScript: bundled types / source TS / etc.

4. Goals

3–6 bullets, phrased as outcomes:

“Developer-friendly API…”

“No deps…”

“Returns copies for safety…”

5. Installation

Always the same triple:

npm install <name>

# or

pnpm add <name>

# or

yarn add <name>

6. Usage

Smallest runnable example (the “copy/paste test”)

Common patterns: 2–5 short subsections max (don’t turn this into an API book)

7. Runtime behavior

This is where you put the “how it behaves in different environments” and “what errors look like”.

Use a consistent set of subheadings when relevant:

Node

Browsers / Edge runtimes

Validation & errors

Safety / copying semantics

Caching semantics (if applicable)

8. Tests

This section should answer:

What test types exist? (unit / integration / e2e / type tests)

Where do they run? (Node versions; browser matrix)

Coverage: tool + percentage (and what it measures)

Status claim: “passes on …” (keep it factual)

Example format:

Suite: unit (Node), integration, E2E (Playwright)

Matrix: Chromium / Firefox / WebKit (+ mobile emulation if you do it)

Coverage: c8 — 100% statements/branches/functions/lines (Node)

Notes: any known skips

9. Benchmarks

This should show actual numbers, plus reproduction context.

Minimum content:

How it was run: command

Environment: runtime version + platform

Results: table or block of key ops/s or timings

Disclaimer: results vary by machine

10. License

One line. Always last.
