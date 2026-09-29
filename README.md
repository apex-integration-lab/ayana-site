# Ayana public pages

Public privacy and support pages for the Ayana family app. The site is static HTML and CSS, with no scripts, analytics, cookies, or build dependencies.

Published URLs:

- https://ayana.aaron.software/privacy/
- https://ayana.aaron.software/support/

GitHub Pages serves the root of `main`. The `CNAME` file configures the custom domain. DNS must contain a `CNAME` record for `ayana` pointing to `apex-integration-lab.github.io` (without the repository name). Keep the custom domain in GitHub Pages settings before adding that record. After DNS and the certificate are ready, enable **Enforce HTTPS** in Pages settings.

To preview locally, run `python3 -m http.server 8000` from this directory and visit http://localhost:8000. Review the policy text with the product owner before using its URL in app-store metadata. Update the effective date whenever the policy materially changes.
