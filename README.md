# automaticResumeGenerator

You're a busy important person. Very important, very busy. No time for Docker files or build scripts. GitHub actions to the rescue. Use this repository to quickly generate a PDF resume using your LaTex template of choice.

## Instructions

1. Click "Use this template" -> "Create a new repository"
2. In your new repository click "Settings (top menu bar)" -> "Actions (left menu bar)" -> "General" 
3. Under "Workflow permissions" select "Read and write permissions" and "Allow GitHub Actions to create and approve pull requests"
4. Create an account and download your favorite `.tex` template from [Overleaf](https://www.overleaf.com/latex/templates/tagged/cv)
5. Replace the `.tex` file in your repository with the `.tex` file of your choice

Whenever you make changes to the `.tex` file in your new repository it will trigger a GitHub action to output a PDF version of your resume. Once the build is complete click "Pull Requests (top menu)" -> click an open pull request titled "[CI] LaTex to PDF Action GitHub action" -> then click "Merge pull request". You should now see your PDF resume in your repository.

## Screenshot

![Screenshot of LaTeX to PDF resume](resume-screenshot.png?raw=true "LaTex to PDF Resume Screenshot")
