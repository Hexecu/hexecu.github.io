# Davide Leopardi — Portfolio

Static portfolio for **Davide Leopardi / Hexecu**, designed for GitHub Pages.

## Positioning

> I build the systems around the model that make AI agents reliable in production.

The site emphasizes:

- AI agent harness engineering
- LangGraph and multi-agent orchestration
- evaluation, quality gates, and deterministic verification
- persistent memory and context engineering
- enterprise RAG and document intelligence
- knowledge-graph reasoning
- forward-deployed and customer-facing engineering
- public MCP projects and merged open-source contributions

## Local preview

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Publish as a GitHub user site

Create a public repository named exactly:

```text
Hexecu.github.io
```

Then push the contents of this directory to its `main` branch:

```bash
git init
git add .
git commit -m "feat: launch personal AI engineering portfolio"
git branch -M main
git remote add origin git@github.com:Hexecu/Hexecu.github.io.git
git push -u origin main
```

The intended public URL is:

```text
https://hexecu.github.io/
```

## Before publishing

Review `CONTENT_AUDIT.md`. It separates public-verifiable claims, CV-grounded proprietary work, and claims that would benefit from an external evidence link.

## Files to personalize

- `index.html`: all portfolio content
- `styles.css`: design tokens and responsive layout
- `assets/og-card.svg`: social sharing preview
- `sitemap.xml`: canonical site URL

## Privacy and confidentiality

The enterprise case studies intentionally remain at architectural level. Do not add customer names, internal repository names, confidential metrics, production endpoints, credentials, or implementation details that are not already approved for public disclosure.
