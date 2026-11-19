# Publish Bean Hub Coffee with GitHub Pages

This file follows the ICT2215 **“How to Publish an HTML Project Using GitHub Pages”** student guide.
It is a project-specific checklist; no Git or terminal commands are required for the web upload
method.

## Before you start

- A GitHub account: <https://github.com/>
- This folder on your computer.
- An internet connection.
- The repository is **public** so the lecturer and classmates can open it.
- `index.html` must stay at the **root** of the repository, not inside another folder.

## Repository settings

| Setting | Value |
|---|---|
| Repository name | `bean-hub-coffee` |
| Description | Bean Hub Coffee — single-page HTML/CSS café website |
| Visibility | **Public** |

## Step 1 — Create the public repository

1. Sign in at <https://github.com/>.
2. Click the **+** icon in the top-right corner.
3. Choose **New repository**.
4. Enter the repository name `bean-hub-coffee`.
5. Add the description above.
6. Select **Public**.
7. Click **Create repository**.

## Step 2 — Upload the project

1. Open the new repository.
2. Click **Add file → Upload files**.
3. Drag the **contents** of this folder into the upload area — not the outer folder itself.
4. Make sure these files are visible at the repository root:
   - `index.html`
   - `style.css`
   - `README.md`
   - `LICENSE`
   - `.nojekyll`
5. Scroll down, enter the commit message `Upload Bean Hub Coffee website`, and click
   **Commit changes**.
6. Confirm that the repository file list shows `index.html` at the top level.

> **Important:** GitHub Pages will look for `index.html` at the repository root. If it is inside a
> folder such as `BeanHubCoffee/index.html`, the live site will show a 404 error or a directory
> listing.

## Step 3 — Enable GitHub Pages

1. In the repository, click **Settings**.
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/(root)`
4. Click **Save**.
5. Wait a few minutes for the deployment to finish.

## Step 4 — Open the live website

1. Return to **Settings → Pages**.
2. Wait for the “Your site is live at …” message.
3. Click **Visit site**, or open:

```text
https://13965217170.github.io/bean-hub-coffee/
```

## Step 5 — Test before submitting

Open the live URL in a **private/incognito** window, without being logged in to GitHub, and check:

- [ ] The page loads at the live URL, not a 404 page.
- [ ] The header logo and all four navigation links work.
- [ ] All six photographs appear.
- [ ] The YouTube video section loads, or the “Watch on YouTube” fallback link works.
- [ ] The contact form fields and display-only button are visible.
- [ ] The layout is readable at phone width; there is no horizontal scrollbar.
- [ ] The browser console has no blocking errors.
- [ ] The page still works after a hard refresh.

## Step 6 — Update the site later

1. Edit `index.html`, `style.css` or the image/video URLs locally.
2. Open the GitHub repository.
3. Click **Add file → Upload files**.
4. Upload the changed files, replacing the existing ones.
5. Commit the changes.
6. Wait for GitHub Pages to deploy, then refresh the live URL.

## Troubleshooting

| Problem | What to check |
|---|---|
| 404 error | Is `index.html` at the repository root? Is Pages set to `main` / `/(root)`? |
| CSS not working | Is the `<link rel="stylesheet" href="style.css">` path correct? Is `style.css` at the root? |
| Images not showing | Are the Unsplash URLs reachable? Did you update the `src` and `alt` when replacing an image? |
| Video not playing | Is YouTube accessible on the network? Use the fallback link. |
| Site looks unchanged | Wait for deployment, then hard-refresh the browser. |
| Blank page | Check that the HTML file was not truncated during upload and that the file name is exactly `index.html`. |

## Submission details

```text
Student Name:  ____________________________________________
Student ID:    ____________________________________________
Repository:    https://github.com/13965217170/bean-hub-coffee
Live website:  https://13965217170.github.io/bean-hub-coffee/
```

## Final reminder

The repository URL shows the source code. The GitHub Pages URL shows the actual website. Submit
both. Test the live URL in a private window before the deadline.
