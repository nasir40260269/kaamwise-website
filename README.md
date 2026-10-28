# Kaamwise Automation website

Business website for **Kaamwise Automation**, Lahore: practical AI, automation and computer vision for Pakistani businesses.

**Live site:** https://nasir40260269.github.io/kaamwise-website/ (after GitHub Pages is turned on)

## What's on the page
- Services: workflow automation, invoice & document processing, Excel dashboards, custom software, AI assistants, computer vision
- Projects with animated demos: AI quality inspection, AI proofreading, product counting, table occupancy & customer counting, real estate WhatsApp-to-Excel
- Time-saved calculator, FAQ, and a contact form that opens WhatsApp with the message ready

## How it's built
Everything is in one file, `index.html`: HTML, CSS and plain JavaScript. There's no build step and no server code. Fonts load from Google Fonts.

## Publish with GitHub Pages
Settings → Pages → Source: **Deploy from a branch** → Branch: **main**, folder **/ (root)** → Save.

## Edit contact details
Search `index.html` for these values:
- WhatsApp: `923004898623`
- Email: `kaamwiseautomation@gmail.com`

## Contact
WhatsApp +92 300 4898623 · kaamwiseautomation@gmail.com · Lahore, Pakistan

## Security
- **Content Security Policy** (in `index.html`): only the page's own script (pinned by SHA-256 hash), Google Fonts and local images may load. Injected scripts, plugins, `<base>` tag changes and form posts to other sites are blocked.
- If you edit the `<script>` block in `index.html`, update the `sha256-…` hash in the Content-Security-Policy meta tag. Otherwise the browser will block the script.
- External links use `rel="noopener noreferrer"`. The enquiry form limits input length and never sends data to a server: it only opens WhatsApp.
- No `innerHTML` with dynamic content, and no cookies, trackers or third-party scripts.
- HTTPS is enforced by GitHub Pages. `/.well-known/security.txt` tells people how to report a security problem.
