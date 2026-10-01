# 1A Recruitment website

A plain static site for [1arecruitment.com](https://1arecruitment.com), served by GitHub Pages. There is no build step: edit the files and push.

## Files

- `index.html`: the whole page, including its styles and a little JavaScript.
- `img/`: the logo files and the LinkedIn preview image (`og-image.jpg`, 1200 × 630, the logo on black).
- `favicon.ico`, `apple-touch-icon.png`, `img/favicon-32.png`, `img/icon-192.png`: icons made from the 1A mark.
- `CNAME`: keeps the custom domain. Do not delete it.
- `robots.txt` and `sitemap.xml`: help search engines find the page.

## Adding a booking link

Open `index.html`, search for `BOOKING_URL` near the bottom and paste your link between the quotes:

```js
var BOOKING_URL = 'https://calendly.com/your-name/30min';
```

Every "Book a call" button will then open that link in a new tab. While it is empty, the buttons scroll to the contact section.

## Checking the LinkedIn preview

After publishing, paste `https://1arecruitment.com` into LinkedIn's [Post Inspector](https://www.linkedin.com/post-inspector/) to refresh the cached preview.
