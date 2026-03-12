# GitHub Pages upload steps

## Files in this package
- `_config.yml`
- `ai-2027-dialogue.md`
- `assets/css/style.scss`

## What this package assumes
This package is set up for a standard GitHub Pages site using Jekyll and the `minima` theme.

## Step 1: create or open your GitHub repository
1. In GitHub, create a new repository or open the one you want to use.
2. If this repository already has a GitHub Pages site, keep a copy of any existing files before overwriting them.

## Step 2: upload the files
1. In the repository root, upload `_config.yml` and `ai-2027-dialogue.md`.
2. Create the folder path `assets/css/` if it does not already exist.
3. Upload `assets/css/style.scss` into that folder.
4. Commit the changes.

## Step 3: turn on GitHub Pages
1. Go to **Settings**.
2. Open **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder.
5. Save.

## Step 4: wait for the site to build
1. GitHub Pages usually builds in under a few minutes.
2. Refresh the **Pages** settings screen until GitHub shows the site URL.

## Step 5: open the article
The article page will be available at:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/ai-2027-dialogue/`

If your repository is a user site named `YOUR-USERNAME.github.io`, the URL will instead be:

`https://YOUR-USERNAME.github.io/ai-2027-dialogue/`

## Step 6: customize the article
### To change the title shown on the page
Edit the front matter at the top of `ai-2027-dialogue.md`:

```yaml
---
layout: page
title: "AI 2027 and a Christian Response"
permalink: /ai-2027-dialogue/
---
```

### To change pull-quote text
Search for `pullbox` in `ai-2027-dialogue.md` and edit the quote lines.

### To change fonts, spacing, or colors
Edit `assets/css/style.scss`.

## Step 7: add this page to a newsletter
Use the full GitHub Pages URL for the article.

For newsletter use, test:
- mobile readability
- whether foldout sections open cleanly
- whether the pull quotes look correct on desktop and mobile

## Notes
- The source text still contains a few placeholders and unresolved references. Search for `____`, `placeholder`, and `Editor’s note` before final publication.
- If your repository already has a custom theme or existing CSS, merge the CSS carefully rather than overwriting it.
