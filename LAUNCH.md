# Launch checklist (site)

Do these when the Google Play listing is public. Each item is small.

## On the site
- [ ] `index.html`: replace the "Soon on Google Play" badge with a real link to the Play page.
- [ ] `index.html` JSON-LD (`MobileApplication`): add `"downloadUrl"` and `"installUrl"` with the Play URL. Add `"sameAs"` (Play page, social profiles) to the `Organization`.
- [ ] Add `aggregateRating` to the JSON-LD only when there are real Play ratings, and only matching what Play shows. Never invent it.
- [ ] Change "Join the Android test" buttons to "Get it on Google Play" (index, closing section, guide pages). Keep `/test.html` working.
- [ ] `/s/index.html`: change `TARGET` and the two fallbacks to the Play page (stickers keep working).
- [ ] FAQ and JSON-LD FAQ: update "(testing now)" wording. Keep both in sync.
- [ ] `llms.txt`: update the status line ("currently in testing").
- [ ] Add `<lastmod>` dates to `sitemap.xml` if pages change. Resubmit it in Search Console.
- [ ] Search Console: request indexing for the home page and the three guide pages.

## Off the site (what AI assistants and search learn from)
- [ ] Play listing: first line says "free photo-to-video app"; use the same words as the site.
- [ ] Links to stillsdrift.com from: reiss.co.il, REISS STUDIO social profiles, the Play listing.
- [ ] A few honest mentions in places people ask "app to turn photos into video": relevant communities (read each one's self-promotion rules first), app-directory listings, short posts from real users.
- [ ] Ask early testers for a Play review once the listing is public (no incentives).
- [ ] App Store listing later: same wording.

## Ready-to-use descriptions
- One line: StillsDrift is a free photo-to-video app that turns a few photos into a short moving video for Reels, Stories and Shorts.
- Short: StillsDrift turns a few photos into a short moving video on your phone. Choose Scrolling Columns, Photo Wall or Slideshow, in 9:16, 1:1 or 16:9. Free, no account, works offline, and your photos are never uploaded.
- Longer: StillsDrift is a free photo-to-video app made by the photographers of REISS STUDIO. Pick a few photos, mark the main subject (a face, a pet, a product) so every move keeps it in the frame, choose a look and a pace, and save the video to your gallery. It works offline, needs no account and never uploads your photos. The Free version includes every style and tool, with up to 3 photos at 720p and a small watermark.
