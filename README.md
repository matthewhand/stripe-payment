
# Stripe Payment Project

This project was entirely developed using ChatGPT and the Noteable plugin. It demonstrates the implementation of:

- A Stripe donation button, including the creation of the payment link via the Stripe API.
- Deploying code to GitHub using the GitHub API.
- Creation of a GitHub README.md that includes a generated image.
- A NodeJS Stripe deployment to Vercel hosting via the Vercel API.
- Modifying open source software using natural language.

## Donation Button

If you find this project useful, you can support its development by making a donation. Think of it as buying me a coffee. Click on the button below to make a donation. You can choose an amount between 1 and 99.

[![Donate with Stripe](https://img.shields.io/badge/Donate%20with-Stripe-blue.svg)](https://buy.stripe.com/00g14peASeEd7xCcMM)

<img src="https://github.com/matthewhand/stripe-payment/raw/main/qr_00g14peASeEd7xCcMM.png" width="150" />

Or send to my Ethereum (ETH) wallet
`0xDf994CeA5a0a11397C938cd903259E8496DA15f5`

<img src="https://github.com/matthewhand/stripe-payment/raw/main/etherium-qrcode-receive.png" width="150" />

## TODO

- [ ] Deploy Stripe donation button
  - [x] Create donation button using Stripe API.
  - [ ] Update Strip donation button referenced payment link to support at least Google Payment.
- [ ] Deploy nextjs-subscription-payments github project
  - [x] (User) fork github project into https://github.com/matthewhand/nextjs-subscription-payments
  - [ ] Configure Supabase as per instructions
- [ ] Deploy accept-a-payment github project
  - [x] (User) Forked accept-a-payment github and linked to Vercel.
  - [ ] accept-a-payment does not return HTTP error 404 on Vercel.
  - [ ] accept-a-payment is updated to use custom image and text.
- [ ] Deploy strip-checkout-next-js-demo github project
  - [x] (User) Forked stripe-checkout-next-js-demo and deployed to Render.com
  - [x] (User) Forked stripe-checkout-next-js-demo and deployed to Netlify
  - [ ] stripe-checkout-next-js-demo is updated to use a payment link to a product in my stripe api.
  - [x] stripe-checkout-next-js-demo is updated to use custom image and text.
  - [ ] stripe-checkout-next-js-demo is updated with correct price.
- [ ] Deploy Paypal donation button
  - [ ] Research using webpilot plugin how to deploy paypal donation button

## Notebooks

The files in the 'notebooks' folder are the raw files created by ChatGPT. They contain the Python code that was executed to develop this project.

![Human AI Conflict](https://github.com/matthewhand/stripe-payment/raw/main/human_ai_conflict.png)

The image above represents the symbiotic relationship between human and machine.

*"Imagination is not what we think, it is how we think" -- Unknown*
