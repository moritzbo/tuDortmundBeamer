# 🟢 TU Dortmund Beamer Theme

This is an attempt of making a **TU Dortmund Beamer Theme** which is a LaTeX presentation template that provides a possibility to align with the university’s corporate design. It includes support for official TU colors, clean typography, and custom block styles.

> ✅ This template is self-contained and easy to adapt. Includes examples for blocks, theorems, columns, and more.

---

## 🚀 Features

- TU Dortmund official green (`tugreen`) and orange (`tuorange`) theme options
- Support for additional color variants (`tugreen80`, `CalPolyGreen`)
- Custom block environments:
  - `tublock`, `tuorangeblock`, `blueblock`, `greenblock`, and standard `block`, `alertblock`, `examples`
- Predefined title and section styles
- Easy customization of header color and layout
- Includes a sample presentation to get started quickly

---

## 📦 Requirements

To compile this theme correctly, make sure you have the following installed:

- **LaTeX distribution** (e.g., TeX Live, MiKTeX, MacTeX, ...)
- **Beamer** package
- **XCharter font** (`XCharter.sty`) – required for the font setup:
  - You can install it via your TeX package manager (`tlmgr install xcharter`) or equivalent
- Other packages used:
  - `hyperref`, `tikz`, `siunitx`, `graphicx`, `booktabs`, `mathdesign`, `fontenc`

---

## 📁 Files

- `main.tex` — The main example presentation source
- `beamerthemetuDortmundBeamer.sty` — The theme definition
- `beamercolorthemeTuDortmundBeamer.sty` — TU color setup (easily customizable)
- `beamerinnerthemetuDortmundBeamer.sty` — Inner Theme with custom blocks
- `beamerfontthemetuDortmundBeamer.sty` — Font Theme build around Charter Font 
- `reference.bib` — Example bibliography (optional)
- `preview/` — Folder for screenshots of the theme

---

## 🎨 Customization

You can switch between TU Dortmund’s color options in `beamercolorthemeTuDortmundBeamer.sty`:

```latex
% Bright green
\setbeamercolor{title}{bg=tugreen,fg=white}
\setbeamercolor{frametitle}{bg=tugreen,fg=white}

% Darker variant (uncomment this instead for a muted tone)
%\setbeamercolor{title}{bg=tugreen80,fg=white}
%\setbeamercolor{frametitle}{bg=tugreen80,fg=white}
