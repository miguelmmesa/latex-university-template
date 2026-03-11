# UNIE LaTeX Academic Template

![GitHub repo size](https://img.shields.io/github/repo-size/miguelmmesa/latex-university-template)
![GitHub last commit](https://img.shields.io/github/last-commit/miguelmmesa/latex-university-template)
![GitHub license](https://img.shields.io/github/license/miguelmmesa/latex-university-template)
![LaTeX](https://img.shields.io/badge/Built%20with-LaTeX-blue)
![Academic Template](https://img.shields.io/badge/Template-Academic%20Writing-green)

Professional **modular LaTeX template** designed for academic writing such as:

* University reports
* Technical documentation
* Final Degree Projects (TFG)
* Research papers
* Engineering documentation

The template has been designed to **separate structure, content, and style**, allowing the author to focus entirely on writing.

---

# Use this Template

You can use this repository as a starting point for your own academic projects.

1. Click the **Use this template** button at the top of the repository.
2. Create your own copy of the project.
3. Start writing immediately.

This allows you to reuse the entire structure without modifying the original repository.

---

# Features

* Institutional academic cover
* Modular project architecture
* Automatic table of contents
* Lists of figures, tables, code and algorithms
* Professional typography
* Bibliography with BibLaTeX (APA style)
* Acronym management
* Code and algorithm environments
* Ready for GitHub + Overleaf workflows

---

# Project Structure

```
latex-university-template/

main.tex

00_config/
01_frontmatter/
02_chapters/
03_figures/
04_tables/
05_bibliography/
06_appendices/
07_styles/
08_acronyms/
```

### Folder purpose

| Folder          | Purpose                           |
| --------------- | --------------------------------- |
| 00_config       | Global configuration and packages |
| 01_frontmatter  | Cover page, dedication, abstract  |
| 02_chapters     | Main document chapters            |
| 03_figures      | Images and logos                  |
| 04_tables       | Tables                            |
| 05_bibliography | References (.bib)                 |
| 06_appendices   | Appendices                        |
| 07_styles       | Typography and document style     |
| 08_acronyms     | Acronym definitions               |

---

# Quick Start

Clone the repository:

```
git clone https://github.com/miguelmmesa/latex-university-template.git
```

Open the project with:

* **Overleaf**
* **VSCode + LaTeX Workshop**
* **TeXStudio**
* **TeXmaker**

Edit the configuration file:

```
00_config/config.tex
```

Here you can configure:

* author
* title
* supervisor
* university
* academic year

Write the document inside:

```
02_chapters/
```

---

# Open in Overleaf

You can easily use this template in Overleaf.

1. Download the repository as a ZIP file.
2. Go to **Overleaf**.
3. Click **New Project → Upload Project**.
4. Upload the ZIP file.

Overleaf will recreate the entire folder structure automatically.

---

# Example Output

You can preview the generated document here:

[View Example PDF](latex-template-example.pdf)

This template generates professional academic documents with:

* consistent formatting
* institutional structure
* automatic references
* structured chapters and sections

---

# Continuous Compilation

This repository includes **GitHub Actions** to automatically compile the LaTeX document.

Each time a change is pushed to the repository, GitHub will:

1. Compile the LaTeX project
2. Generate the PDF
3. Upload it as a downloadable artifact

You can view the compilation results in the **Actions** tab.

---

# Author

Miguel Ángel Martín Mesa
Computer Engineering Student
UNIE University

Areas of interest:

* Software Engineering
* System Architecture
* Technical Documentation
* Professional Knowledge Systems

This repository is part of a broader effort to build a **professional digital ecosystem**, including:

* LinkedIn professional presence
* GitHub technical portfolio
* Personal website (in development)
* Technical documentation projects

Contact Info: https://linktr.ee/miguelmmesa

---

# License

MIT License
