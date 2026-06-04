# rabbeinu-signup

A tiny static page hosted on GitHub Pages that redirects visitors to a Google Form.
GitHub Pages terminates HTTPS, so links to this repo's Pages URL stay secure even
though the final destination is an external form.

## Set the destination URL

Edit `index.html` and replace every `REDIRECT_URL_HERE` (4 occurrences) with your
Google Form URL, e.g. `https://docs.google.com/forms/d/e/XXXX/viewform`.

## Enable GitHub Pages

1. Push this repo to GitHub.
2. Repo **Settings → Pages**.
3. Under **Build and deployment**, set **Source: Deploy from a branch**.
4. Choose branch `main` and folder `/ (root)`, then **Save**.
5. After a minute, your redirect is live at
   `https://<your-username>.github.io/rabbeinu-signup/`.
