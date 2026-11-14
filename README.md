# Puttur Kattu Center Website

A responsive, static website built with plain HTML, CSS and JavaScript.

## Files

- `index.html` — page content, SEO metadata, structured business data and links
- `styles.css` — responsive layout, colours, typography and component styling
- `script.js` — mobile menu, enquiry form-to-WhatsApp behaviour and footer year

## Preview locally

1. Download and unzip the project.
2. Open `index.html` in a browser.
3. For a local development server, run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`.

No build step or paid hosting is required.

## Publish with Cloudflare Pages (free)

1. Create or sign in to a Cloudflare account.
2. Create a GitHub repository and upload the three website files (`index.html`, `styles.css`, `script.js`) to its root.
3. In Cloudflare, open **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
4. Select the repository.
5. For a plain static site, leave the framework preset as **None**. Leave the build command empty and set the build output directory to `/` (or the repository root, if prompted).
6. Select **Save and Deploy**. Cloudflare will provide a free `*.pages.dev` address.
7. Whenever you update the files in the connected Git repository, Cloudflare Pages will redeploy the site.

You can also use Cloudflare Pages Direct Upload by uploading the project folder contents in the Pages dashboard. Git integration is recommended for easier future updates.

## Important details to verify before going live

- Confirm the phone/WhatsApp number `+91 73973 83061`. It is set in `index.html` and `script.js`.
- Confirm the address and landmark wording.
- Confirm the experience figure and the Justdial rating/review count. The website attributes the approximate rating (4.2/5, 140+ reviews) to Justdial and labels it as supplied information that should be checked against the live listing.
- Confirm the 20+ years experience claim before publication.
- One supplied YouTube Shorts URL contained unusual non-Latin characters (`vOaad03ТЬКС`), so it has intentionally not been linked. Add it after confirming the correct URL.
- The photos are loaded from Unsplash and require an internet connection. Replace them with the center's own licensed photos for a more authentic website.
- Service descriptions are informational and do not promise cures or guaranteed outcomes.

## Updating the WhatsApp number

1. In `script.js`, change `WHATSAPP_NUMBER` to the country code and number with digits only (for India, begin with `91`).
2. In `index.html`, update the `tel:` links and all `https://wa.me/` links to match.
3. Search for the old number to ensure every instance has been updated.

## Notes

This is a static information and enquiry website, not a patient portal and not a medical diagnosis service. The enquiry form opens WhatsApp with the submitted details; it does not store submissions on the website.
