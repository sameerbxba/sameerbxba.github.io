# sameerbxba.github.io

The source for [sameerbxba.github.io](https://sameerbxba.github.io), a
personal site covering technology risk, AI governance and delivery work.

## What is here

| file | what it is |
|---|---|
| `index.html` | The site: projects, approach, five co-op terms, background, contact |
| `case-soc2-agent.html` | Case study: an AI agent that reviews SOC 2 reports and cannot act without permission |
| `case-syncbase.html` | Case study: SyncBase, and what happened when I audited my own tool |
| `case-approval-workflow.html` | Case study: an approval workflow redesign at Equitable Life |
| `assets/` | The two governance documents the case studies cite, as PDFs |

## How it is built

Plain HTML and CSS, no framework and no build step. Each page is
self-contained, with its styles inline, so a page can be read from source
without running anything. Fonts come from Google Fonts; everything else is in
this repository. GitHub Pages serves it from `main`.

To view it locally, open `index.html` in a browser, or:

```
python3 -m http.server 8000
```

and visit `http://localhost:8000`.

## The projects it points to

- [soc2-gap-agent](https://github.com/sameerbxba/soc2-gap-agent): the agent in
  the first case study, with its control matrix and tests.
- [portfolio-attestation](https://github.com/sameerbxba/portfolio-attestation):
  a quarterly attestation cycle for an application register, built on the
  same idea about what a system should refuse to count.
- [SyncBase](https://github.com/sameerbxba/syncbase): the alignment hub in the
  second case study, live at
  [syncbase-eight.vercel.app](https://syncbase-eight.vercel.app).
