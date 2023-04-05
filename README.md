# Demonstrate an issue linking from slides to website

## Steps

1. Create the project

  ```
  quarto create-project --type=website
  ```

2. Create a slides directory with `_metadata.yml` which overrides the format of the
   directory's contents to `revealjs`.
3. Link from a slide to any non-slide QMD file.
4. Render or preview the site

  ```
  quarto preview
  ```

5. View the slide deck, and click the "Go home" link
6. Observe the browser shows plaintext instead of expected HTML, and the URL bar says
   `/slides/test.qmd` instead of the expected `slides/test.html`.
