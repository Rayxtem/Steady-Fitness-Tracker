# Steady Fitness Tracker

A responsive, browser-local fitness tracker with a 30-day recovery plan as a starting point. It works offline after loading and stores plans, logs, and notes in `localStorage`.

## Run locally

1. Install Node.js 20 or newer.
2. Run `npm install`.
3. Run `npm run dev` and open the URL shown.

## Deploy to Vercel

1. Put this folder in a GitHub, GitLab, or Bitbucket repository.
2. In [Vercel](https://vercel.com/new), import the repository.
3. Vercel detects Vite. Use `npm run build` as the build command and `dist` as the output directory if prompted.
4. Click **Deploy**.

You can also install the Vercel CLI, run `npx vercel` in this folder, and follow the prompts.

## Important privacy and backup note

All data is saved only in the current browser on the current device. Clearing browser site data, using another browser, or changing devices will not carry progress over. Use **Settings → Export backup** periodically; you can restore it there later.
