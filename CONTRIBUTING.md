# Contributing a template

## The deal

- You design a complete single-page website template for one industry.
- If it's accepted and listed on [siteboardhq.com](https://siteboardhq.com):
  - **Credit**: your name and a link on the template's product page.
  - **Revenue share**: **45% of net sales** of that template (after Stripe fees and refunds), paid **quarterly** via PayPal or bank transfer. I send you a sales report with each payout.
- You keep the right to show the work in your own portfolio.
- Not accepted? You keep everything; nothing is used.

## What a template needs

1. Read [DESIGN-DIRECTIONS.md](DESIGN-DIRECTIONS.md) and pick an industry. Follow its "people come to check / trust comes from / photos / mood" rules.
2. One `index.html` with inline or one linked CSS file. No frameworks, no build step.
3. All text and images must be swappable by a non-technical owner: real section structure (hero, services/menu, about, hours/location, contact), no text baked into images.
4. Works on a phone at 375px wide and on desktop at 1440px.
5. Photos: use free-licensed images (Unsplash, Pexels) and list their URLs in a comment at the top of the file.
6. No external JS dependencies except what is strictly needed.

## How to submit

1. Fork this repo.
2. Add your template as `submissions/<industry>-<your-handle>/index.html` plus any assets.
3. Open a pull request. In the description: the industry, the business name you used, and one paragraph on the design decisions.
4. I review within a week and reply on the PR.

## Feedback only?

You don't need to build anything. Open an [issue](../../issues/new/choose) with what you'd change and why.
