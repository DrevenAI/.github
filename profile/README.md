# Dreven

AI-assisted accessibility audits you can stand behind.

Dreven audits websites against WCAG 2.2 (or WCAG 2.1, Section 508 or EN 301 549), keeps the evidence behind every result, and drafts an Accessibility Conformance Report in the VPAT 2.5Rev structure. A person decides each result and signs the report.

## What it does

- Give it one address. It finds your site's pages and audits up to 25 together.
- Every result is one of four states: passed, failed, not applicable or can't tell. Can't tell is never counted as a pass.
- Every result keeps its evidence, shown on the page where it was found.
- What needs judgment goes to a person with the evidence.
- A reviewer decides each result, records why, and signs the drafted report.

## What it does not do

- It does not change your site's code and is not an overlay.
- It does not make a site compliant. No automated tool can. A person decides each result.
- It does not sign the report. The reviewer does, under their own name.

## Pages behind a sign-in

The `@dreven/cli` package audits pages from your own computer, inside your own signed-in session, so your password never reaches Dreven. It runs from the command line or as an MCP server for Claude Code and Codex. It is in preview. A Chrome extension that records signed-in pages is in early access and is installed by hand.

- Guide: https://drevenai.com/guides/audit-from-your-machine
- Extension: https://drevenai.com/guides/extension

## Links

- Website: https://drevenai.com
- What an audit covers: https://drevenai.com/accessibility-audit
- VPAT and ACR: https://drevenai.com/vpat
- WCAG 2.2 in plain words: https://drevenai.com/wcag
- Contact: hello@drevenai.com
