# CarZero website

Static site (no build step), published with GitHub Pages at https://julesmoreau62.github.io/carzero-site/.

- `index.html`: the home page, in English only and in a light theme only. Texts are written directly in the HTML. Colours are tokens at the top of the `<style>` block.
- `img/hero-stage.jpg` and `img/hero-hand.webp`: the hero photo and the hand holding the phone. The hand's screen is transparent; the app screens in the HTML show through it.
- `legal.html`, `privacy.html`: legal pages (drafts, fields marked TO COMPLETE).
- `_headers`: security headers for Cloudflare Pages. GitHub Pages ignores this file; it only applies if the site moves back to Cloudflare.
- `img/`: images.

Every push to `main` is published automatically (about 30 seconds). Work on a branch and open a pull request if you want a review first.
Do not add secrets, personal data or tracking scripts to this repository.
