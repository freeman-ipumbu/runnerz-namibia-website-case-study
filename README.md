# Runnerz Namibia — Website & Route Lab Case Study

![Runnerz Namibia website](assets/runnerz-og.png)

**The public launch surface for a Windhoek-first social running network.**

[Runnerz Namibia](https://runnerznamibia.com) · [Android product case study](https://github.com/freeman-ipumbu/runnerz-android-case-study)

> This repository is a presentation-safe product record. The website source, server routes, infrastructure, provider configuration and operational controls remain private.

## My role

**Freeman Ipumbu — Founder, product builder and design researcher**

I designed and built the complete launch experience: product positioning, responsive interface, Windhoek Route Lab, self-hosted map stack, weather integration, Insider conversion flow, social pathways, safety wording, performance work and production-readiness foundation.

## The brief

The website had to make an unfamiliar product understandable in seconds while still proving that Runnerz had real depth behind the campaign language.

The result combines a human launch story with a working route-discovery surface. Visitors can understand the social loop, explore real Windhoek route studies and decide whether the community is for them without being buried in product mechanics.

## Experience highlights

- Cinematic Windhoek launch direction grounded in the actual city.
- Searchable Route Lab with 24 distinct BRouter/OpenStreetMap geometry and elevation studies.
- Route-specific pages with distance, climb, terrain context and honest field-check status.
- Self-hosted MapLibre basemap using a compact Windhoek PMTiles archive.
- Suggested public meetup options ranked by true nearest-route distance.
- Live MET Norway weather and conservative warm/high-UV guidance.
- A seventeen-screen real Android gallery rather than speculative phone mockups, including ranked meetup options, a live Founder portrait, governed recognition, the native share-card studio and a device-aware run celebration.
- Production-shaped Insider registration with validation, consent and truthful delivery states.
- Privacy, support, terms, safety and account-deletion routes.
- Mobile-hardened Route Lab, navigation and gallery behaviour with reduced-motion handling.
- Metadata, sitemap, security headers and production health checks.

## Live product proof

The website now presents the production-shaped Android account journey alongside the wider Runnerz product story.

| Welcome | Secure sign-in | Create account |
|---|---|---|
| ![Runnerz welcome](assets/app-welcome.webp) | ![Runnerz sign-in](assets/app-sign-in.webp) | ![Runnerz create account](assets/app-create-account.webp) |

| Password recovery | Authenticated password update |
|---|---|
| ![Runnerz password recovery](assets/app-password-recovery.webp) | ![Runnerz new password](assets/app-new-password.webp) |

| Live Founder profile | Governed recognition | Privacy-safe share studio |
|---|---|---|
| ![Runnerz Founder profile](assets/app-founder-profile.webp) | ![Runnerz recognition shelf](assets/app-founder-badges.webp) | ![Runnerz share-card studio](assets/app-share-card.webp) |

| Ranked meetup options on the live route map |
|---|
| ![Runnerz ranked public meetup options](assets/app-meetup-options.webp) |

| Device-aware completion moment |
|---|
| ![Runnerz run-completion celebration](assets/app-run-celebration.webp) |

## Product atmosphere

![Windhoek sunrise campaign](assets/windhoek-sunrise.webp)

The visual system uses near-black, electric green, white and mint with a restrained gold signal. It is performance technology with Namibian warmth—not generic fitness imagery or imported cyberpunk decoration.

## Route Lab

![Runnerz Windhoek route concept](assets/route-lab.webp)

The public catalogue includes route studies across Avis, Eros, Olympia, Brakwater, Windhoek Central, Auasblick, Ludwigsdorf, Katutura, Khomasdal, Dorado Park, Pioneerspark, Suiderhof, Kleine Kuppe, Academia, Hochland Park and Cimbebasia.

Geometry is genuine routed open data. Access, lighting, water, road conditions and safety remain explicitly marked for local field verification.

## Engineering overview

- React 19 and TypeScript
- Vinext and Vite
- MapLibre with self-hosted PMTiles, fonts and sprites
- Protomaps/OpenStreetMap attribution and BRouter route studies
- DigitalOcean App Platform deployment behind Cloudflare DNS and edge controls
- Responsive route metadata and map rendering
- Content Security Policy and conservative browser-security headers
- Optimised WebP media and deferred below-the-fold assets
- Structured consent, duplicate prevention and abuse-protection foundations

## Design science loop

```text
LOCAL PROBLEM → PRODUCT THESIS → INTERACTIVE ARTEFACT →
BROWSER + DEVICE EVALUATION → SAFETY CORRECTION → HARDENED RELEASE
```

## Current status

The official website is live at [runnerznamibia.com](https://runnerznamibia.com). Its production verification suite covers public routes, legal and support pages, security headers, health/weather contracts, sitemap coverage, route studies, PMTiles byte-range delivery and canonical host behaviour.

The Route Lab exposes 24 distinct Windhoek studies while keeping field verification explicit. The Insider journey is live with validation and confirmation mail, and the product gallery contains seventeen clean physical-device captures spanning hardened signup and recovery, ranked meetup-map options, an owner-controlled Founder profile, governed recognition, privacy-safe square/Story exports and a finite run-completion moment. This case study records the shipped experience without exposing deployable source, operational endpoints or private configuration.

## Repository boundary

No application source, PMTiles archive, environment file, API implementation, production identifier, subscriber data or deployment configuration is included here.

Security concerns should be sent privately to [info@runnerznamibia.com](mailto:info@runnerznamibia.com).

---

© 2026 Runnerz Namibia. Product and brand material is shared for portfolio viewing. No licence is granted to reproduce the product, identity or documentation.
