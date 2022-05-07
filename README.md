# Quarto-RLadies

a dark theme for Quarto slide presentation


## Deploy your slides (GitHub pages)

- ensure your `.qmd` file is named `index.qmd` then render it to generate the needed files and folders
- create a new file `.nojekyll` in the repository [`touch .nojerkyll`]
- create a new file `_quarto.yml` in the repository and add
```
project:
  type: website
  output-dir: docs
```
- render your your index.qmd file again
- commit & push to GitHub
- go to GitHub Pages settings, have `Branch: main` and Select folder `/docs`
- check GitHub Actions to see for deployment status and link








