# GetTenDoors.com

Static launch site for Ten Doors by A2M4 Systems LLC.

## Included

- `/` landing page
- `/support/` App Store support URL
- `/privacy/` public privacy policy URL
- responsive CSS
- Ten Doors logo, app icon, and product marketing image
- `404.html`

## Run locally

From this directory:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages

1. Create a repository such as `gettendoors-site`.
2. Put the contents of this folder at the repository root.
3. Enable GitHub Pages from the main branch/root.
4. Add the custom domain `gettendoors.com` in Pages settings.
5. Configure the DNS records GitHub provides for the custom domain.
6. Once DNS has propagated, enable HTTPS enforcement.

If you are publishing from GitHub Pages and want the repository to carry the custom domain configuration, create a file named `CNAME` containing:

```text
gettendoors.com
```

## Before App Store submission

- Replace the `App Store coming soon` element on `index.html` with the final App Store URL.
- Create `support@gettendoors.com` and `privacy@gettendoors.com`, or change the site to addresses you actively monitor.
- Review `/privacy/` against the actual production data flows in the shipped app, particularly receipt processing, cloud synchronization, analytics/diagnostics, and any third-party infrastructure. Apple's App Privacy answers should match the production implementation and the policy.
- Confirm the pricing shown on the site still matches App Store Connect.

## Brand

- Evergreen: `#0F3D36`
- Gold: `#D4A259`
- Warm Cream: `#F8F5EE`
- Tagline: `Properties. Progress. Peace of mind.`
