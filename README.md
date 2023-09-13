# automaticResumeGenerator

[![latex2pdf](https://github.com/burnbrian/automaticResumeGenerator/actions/workflows/latex2pdf.yml/badge.svg)](https://github.com/burnbrian/automaticResumeGenerator/actions/workflows/latex2pdf.yml)

You're a busy important person. Very important, very busy. No time for Docker files or build scripts. GitHub actions to the rescue. Use this repository to quickly generate a PDF resume using the LaTex template of your choice. You can accomplish something similar _(read better)_ with [Overleaf.com](https://www.overleaf.com).
## Instructions

1. Click "Use this template" -> "Create a new repository"
2. In your new repository click "Settings (top menu bar)" -> "Actions (left menu bar)" -> "General" 
3. Under "Workflow permissions" select "Read and write permissions" and "Allow GitHub Actions to create and approve pull requests"
4. Modify the information in `resume.tex`

Whenever you make changes to the `resume.tex` file it will trigger a GitHub action to output a PDF version of your resume. Once the build is complete click "Pull Requests (top menu)" -> click an open pull request titled "[CI] LaTex to PDF GitHub action" -> then click "Merge pull request". You should now see a `resume.pdf` in your `main` branch.

## Screenshot

![Screenshot of LaTeX to PDF resume](resume-screenshot.png?raw=true "LaTex to PDF Resume Screenshot")
