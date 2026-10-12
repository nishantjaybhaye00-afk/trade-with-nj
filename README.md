# Trade With NJ — ₹99 PDF website

This is a static, mobile-friendly starter website for your trading-education PDF.

## Files
- `index.html` — sales page
- `privacy.html` — privacy policy draft
- `terms.html` — terms/refund policy draft

## Before publishing
1. Finish your PDF and ensure you have the rights to all charts/images/content.
2. Edit `index.html` so every product feature accurately matches the PDF.
3. Replace `YOUR_SUPPORT_EMAIL` with a business support email in all files.
4. Read and customize `privacy.html` and `terms.html`; they are templates, not legal advice.
5. Do not take payments until the PDF, delivery method, policies, and payment link have been tested.
6. Do not put the paid PDF in this public website repository. Anyone could download a file committed to a public repository.

## Free deployment with GitHub Pages
1. Create/sign in to a GitHub account at https://github.com/
2. Create a new **public** repository named `trade-with-nj`.
3. Upload `index.html`, `privacy.html`, and `terms.html` to the repository root.
4. Open repository **Settings → Pages**.
5. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for the Pages URL to appear. It will resemble `https://YOUR-USERNAME.github.io/trade-with-nj/`.
7. Open the URL on a phone and desktop and test every link. GitHub Pages documentation: https://docs.github.com/en/pages

## Payment setup (manual delivery to start)
1. Apply for a merchant account with a payment provider such as Razorpay and complete its onboarding/KYC. Approval is not guaranteed; describe the product honestly as trading education and ask the provider if it is permitted under their current terms.
2. In the provider dashboard, create a hosted Payment Link for INR 99 and a clear description such as `Trade With NJ — educational strategy PDF`.
3. Test the link using the provider's supported test process before accepting real payments.
4. Once approved and live, open `index.html` and replace the placeholder in the Buy section with the real hosted payment URL. Example:
   `<a id="buyButton" class="btn primary" href="https://YOUR-REAL-PAYMENT-LINK">Pay ₹99</a>`
5. Re-upload the edited file to GitHub.
6. For the first orders, verify each payment in the provider dashboard (never trust a screenshot alone), then email the PDF to the buyer's provided address. Keep a simple order log and only collect the information you need.
7. Do not put your payment provider secret/API key in HTML or JavaScript. Public website code is visible to everyone.

## Secure PDF delivery
For the lowest-cost launch, manually email the PDF after verifying payment. Do not place the PDF in the public GitHub repository or use an unprotected public download URL.
For automated delivery, use a reputable digital-product service that supports your Indian merchant/payment setup, or build a backend that verifies payment webhooks and issues expiring download links. A static GitHub Pages site alone cannot securely verify payments or protect a paid file.

## Important
This starter page is not a payment integration and does not process or verify payments itself. The purchase button must be connected to your own approved live payment link before launch. Review applicable Indian laws, tax obligations, consumer rules, and any SEBI requirements that may apply to your actual activity. Do not sell investment advice/trade calls or make return promises without appropriate legal review.
