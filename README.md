# Skora Consulting website

One-page site for [www.skora.net.au](https://www.skora.net.au), hosted free on GitHub Pages.

## How to update content

Open Claude Code in this folder (`C:\Users\hobbs\OneDrive\Skora\Website`) and just ask, e.g.:

> "Change the hero headline to ..." or "Update Kate's bio to mention ..."

Then ask Claude to "publish the changes" — it will commit and push, and the live site updates in about a minute.

Everything lives in one file: `index.html`. Logos and favicons are in `assets/`.

## Adding a headshot

Save the photo as `assets/kate.jpg`, then in `index.html` replace the placeholder line inside `.who-photo` (there's a comment showing exactly what to put). Or just ask Claude to do it.

## Contact form

The form posts to FormSubmit (free) and delivers to kate@skora.net.au.
The **first submission** triggers an activation email to that address — click the link in it once, and all future submissions come through.
