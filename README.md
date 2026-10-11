# AvoR744 — Claude Startups setup

This package contains a one-page website based only on the information in the uploaded engineering project document.

## Cheapest practical setup

1. Buy one domain. Recommended for credibility: a short `.com` if the name is available.
2. Create a free Cloudflare account.
3. Deploy this `index.html` to Cloudflare Pages.
4. Connect the custom domain.
5. Create `contact@yourdomain.com`.
   - Since you already have ExpressVPN/ExpressMailGuard, you can use its Custom Domain feature.
   - Alternatively, Cloudflare Email Routing can forward incoming mail to an existing inbox at no extra charge.
6. Verify that `contact@yourdomain.com` receives mail.
7. Create/sign in to Claude Console and submit the Claude Startups application.

## Important

The Claude Startups program currently says applicants need a Claude Console account, a company email matching the website domain, a website, and a short description. Anthropic reviews applications.

Do not claim VC funding, revenue, a manufactured product, customers, patents, or a legally incorporated company unless those facts are true.

The uploaded thesis/project document says the current scope is engineering design; it explicitly does not include automation, manufacturing, or physical construction. Keep the application consistent with that unless the team has since progressed beyond the document.

## Suggested application positioning

Company/project: AvoR744

One-line description:
"Early-stage engineering project developing a CO₂ (R-744) refrigeration design for avocado cold storage in Mexico."

Longer description:
"We are developing an engineering design for a stationary cold-storage chamber for 1–5 metric tons of avocado in Morelia, Michoacán. The system uses CO₂ (R-744) as a natural refrigerant. Our work focuses on thermal-load calculation, analysis of the CO₂ refrigeration cycle, mechanical component selection, and life-cycle cost evaluation. We are exploring how this engineering concept could evolve into a practical solution for post-harvest avocado storage."

## Before submitting

Replace `YOURDOMAIN` in `index.html` with the domain you actually purchase.
