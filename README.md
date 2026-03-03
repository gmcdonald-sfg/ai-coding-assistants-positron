# AI Tools for Academic Research

A Quarto-based presentation summarizing AI tools for academic research, focused on data science, fisheries, remote sensing, machine learning, economics, and econometrics.

## 🎯 Purpose

This presentation is designed for researchers at the environmental Markets Lab (emLab) at UCSB and others interested in leveraging AI tools for academic research.

## 🚀 Quick Start

### View the Presentation

Visit the live presentation at: [https://gmcdonald-sfg.github.io/ai-for-research/](https://gmcdonald-sfg.github.io/ai-for-research/)

### Local Development

#### Prerequisites

- [R](https://www.r-project.org/) (version 4.0 or higher)
- [Quarto](https://quarto.org/docs/get-started/) (version 1.4 or higher)

#### Render Locally

```bash
# Render the presentation
quarto render

# Preview with live reload
quarto preview
```

The rendered HTML will be in the `docs/` directory.

## 📂 Project Structure

```
.
├── index.qmd              # Main presentation file
├── _quarto.yml            # Quarto configuration
├── styles.css             # Custom styling
├── .github/workflows/     # GitHub Actions for auto-publishing
└── README.md              # This file
```

## 🔄 Automatic Publishing

This repository uses GitHub Actions to automatically render and publish the presentation to GitHub Pages when changes are pushed to the `main` branch.

## ✏️ Editing the Presentation

1. Edit `index.qmd` to modify content
2. Update `_quarto.yml` for configuration changes
3. Customize `styles.css` for styling
4. Commit and push to `main` branch
5. GitHub Actions will automatically build and deploy

## 🎨 Customization

- **Theme**: Modify the `theme` in `index.qmd` (options: beige, blood, dark, league, moon, night, serif, simple, sky, solarized)
- **Colors**: Edit `styles.css` to match your branding
- **Content**: Add or remove slides in `index.qmd`

## 📚 Resources

- [Quarto Documentation](https://quarto.org/)
- [Quarto Presentations](https://quarto.org/docs/presentations/)
- [RevealJS Features](https://quarto.org/docs/presentations/revealjs/)

## 🏛️ About emLab

The environmental Markets Lab (emLab) at UC Santa Barbara is dedicated to using economics and data science to improve environmental outcomes.

## 📝 License

This project is open source and available for educational purposes.
