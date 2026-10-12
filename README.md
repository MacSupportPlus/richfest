# R.I.C.H. Fest website

The website for **R.I.C.H. Fest** (Resilience, Inspiration, Culture, Healing), a three-day community festival in Chattanooga, Tennessee, from CT Rich Way Productions.

**Live site:** https://richfest.org

Designed and built by [Jason McElvain](https://github.com/MacSupportPlus).

## What it does
- One-page festival site: mission, three-day schedule, tickets, photo gallery, and the founder's story
- Ticketing for three separate events: two free Eventbrite registrations and a paid Stripe Payment Link for the finale
- After the event, the site switches to a recap: ticket sales are marked closed and the buttons point to next year's updates

## The move
Moved off a Wix plan to Netlify, with the domain's DNS cutover handled end to end.

## Stack
Plain HTML and CSS (one file, no build step) · Netlify · Stripe Payment Links · Eventbrite

## Project layout
```
index.html    The entire site: markup, styles, and layout in one file
*.jpg         Event photos (ct_sign, grill1-3, sign1-3): served on the live site, not yet added here
```

No build step and no framework. Open `index.html` in a browser, or drag the folder into Netlify to deploy.
