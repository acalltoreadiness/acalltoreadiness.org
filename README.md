# acalltoreadiness.org -- the ministry website

Built 2026-10-25 (TODO 10a, cut down for the business cards: a where-to-listen hub plus a privacy page).
Status: BUILT AND CHECKED LOCALLY. NOT LIVE YET -- hosting and the domain change are waiting on Joseph
(see DECISIONS.md, 2026-10-25 WEBSITE BUILT; HOSTING PROPOSED).

## What is here
- index.html     Where to listen (Apple Podcasts, Spotify, SermonAudio, YouTube, the feed), About (the show
                 DESCRIPTION exactly as in SHOW METADATA.md), Contact (contact@acalltoreadiness.org).
- privacy.html   Privacy policy. Also covers the "GRM Uploader" YouTube tool, so it can be entered as the
                 privacy-policy URL when the Google Cloud app is published out of Testing mode.
- 404.html       Not-found page.
- assets/        site.css, self-hosted fonts (Oswald, EB Garamond, with their OFL licences), icons, and
                 share-1400.jpg (the show art, used when the link is texted or posted).
- CNAME, robots.txt, sitemap.xml   for the host and search engines.

## Rules this site keeps (do not break without asking)
- No cookies, analytics, trackers, embeds or third-party fonts. The privacy page says so; adding any of them
  means updating privacy.html in the same change.
- Show name, author ("Gerry G. Register"), subtitle and description exactly as in SHOW METADATA.md.
- No "Inc." anywhere. Nothing implying money or monetization. No phone number or mailing address.
- YouTube is labelled "being added now" until the video backfill is public; change that line when it is.

## Updating
The folder is a git repository. Edit, then commit. Publishing (once hosting is set up) is a git push using
the deploy key in ~/.grm/github_deploy_key -- no password involved.
