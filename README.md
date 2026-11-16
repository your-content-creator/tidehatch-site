# tidehatch.com

Landing page for Tidehatch, early access waitlist. One static page on GitHub Pages.

- `index.html` the page (all CSS and JS inline). Waitlist posts to a Google Form (MJC Workspace), responses land in the sheet "Tidehatch Early Access Waitlist (Responses)". Form IDs live in the `WAITLIST` object at the bottom of the page.
- `logo.svg` Tidehatch mark: a wave (tide) cresting out of a hatch line, with a dot for the new idea.
- `media/` proof screenshots and the AP reel (copied from mjcreativellc-site).
- DNS (Porkbun): root ALIAS + www CNAME to your-content-creator.github.io. Never touch MX, SPF, DKIM, DMARC. Subdomains sfc. and lfc. stay as they are.
- Edit: change files, commit, push. Pages rebuilds in about a minute.
