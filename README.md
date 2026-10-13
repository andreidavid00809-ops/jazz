# ReFOUND (jazz)

A simple single-file landing page intended to send users to a download link.

This repository contains a static `index.html` ready to be deployed on Vercel.

How to deploy

- Quick (recommended):
  1. Sign in to Vercel (https://vercel.com).
  2. Click "New Project" and import this repository `andreidavid00809-ops/jazz`.
  3. Vercel will detect a static site; click "Deploy".

- Using the Vercel CLI:
  1. Install the CLI: `npm i -g vercel`.
  2. From this repo's directory run: `vercel --prod`.

Notes

- The page currently links to `https://www.google.com`. Update the link in `index.html` (the anchor with class `button`) to point to your actual download URL before deploying.
- `vercel.json` is included to ensure the static build is used and the app serves `index.html` for all routes.

If you want, I can:
- Update the button URL to the real download link for you.
- Add a custom domain setup guide.
