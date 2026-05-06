# Solnox Systems Website

A simple static website for Solnox Systems, built with plain HTML, CSS, and JavaScript so it can be published directly with GitHub Pages.

Solnox Systems is positioned as an engineering services company for sustainability reporting,
compliant off-grid power systems, lithium battery lifecycle safety, automation and virtual power
plants, and energy storage rebate or grant opportunities.

## Project Files

- `index.html` - homepage content
- `about.html` - company positioning and values
- `contact.html` - contact details and email call to action
- `styles.css` - all responsive styling and visual design
- `script.js` - small enhancements such as the mobile navigation menu
- `logo/header.svg` - logo used in the site header
- `logo/icon.png` - favicon used in the browser tab

## Develop Locally

Open the project folder:

```bash
cd /Users/sebastien/solnoxui
```

Start a simple local server:

```bash
python3 -m http.server 8000
```

Open this URL in your browser:

```text
http://localhost:8000
```

When you make edits, refresh the browser to see them.

## Editing Guide

- Change the main homepage copy in `index.html`.
- Change the about page copy in `about.html`.
- Change email and contact details in `contact.html`.
- Adjust colours, spacing, layout, and responsive design in `styles.css`.
- Adjust the mobile menu behaviour in `script.js`.

The current contact email is:

```text
equiries@solnox.com.au
```

The current ABN is:

```text
ABN 78 774 038 811
```

## Publish With GitHub Pages

1. Create a new GitHub repository for this project.
2. Push these files to the repository's `main` branch.
3. In GitHub, open the repository settings.
4. Go to **Pages**.
5. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
6. Choose branch `main` and folder `/root`.
7. Save the settings.
8. Wait for GitHub to publish the site, then open the generated GitHub Pages URL.

## Optional Git Commands

If this folder is not already a git repository, initialise it:

```bash
git init
git add .
git commit -m "Create Solnox Systems static website"
```

Then connect it to your GitHub repository:

```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git branch -M main
git push -u origin main
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with your GitHub details.

## Notes

- There is no build step.
- There are no runtime dependencies.
- The site header uses `logo/header.svg`.
- The site uses Google Fonts. If you want the site to have zero external requests, replace those font links with system fonts.
