# Dinda Mutiara Sukmaningrum, Portfolio

A static site: one `index.html`, no build step, no backend, no paid services.

## Edit
- **Contact links:** open `index.html`, change `EMAIL` near the bottom. To add LinkedIn or GitHub later, add another link in the `#clist` block.
- **Projects:** each project is an `<article class="card">` in the `#projects` section. Edit the title, business question, dataset, methods, key findings, tools and the Colab `href`. The matching case study is the `<details class="case">` block below the cards. Fields marked `class="edit"` are placeholders to replace.
- **Check the notebook order:** the cards assume Colab link 1 = Mental Disorder, 2 = RFM, 3 = Health Insurance. Swap titles if your links map differently.
- **Colors:** change the variables at the top of the `<style>` block.

## Preview
Open `index.html` in a browser.

## Publish on GitHub Pages (free, via GitHub Actions)
1. Create a GitHub repository (for example `dinda-portfolio`) and upload `index.html`, `certificate.webp` and `README.md`.
2. Add the workflow file: click **Add file > Create new file**, type `.github/workflows/pages.yml` as the file name (typing the slashes creates the folders), paste the contents of `pages.yml` from this project, and commit to `main`.
3. Go to **Settings > Pages**. Under **Build and deployment > Source**, choose **GitHub Actions**.
4. Open the **Actions** tab and wait for "Deploy site to GitHub Pages" to turn green (about a minute). If it did not start, click it and choose **Run workflow**.
5. Your site is live at `https://YOUR-USERNAME.github.io/dinda-portfolio/`. Every later commit to `main` redeploys automatically.

## Before publishing
- [ ] Confirm project 1/2/3 match the right notebooks
- [ ] Replace the "Add your own..." placeholders (recommendations, limitations)
- [ ] Review the key findings against your notebooks
- [ ] Optionally add a `<link rel="canonical">` once you know your URL

## Project images and new notebooks
- Upload the three `viz-*.webp` images next to `index.html`.
- Projects 04 and 05 show "Notebook coming soon". When a notebook is ready, replace the `<span class="btn off">` in that card with the "Open Google Colab" link used in the other cards, fill in Key findings, and replace the `fig soon` box with a `<figure class="fig">` image.

## Dashboard views
Projects 01 to 03 have a "View dashboard" popup built from notebook outputs. Upload every `dash-*.webp` and `viz-*.webp` image next to `index.html`. To embed a real Looker Studio report later, publish it with **File > Embed report** and place its `<iframe>` inside the matching `<dialog class="dash">`.

## Latest additions
Upload `kaggle-certificate.webp` next to `index.html`. Projects 04 and 05 now link to their notebooks; fill in their Key findings and replace the placeholder box with a chart image once you have the results.

## Projects 04 and 05
Both now have a dashboard view. Upload all new `dash-maint-*.webp` and `dash-retail-*.webp` images next to `index.html`.
