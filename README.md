# Dinda Mutiara Sukmaningrum, Portfolio

A static site: one `index.html`, no build step, no backend, no paid services.

## Edit
- **Contact links:** open `index.html`, change `EMAIL` near the bottom. To add LinkedIn or GitHub later, add another link in the `#clist` block.
- **Projects:** each project is an `<article class="card">` in the `#projects` section. Edit the title, business question, dataset, methods, key findings, tools and the Colab `href`. The matching case study is the `<details class="case">` block below the cards. Fields marked `class="edit"` are placeholders to replace.
- **Check the notebook order:** the cards assume Colab link 1 = Mental Disorder, 2 = RFM, 3 = Health Insurance. Swap titles if your links map differently.
- **Colors:** change the variables at the top of the `<style>` block.

## Preview
Open `index.html` in a browser.

## Publish on GitHub Pages (free)
1. Create a GitHub repository (for example `dinda-portfolio`) and upload `index.html`, the `assets` folder (certificate image) and `README.md`.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. After a minute your site is live at `https://YOUR-USERNAME.github.io/dinda-portfolio/`.

## Before publishing
- [ ] Confirm project 1/2/3 match the right notebooks
- [ ] Replace the "Add your own..." placeholders (recommendations, limitations)
- [ ] Review the key findings against your notebooks
- [ ] Optionally add a `<link rel="canonical">` once you know your URL
