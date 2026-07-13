# ContractDiff — Contract Version Comparison Tool

A lightweight, browser-based tool to compare two versions of a contract and highlight exactly what changed — additions, deletions, and unchanged lines.

Built with vanilla JavaScript, HTML5, and CSS3. No frameworks, no dependencies, no backend required.

## Features

- **Line-by-line diff** using the LCS (Longest Common Subsequence) algorithm
- **Visual highlights** — green for added lines, red for removed lines
- **Change summary** — shows count of lines added, removed, and total compared
- **Works entirely in the browser** — no data leaves your machine
- **Responsive design** — works on desktop and mobile

## How to Use

1. Open `index.html` in any browser
2. Paste the original contract in the left panel
3. Paste the revised contract in the right panel
4. Click **Compare Contracts**
5. Review the highlighted diff output

## Live Demo

[View on GitHub Pages](https://YOUR-USERNAME.github.io/contract-diff-tool)

## Tech Stack

- JavaScript (ES6+) — LCS diff algorithm, DOM manipulation
- HTML5 — Semantic structure
- CSS3 — Responsive layout, visual diff highlighting

## Algorithm

The diff engine uses the **Longest Common Subsequence (LCS)** dynamic programming algorithm to find the minimum set of changes between two documents — the same approach used by tools like `git diff`.

## Use Cases

- Comparing contract drafts before signing
- Reviewing changes made by the other party
- Auditing version history of agreements
- Legal document review workflows

## Author

Janhavi S. Kulkarni — [github.com/YOUR-USERNAME](https://github.com/janhaviik )

## License

MIT License — free to use, modify, and distribute.
