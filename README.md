# cryptobace | Be Ace

Portfolio website of **cryptobace**: graphic design, web apps, SEO, email marketing, Facebook business pages, and crypto community growth.

- Brand: cryptobace
- Slogan: Be Ace
- Email: cryptobace001@gmail.com
- Telegram: @Yalex1262 (https://t.me/Yalex1262)
- LinkedIn: https://www.linkedin.com/in/yahya-muhammed-aa7a36172
- GitHub: https://github.com/cryptobacedev

## What is in this project

| File or folder | What it is |
|---|---|
| `index.html` | The whole website (pages, design and code in one file) |
| `work/design/` | Logos, flyers, social media posts |
| `work/web-apps/` | Covers and screenshots of the sites and apps you built |
| `work/community/` | Proof of community growth (Looter.io, Artem Decompile) |
| `work/marketing/` | SEO, email and Facebook results |
| `work/automation/` | Bots and AI tools |
| `work/testimonials/` | Client reviews |
| `assets/` | Your profile photo, logo and sharing picture |
| `README.md` | This guide |

It is a static website. There is nothing to install and no build step.

## How to add a project

1. Open `index.html`.
2. Find the part marked `EDIT HERE`.
3. In the `WORKS` list, copy one line, paste it below, and change the words.

```js
{t:'Project name',cat:'Web apps',d:'One short sentence about it.',url:'https://link-to-project.com',e:'P'},
```

- `cat` can be `Web apps`, `Automation`, `Community` or `Design`.
- `url` is optional. Leave it out if the project has no link.
- For a design picture, add `img:'work/design/your-picture.jpg'` and upload the picture into the matching folder inside `work`.

## How to change prices

In the same part of `index.html`, find the `SERVICES` list. `ng` is the naira price and `us` is the dollar price. Change the number and save.

## How to put it online (free)

**Cloudflare Pages (recommended)**
1. Go to dash.cloudflare.com, then Workers and Pages, then Create, then Pages.
2. Choose Upload assets, name the project `cryptobace`, and drag in this folder.
3. Click Deploy. Your site is live at `cryptobace.pages.dev`.

**Or connect this GitHub repository**
1. In Cloudflare Pages choose Connect to Git and pick this repository.
2. Leave the build settings empty and click Deploy.
3. Every change you save on GitHub goes live by itself.

Note: Vercel's free Hobby plan is for personal, non-commercial use only, so use Cloudflare Pages for this site.

## Contact

Message me on Telegram (@Yalex1262) or email cryptobace001@gmail.com.

&copy; cryptobace. All rights reserved.
