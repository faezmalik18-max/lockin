# Putting Lockin online

This folder is the whole website. There is nothing to build or install. Upload the files as they are.

## Easiest: Netlify Drop (about 2 minutes)
1. Go to https://app.netlify.com/drop
2. Drag this whole `lockin-site` folder onto the page.
3. Create a free account when it asks, so the site stays up.
4. You get a link like `something.netlify.app`. In Site configuration you can change the name.

## Also free: GitHub Pages
1. Make a new repository on GitHub and upload all the files in this folder.
2. In the repository, open Settings, then Pages, and choose "Deploy from a branch" with the `main` branch.
3. Your site appears at `your-username.github.io/repo-name`.

## Your own address (optional)
Buy a domain (about $10 to $15 a year) and connect it in your host's domain settings.

## Updating later
Upload the new files over the old ones. If you change `catalog.json` or `index.html`, also open `sw.js` and change `VERSION` (for example to `lockin-v2`) so phones pick up the update.

## Good to know
- Your planner is saved in each browser. It does not sync between devices. Use Settings, Download backup and Restore from file to move it.
- "Sync from school" only exists when Lockin is opened inside Claude. On the website, use Quick update and the Schoology calendar import.
- Course data comes from Ohio State's class search for Autumn 2026 and Spring 2027.
