# ipt_tvha

Single-file website (HTML + CSS + JS). No build step.

## Run locally
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a repository on GitHub and upload `index.html` and `README.md`.
2. Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Your site appears at `https://USERNAME.github.io/REPOSITORY/`.

## Notes
- Admin page: add `#admin` to the address or click the logo 5 times.
- On GitHub Pages the admin account, orders, messages and plan edits are stored in each visitor's own browser (localStorage). Visitors' orders and messages do not reach you. Use WhatsApp for that, or connect a backend (Firebase, Supabase) later.
- The payment page is a demo and takes no real payment.
- Three.js is loaded from cdnjs.cloudflare.com.
