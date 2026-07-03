# Copilot × Supertab — Paywall Prototype

An interactive prototype showing how **Supertab** can act as the paywall to help an AI
assistant (Microsoft Copilot, as the demo example) monetize premium responses — via either
a frictionless **$0.25 micro-payment** ("Get Access Now, Pay Later") or a **subscription upsell**.

## Live demo

Enable GitHub Pages (Settings → Pages → Deploy from branch `main` / root), then open:

```
https://jw1019.github.io/copilot-supertab-demo/
```

> Note: GitHub Pages on a **private** repo requires a paid plan. Make the repo public to use
> the free tier, or drag `index.html` onto https://app.netlify.com/drop for an instant public URL.

## The flow

1. **Ask** — send a message in the Copilot chat (or tap a suggestion chip).
2. **Free overview** — Copilot returns a quick free answer, then offers an in-depth version
   with a suggestion chip tailored to what you asked.
3. **Offer** — tapping the chip goes straight to the premium offer: *Upgrade Plan* or
   *Get premium answer for $0.25*.
4. **Supertab paygate** — choose the one-tap micro-payment ("Get Access Now, Pay Later") or
   a Standard Monthly / Quarterly / Yearly subscription.
5. **Unlock** — the premium, in-depth answer is revealed in-chat.

Use the **Restart demo** button (bottom-right) to run through it again.

## Running locally

It's a single self-contained HTML file — no build step, no dependencies.
Just open `index.html` in any modern browser.

## Notes

- Copy and the premium answer are illustrative placeholders for demo purposes.
- Supertab branding/colors are stand-ins; swap in exact brand assets as needed.
