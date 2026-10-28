# Cubby public site draft

This branch prepares a separate Cubby website from the existing Ayana public pages. It is not the live legacy site. Keep `ayana.aaron.software` serving its auth callback, verified-link files, and existing store URLs while older builds remain supported.

The draft has a private invitation-only landing page, privacy and support pages, an account-deletion page, a join page, an auth callback page, and the existing Apple/Android association files. The public hostname is pending because `cubby.ayanasrivastava.com` currently serves the Supabase API. Set the new site's `CNAME`, update the join link, and verify the association files on the chosen host before publishing.

The site is static HTML and CSS, with no analytics, cookies, or build dependencies. To preview locally, run `python3 -m http.server 8000` from this directory. Review the privacy policy with the product owner before publication and set its effective date to the publication date.
