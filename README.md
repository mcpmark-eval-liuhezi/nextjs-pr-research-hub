# nextjs-pr-research-hub

This repository tracks research into **Next.js pull request practices** — a case study of how a large open-source project ( [`vercel/next.js`](https://github.com/vercel/next.js) ) actually runs its pull request process.

It supports an internal talk on the topic and consolidates previously browser-tab-scattered research into one place.

## What's tracked

Research is organized as a parent issue with three sub-issues:

1. **Finding: size and scope of recent changes** — files touched and change size of the most recently updated open pull request.
2. **Finding: review workflow signals** — reviewers, review activity, and CI/check status on that same pull request.
3. **Finding: discussion activity** — the state of the repository's GitHub Discussions.

## Case study snapshot

- **Repository:** [`vercel/next.js`](https://github.com/vercel/next.js) (default branch: `canary`)
- **Most recently updated open pull request:** [#100201 — "docs: fix mismatched filenames, languages and invalid JS in code examples"](https://github.com/vercel/next.js/pull/100201)
- **Headline size:** 37 files changed, +167 / −160 lines, 7 commits — documentation-only, docs-wide consistency cleanup

See the parent issue (`Next.js PR review practices - research tracker`) for the full research log and the sub-issues for detailed observations.
