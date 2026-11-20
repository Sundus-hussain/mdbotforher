# MDBot for Her — personal brand website

A responsive static website built with HTML, CSS and vanilla JavaScript. No build step or framework required.

## Preview locally

Open `index.html` in a browser. For a local server, run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Deploy to Cloudflare Pages (free static hosting)

1. Create a GitHub repository (for example, `mdbot-for-her-website`).
2. Upload the contents of this folder to the repository root (keep the `assets` folder).
3. In Cloudflare Dashboard, open **Workers & Pages → Create → Pages → Connect to Git**.
4. Select the repository. Choose **None** as the framework preset. Leave the build command blank and set the build output directory to `/`.
5. Deploy. Cloudflare Pages will provide a `*.pages.dev` address. You can connect a custom domain later under the Pages project’s Custom domains tab.

You can also use Cloudflare Pages direct upload by uploading the site folder contents in the dashboard, but Git integration is better for future edits.

## Personalization still needed

- Replace the illustrative conference image at `assets/conference-speaker-illustrative.png` with a real photograph of Sundus speaking. The current image is AI-generated and is not a documentary photograph.
- Replace the `SH` portrait placeholder in the About section with a professional headshot when supplied.
- The Dimple Sthankiya podcast card is intentionally marked as awaiting the exact episode link; add the correct YouTube/episode URL and confirmed guest details before publishing.
- Confirm whether the credential labels and award wording should be expanded with exact dates, awarding organizations and certificate links.
- If you want direct email contact, add a public business email address; none was supplied, so this version uses LinkedIn and Sessionize links.

## Files

- `index.html` — content and page structure
- `styles.css` — responsive visual design
- `script.js` — mobile navigation and current year
- `assets/` — image assets
