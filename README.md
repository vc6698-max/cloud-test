# Self Cloud informational pages

Publish only `index.html`, `privacy.html`, `terms.html` and `style.css` from this directory to
a separate public GitHub Pages repository. These are standalone static files;
no Python, build step, credentials or application deployment is needed.

Before publishing, review the privacy policy and terms against your actual configuration
and confirm the user support email configured in Google Auth Platform reaches
you. You may replace the contact paragraph with a public contact address you
are comfortable publishing. Update the effective date if you revise the policy.

After GitHub Pages provides the site's public base URL, use:

- Application homepage: `https://YOUR-USER.github.io/YOUR-REPO/`
- Privacy policy: `https://YOUR-USER.github.io/YOUR-REPO/privacy.html`
- Terms of Service: `https://YOUR-USER.github.io/YOUR-REPO/terms.html`

Replace those examples with the actual working URLs in Google Auth Platform's
Branding settings. Keep all three pages publicly readable and confirm their links
work. Google may separately require domain registration/ownership verification
or review; publishing these files does not guarantee OAuth approval.

Keep the Self Cloud source workspace, credentials, `.env`, tokens and storage
data out of this static site's repository. The actual portal stays on localhost.
