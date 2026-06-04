[![Follow on GitHub](https://img.shields.io/github/followers/fernandotonacoder?label=Follow&style=social)](https://github.com/fernandotonacoder)
[![Website](https://img.shields.io/badge/visit-website-green?logo=gnometerminal)](https://fernandotonacoder.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/fernandotona/)
# Resume template written with LaTeX

🎓 A clean and customizable one-page LaTeX resume template for developers and tech professionals.

## Features

- A4 format with compact layout
- Modern, minimalist design
- Well-structured sections (Skills, Experience, Education, Projects, etc.)
- Custom sidebar line for grouped experience (e.g., multiple roles in same company)
- Fully customizable: colors, fonts, spacing

## Preview

📄 [Sample PDF](./main.pdf)

## Getting Started

### Option A — VS Code with LaTeX Workshop

1. Install the [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension by James Yu.
2. The project already includes a `.vscode/settings.json` that configures XeLaTeX as the compiler — no extra setup needed.
3. Open `main.tex` and save the file. The PDF preview will open automatically on the side.

> **Tip:** Use **Ctrl+Click** on the PDF to jump to the corresponding line in the source (SyncTeX). Use **Ctrl+Alt+J** in the `.tex` file to jump to the corresponding position in the PDF.

### Option B — Local (Linux / macOS / Windows)

This template uses `fontspec`, so it must be compiled with **XeLaTeX** (not `pdflatex`).

**Linux (Ubuntu/Debian):**

```bash
sudo apt install texlive-xetex texlive-fonts-extra
xelatex main.tex
```

> **Note:** The template uses `Liberation Sans` as the main font (a free, metric-compatible substitute for Arial). If you want to use Arial instead, install the Microsoft core fonts first:
> ```bash
> sudo apt install ttf-mscorefonts-installer
> ```
> Then change line `\setmainfont{Liberation Sans}` back to `\setmainfont{Arial}` in `main.tex`.

**macOS:**

```bash
brew install --cask mactex
xelatex main.tex
```

**Windows:**

Install [MiKTeX](https://miktex.org/) or [TeX Live](https://tug.org/texlive/), then run:

```
xelatex main.tex
```

The output `main.pdf` will be generated in the same directory.

### Option C — Overleaf (easier, no local setup)

1. Import the project ([main.tex](./main.tex) file) to [Overleaf](https://www.overleaf.com/).
2. Go to **Menu → Compiler** and select **XeLaTeX** (the default `pdflatex` will fail).
3. Compile and preview directly in the browser.
## Author

**Fernando Tona**  
[Website](https://fernandotonacoder.github.io) • [LinkedIn](https://www.linkedin.com/in/fernandotona/) • [GitHub](https://github.com/fernandotonacoder)

<div align="center">

**⭐ Star this repo if you find it useful!**

Made with ❤️ by Fernando Tona

</div>