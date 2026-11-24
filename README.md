# Public legal documents — YouTube Upload Tool

Google Cloud project `extreme-lodge-504919-f7` · OAuth client `201426262762-mv5t1d0t2cqjvhpgrmv7egtls6gaciq5.apps.googleusercontent.com`

| Document | Public URL |
|---|---|
| App home page | https://xcoderpmd.github.io/privacy-policies/home.html |
| Privacy Policy | https://xcoderpmd.github.io/privacy-policies/ (mirror: /privacy-policy.html) |
| Terms of Service | https://xcoderpmd.github.io/privacy-policies/terms.html |

These URLs go into the OAuth consent screen (Branding → App Home Page, App Privacy Policy) and into the
Google API verification request. **Authorized domains must list `xcoderpmd.github.io`** (the domain of all
three pages) plus `youtube.com`; an empty "Authorized domain 2" row is a validation error — delete it.

## How to update
Edit `index.html` / `terms.html`, bump the "Last updated" date, commit to `main`. GitHub Pages
rebuilds in about a minute.
