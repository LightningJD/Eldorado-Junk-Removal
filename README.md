# ElDorado Junk Solutions Website

Static website for ElDorado Junk Solutions LLC, a junk removal business serving Las Vegas and Henderson.

Live site: [https://www.eldoradojunk.com](https://www.eldoradojunk.com)

GitHub repo: [LightningJD/Eldorado-Junk-Removal](https://github.com/LightningJD/Eldorado-Junk-Removal)

## What This Is

This is a simple, self-contained website hosted with GitHub Pages. There are no build tools, frameworks, or backend services required.

The site includes:

- Mobile-friendly one-page design
- Click-to-call phone links
- Mobile sticky tap-to-call button
- Text-a-photo quote form that opens the visitor's SMS app
- Service cards
- Before/after photo sliders
- Reviews
- Service area for Las Vegas and Henderson
- FAQ section
- Instagram footer link
- Favicons and social preview image
- LocalBusiness SEO data
- `robots.txt` and `sitemap.xml`

## Main Files

- `index.html` - the full website: text, layout, styles, phone links, form behavior, and SEO data.
- `logo.png` - business logo used on the site.
- `photos/` - before/after project photos.
- `favicon.ico`, `favicon-16x16.png`, `favicon-32x32.png`, `apple-touch-icon.png`, `android-chrome-192x192.png`, `android-chrome-512x512.png` - browser/app icons.
- `og-image.png` - image shown when the website is shared by text, social media, or messaging apps.
- `site.webmanifest` - mobile/browser icon metadata.
- `robots.txt` - tells search engines they can crawl the site.
- `sitemap.xml` - tells search engines the main website URL.
- `CNAME` - connects GitHub Pages to `www.eldoradojunk.com`.

## How Deployment Works

The site is published by GitHub Pages from the `main` branch.

Plain-English version:

1. Make a change in this repo.
2. Commit and push it to `main`.
3. GitHub Pages automatically republishes the site.
4. The live website updates at [https://www.eldoradojunk.com](https://www.eldoradojunk.com).

You do not need to stay logged into Namecheap for normal wording/photo changes. Namecheap is only needed if DNS/domain settings need to change.

## Common Edits

### Change the phone number

In `index.html`, find this line near the bottom:

```js
const PHONE = "725-212-8777";
```

Change the number there once. The call buttons and phone links update automatically.

### Change wording

Most visible text is inside `index.html`. After editing wording, check the site on both desktop and mobile because longer text can wrap differently on phones.

### Change the logo

Replace `logo.png` with the new logo file. Keep the filename as `logo.png` unless you also update the references in `index.html`.

### Change before/after photos

Replace the files in `photos/`:

- `garage-before.jpg`
- `garage-after.jpg`
- `storage-before.jpg`
- `storage-after.jpg`
- `yard-before.jpg`
- `yard-after.jpg`

Keep the same filenames unless you also update the image paths in `index.html`.

### Change the Instagram link

The footer Instagram link currently points to:

```text
https://www.instagram.com/eldoradojunk/
```

The visible handle is:

```text
@eldoradojunk
```

Both live in the footer section of `index.html`.

## Testing Checklist

After any website change, test:

1. Open [https://www.eldoradojunk.com](https://www.eldoradojunk.com) on desktop.
2. Open it on a phone or narrow browser window.
3. Tap a call button and confirm it opens `725-212-8777`.
4. Try the text-a-photo quote form and confirm it opens the SMS app.
5. Scroll to the before/after sliders and make sure the photos load.
6. Scroll to the footer and make sure `@eldoradojunk` opens Instagram.
7. Check that no text overlaps or looks cut off on mobile.

## SEO Notes

The site currently targets junk removal in Las Vegas and Henderson. SEO basics already included:

- Search-friendly title and description
- Canonical URL
- LocalBusiness JSON-LD
- Business logo and preview image metadata
- Service area mentions
- `robots.txt`
- `sitemap.xml`

Google Business Profile should match the website exactly: business name, phone number, website URL, hours, service area, photos, and reviews.

## Current Business Details

- Business name: ElDorado Junk Solutions LLC
- Phone: `725-212-8777`
- Service area: Las Vegas and Henderson
- Hours: Open 24 hours
- Instagram: [@eldoradojunk](https://www.instagram.com/eldoradojunk/)

