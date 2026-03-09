# AI Coding Assistants for Positron

A Quarto RevealJS presentation on AI coding assistants available in Positron, created for the [emLab](https://emlab.ucsb.edu/) Study Club at UC Santa Barbara.

## Overview

This presentation covers:

- What Positron is and how it differs from RStudio
- The landscape of AI coding assistants available in Positron (Positron Assistant, Positron Databot, Claude Code, GitHub Copilot)
- How to choose between LLM backends (Claude, Copilot, etc) and their trade-offs
- Billing models for Claude API vs. Claude Code vs. GitHub Copilot
- Advanced customization via `instructions.md`, `prompts.md`, `agents.md`, and `skills.md`
- Best practices for responsible, human-in-the-loop AI use

## View the Presentation

**Live:** [https://gmcdonald-sfg.github.io/ai-coding-assistants-positron](https://gmcdonald-sfg.github.io/ai-coding-assistants-positron)

## Local Development

### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/) ≥ 1.4
- [R](https://www.r-project.org/) ≥ 4.0

### Render & Preview

```bash
# One-off render
quarto render

# Live-reload preview
quarto preview
```

Rendered output is written to `docs/`.

## Project Structure

```
.
├── index.qmd                  # Slide content (RevealJS)
├── _quarto.yml                # Quarto project configuration
├── dracula.scss               # Custom Dracula theme for RevealJS
├── styles.css                 # Additional CSS overrides
├── images/                    # Static images used in slides
├── docs/                      # Rendered HTML output (GitHub Pages)
└── .github/workflows/
    └── publish.yml            # CI: render + deploy to GitHub Pages on push to main
```

## Automatic Publishing

Pushing to `main` triggers a GitHub Actions workflow that:

1. Renders the Quarto project with Quarto 1.4 and R 4.3
2. Uploads the `docs/` directory as a Pages artifact
3. Deploys to GitHub Pages

## Editing

| What you want to change | Where to edit |
|---|---|
| Slide content | `index.qmd` |
| RevealJS theme / colors | `dracula.scss` |
| Additional CSS | `styles.css` |
| Quarto project settings | `_quarto.yml` |
| CI/CD pipeline | `.github/workflows/publish.yml` |

## Resources

- [Quarto Presentations](https://quarto.org/docs/presentations/)
- [RevealJS in Quarto](https://quarto.org/docs/presentations/revealjs/)
- [Positron IDE](https://positron.posit.co/)
- [Posit AI Newsletter](https://posit.co/blog/2026-02-13-ai-newsletter/)
- [R LLM Benchmark](https://skaltman-model-eval-app.share.connect.posit.cloud)

## License

Open source, available for educational purposes.
