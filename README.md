# Spacetel Inventory Portal (GitHub + Netlify only)

- `public/index.html` is the dashboard. Anyone with the link can use it. No login, no database.
- `public/data.json` is the published inventory. You create it from the two reports and upload it to GitHub.
- Netlify republishes the site automatically every time something changes in the GitHub repo.

## Update the data (every time)
1. Open your site link with `#admin` at the end, e.g. https://your-site.netlify.app/#admin
2. Upload the Inventory Listing report and the Calling Tree. Wait for both green messages.
3. Click Download data.json.
4. GitHub repo > open the `public` folder > Add file > Upload files > drop data.json > Commit changes.
   (Same name replaces the old file.)
5. Wait about a minute. Open the normal link: "Source report last updated on ..." shows the new date.

## First-time setup
See the chat instructions: create GitHub repo, upload these files, connect Netlify (publish directory: public).
