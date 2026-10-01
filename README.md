# Blog by Mohammed Zaid Waghoo

Static digital-magazine site: index.html + images/. No build step.

## Deploy on Netlify (fastest)
1. Go to app.netlify.com/drop
2. Drag this whole folder onto the page.
3. Site > Site configuration > Change site name to pick your URL.

## Deploy via GitHub (auto-updates)
1. Create a repo, push these files.
2. Netlify > Add new site > Import from Git > pick the repo.
3. Build command: (leave empty)   Publish directory: .

## Add a post
Open index.html, find `const POSTS = [`, copy one post object to the top, change slug/title/date/tag/summary/body.
