CID Watch static site

This commit adds a simple static website to the repository (branch: gh-pages) with placeholder YouTube iframes for CID episodes and a sidebar with monetization placeholders.

What I added:
- index.html — A simple responsive page that shows multiple YouTube embed iframes (placeholders), a monetization sidebar, and a subscribe form placeholder.
- styles.css — Basic styles for the page.

Important next steps you should do after this push:
1. Replace the placeholder YouTube IDs in index.html (VIDEO_ID_1..VIDEO_ID_6) with the real YouTube video IDs for the CID episodes or other videos you want to embed. Example embed URL format:
   https://www.youtube.com/embed/VIDEO_ID

2. Replace the ad/affiliate placeholders with real ad network code (e.g., Google AdSense), affiliate links, or donation links. Make sure you comply with the ad network's policies.

3. Publish the branch via GitHub Pages (set the source to the gh-pages branch in repository Settings -> Pages) if you want the site served at https://<your-username>.github.io/TV-Serial/

4. (Optional) Improve the site: add navigation, search, categories, episode pages, server-side tracking for analytics, or integrate an email provider for the subscribe form.

License / Copyright
- This site contains placeholder links to videos. Ensure you have the right to embed or share the CID videos you add.

If you'd like, I can:
- Replace the placeholders with actual YouTube CID episode IDs if you provide the links or let me search for public uploads.
- Add a simple server-side backend or static data file (episodes.json) and wiring so you can manage episodes more easily.
- Enable a GitHub Pages workflow to automatically publish from gh-pages.
