# Bianca's Cleaning Service — Interactive Prize Wheel

A static, responsive prize-wheel website. No customer form or backend is required.

## Included
- `index.html` — complete interactive wheel.
- `vercel.json` — simple static deployment configuration.

## Prizes and odds
Each of the four prizes has an equal 25% chance:
1. FREE Oven Cleaning ($50 value)
2. FREE Fridge Cleaning ($50 value)
3. 20% OFF your next cleaning
4. $40 OFF your next cleaning

## Publish on Vercel (no coding required)
1. Unzip this folder on your computer.
2. Sign in at https://vercel.com.
3. Choose **Add New → Project**. If you have the Vercel CLI or GitHub connected, import this folder/repository and deploy.
4. For the simplest path, use Vercel's dashboard flow for deploying a project from a Git repository; alternatively install Vercel CLI and run `vercel` inside this folder.
5. After deployment, Vercel will provide a public URL ending in `.vercel.app`. Send that public URL to customers — not the Vercel dashboard URL.
6. To use your own domain, open the deployed project → Settings → Domains and follow Vercel's DNS instructions.

## Important notes
- The wheel runs in the customer's browser. The selected result is saved in that browser using local storage and the page disables another spin on that browser.
- This is a convenience limit, not fraud-proof: clearing browser data or using another device/browser can allow another spin.
- Because there is no customer data collection or server, the business does not receive a record of who spun or which prize they received.
- Before launch, confirm the promotion's validity period, eligibility, redemption rules, and whether prizes can be combined with other offers.
- The visual odds are equal: each prize is selected with a 25% chance.
