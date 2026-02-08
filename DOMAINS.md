# LaunchAgent Domain Setup

## Domain
- **launchagent.dev** — purchased on Porkbun Feb 7, 2026

## Stripe (LIVE)
- Product: LaunchAgent - Managed AI Hosting
- Price: $29/mo with 7-day free trial
- Payment Link: https://buy.stripe.com/14A00ia5i6B08Irgn5cbC02
- Payment Link ID: plink_1SyKjMAhRKVsguBFknG9j7g4
- Accepts: Card, Apple Pay, Klarna, Link, Cash App Pay, Amazon Pay

## DNS Setup Needed
Point launchagent.dev to Surge hosting:
- CNAME: `www` → `na-west1.surge.sh`
- For apex domain, may need Surge premium or redirect www→apex

## Staging
- Live at: launchagent.surge.sh (Surge free tier)
- Source: ~/clawd/openclaw-deploy/index.html
