# Outpaze — Landing Page

Single-file site. `index.html` contains everything (HTML, CSS, JS, and the embedded Mission Control demo). `og.png` is the social-share card.

## Editing
- **Copy/text:** open `index.html`, search for the sentence, change it. All copy is plain HTML.
- **Do not hand-edit:** the `<script>` blocks, or the `<script type="text/html" id="mc-src">` block (that's the live demo).
- **Bigger changes:** give `index.html` to Claude with instructions, replace the file with the result.
- Every commit to `main` auto-deploys via Vercel. Use a branch + preview URL to test risky changes.

## Pending before real launch
- [ ] Replace `mailto:hello@outpaze.com` CTAs with the Calendly/booking link (6 places)
- [ ] Replace placeholder metrics (41s / 37 / 120+ / 2.1x) with real numbers when available
- [ ] Remove or replace the placeholder testimonial in the Results section
- [ ] Add analytics (e.g., Plausible one-liner) if wanted
