# Svett Gutt's Cryptic XXXword

Static site, no build step.

## Deploy on GitHub Pages
1. Create a repo and push these files to the root (or keep them in a folder and push that folder's contents).
2. Repo Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Your site appears at `https://<username>.github.io/<repo>/`.

## Customise
- Pop-up images: `image-1`, `image-2`, `image-3` (.png, .jpg, .jpeg or .webp) go in the same folder as the HTML files. Names are case-sensitive.
- Colours: `:root` variables in the `<style>` block of each page.
- The crossword page embeds `crossword.pdf`. Put your PDF in the same folder with exactly that name.
