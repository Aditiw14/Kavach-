# Kavach (कवच) — Scam Shield for India

Paste a suspicious SMS, WhatsApp forward, link or call script and Kavach scores it for Indian scams
(digital arrest, fake KYC, UPI refund traps, task-job fraud) in English, हिन्दी and Hinglish.

- Message scanner with highlighted trigger words
- Link inspector (look-alike domains, shorteners, punycode, raw IPs)
- "Digital arrest" scam-call drill
- Family circle with one-tap WhatsApp alerts and a flip Guardian card
- Step-by-step "Been scammed?" checklist (1930, cybercrime.gov.in)
- Rule-based assistant, dark mode, English/हिन्दी toggle

Everything runs in the browser. Nothing a user pastes is sent anywhere.
Single static file: `index.html`. No build step.

## Run locally
Open `index.html` in a browser.

## Deploy
Import the repo in Vercel (Framework Preset: Other), or run `npx vercel --prod`.

> Prototype. The detector is rule-based and does not replace reporting to the National Cyber Crime Helpline 1930.
