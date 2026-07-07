# Noah's Ark Animal Rescue Network

**Rescue. Adopt. Earn Karma.**

Noah's Ark ARN is a global franchise network of animal rescue centres, vets, healing centres, day care facilities and charity shops — all connected through the [OASIS Web4 Karma API](https://oasisomniverse.one). It is one of the core applications within the OASIS Omniverse ecosystem.

The mission is simple: **every stray cat and dog finds a loving home.**

---

## What is Noah's Ark ARN?

Noah's Ark ARN allows anyone to:

- **Report a stray** — submit a stray sighting with location details so the nearest centre can respond
- **Adopt an animal** — browse and enquire about animals available for adoption
- **Find your nearest centre** — locate rescue centres, vets, healing centres and day care
- **Apply for a franchise** — open your own Noah's Ark ARN centre in your city
- **Volunteer or foster** — contribute time, skills or a temporary home for animals in care
- **Donate** — fund food, vet care and rescue operations directly
- **Join the community forum** — share stories, ask for advice and earn karma for helping others

Every rescue, adoption and act of compassion earns **OASIS karma** — a persistent score that grows across every app in the OASIS Omniverse.

---

## Tech Stack

| Layer | Detail |
|---|---|
| Front-end | Single-file `index.html` — inline CSS + vanilla JS, no build step |
| Fonts | Orbitron, Rajdhani, Share Tech Mono (Google Fonts) |
| Animations | Canvas 2D — hero network visualisation (paw pulses between global hubs), mission orbital canvas, star field |
| OASIS API | `@oasisomniverse/web4-api@2.0.2` via esm.sh |
| Forms | formsubmit.co — no server required |
| Hosting | Static — deployable to any CDN or static host |

---

## Karma Actions

| Action | Karma Earned |
|---|---|
| Report a stray | +500 |
| Adopt an animal | +1,500 |
| Volunteer day at a centre | +400 |
| Foster a pet | +1,000 |
| Skills volunteer project | +600 |
| Post in the community forum | +50 |

---

## Sections

- **Hero** — canvas network animation, headline CTAs
- **Stats Band** — rescues, adoptions, centres, karma awarded
- **Mission** — orbiting animals canvas, mission statement
- **Karma System** — rescue (+500) and adoption (+1,500) karma explainer
- **Community Profiles** — example rescued and adopted animal profiles
- **Network** — 8 facility types (rescue centres, vets, healing centres, day care, grooming, training, charity shops, foster network)
- **Report a Stray** — modal form submitted via formsubmit.co
- **Community Forum** — live-feel forum threads, Join CTA
- **Volunteer & Donate** — 4 ways to get involved with karma incentives, volunteer enquiry modal
- **Features** — platform feature overview
- **OASIS Integration** — universal avatar and karma system
- **Global Healing Network** — cross-app animal healing connection
- **Digital Pet** — OASIS digital companion system teaser
- **Franchise** — franchise application with modal form
- **CTA Band** — final call to action
- **Footer** — links, ecosystem navigation

---

## Network Facility Types

| Facility | Description |
|---|---|
| Rescue Centres | Primary shelters for stray and surrendered animals |
| Veterinary Clinics | In-network vets offering subsidised care |
| Healing Centres | Energy and holistic healing for traumatised animals (GHN integrated) |
| Day Care | Animal day care for working owners |
| Grooming Studios | Professional grooming services |
| Training Academies | Behaviour and obedience training |
| Charity Shops | Fundraising retail supporting the network |
| Foster Network | Temporary homes for animals not suited to shelter life |

---

## OASIS Ecosystem

Noah's Ark ARN is one of several interconnected apps in the OASIS Omniverse:

- **GraceBook** — Web4 social network
- **Global Healing Network** — worldwide community of healers
- **Justice League Academy** — free learning platform
- **Our World** — immersive Web4 world
- **OPORTAL** — avatar creation and management

---

## Running Locally

No build step required. Open `index.html` directly in a browser, or serve with any static server:

```bash
npx serve .
# or
python -m http.server 8080
```

---

*Part of the [OASIS Omniverse](https://oasisomniverse.one) · Powered by OASIS Web4*
