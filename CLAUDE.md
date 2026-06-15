# The Smith Team (Maui) — site rules

Redesign for client **The Smith Team** (Ken, Gregory, Melissa Smith) — Coldwell Banker
Island Properties, Wailea, Maui. Rebuilt from scratch as **one self-contained HTML file**.

> ⚠️ **This is a PITCH demo to win the design contract.** The client has NOT provided their
> real listing/headshot assets yet — image slots are filled with stand-ins (see below). Real
> assets get swapped in *after they sign*.

> Canonical repo is **here** (`C:\Users\Tanne\smith-team-maui\smith-team-maui.html`). The
> `Sessions\smith-team-maui.html` copy in OneDrive is **stale** — edit this repo.

## Stack
Single file `smith-team-maui.html`, **no frameworks** — inline CSS, deferred JS,
IntersectionObserver reveals **with a JS failsafe** (content must show if JS fails).

## Deploy (temporary pitch host)
- Vercel team **fireline-web-design**, project `smith-team-site`, deployed from a copy at
  `Sessions\smith-team-site\index.html`. Re-deploy:
  `npx vercel deploy <dir> --yes --scope fireline-web-design` (needs a fresh token).
- Share **only the clean alias** https://smith-team-site.vercel.app — the auto-generated
  `…-<hash>-…vercel.app` URLs sit behind Vercel Authentication (401).
- GitHub `tannermosher2015-debug/smith-team-maui` (SSH, `main`). Sync: `git pull --rebase`
  before work, push after (`SYNC.md`).

## Design (warm-organic island luxury)
- Fonts: **Fraunces** (display) + **Figtree** (body).
- Palette: bg `#F6EFE4`, surface `#FFFDF9`, primary teal `#1E3A34`, accent terracotta
  `#C16A3E` (seller band deepened `#92421F`→`#5E2910` for AA), text `#241F1A`.
- **WCAG-AA verified** across all text pairings; mobile hamburger tested at 375px. Keep it AA.

## Real data (already wired — NOT placeholder)
Phone (808) 572-0866 · team@mauisales.com · 3750 Wailea Alanui #A-37, Wailea HI 96753.
Trust stats are sourced facts (35 yrs / 3 gens / Top-3 agent / 5.0 Zillow) —
**do not use the "450+ families" claim** (that 450 was the statewide agent pool, not clients).

## Swap before real launch
Real MLS listing exteriors, professional team headshots (currently **Fraunces monogram
avatars** KS/GS/MS — deliberate, never fake stock faces), OG image, Google Map embed, verbatim
Zillow review text, real social URLs. Self-host + optimize the demo **Pexels** photos
(hero ≈423KB is heaviest); each already has an `onerror`→gradient fallback. Re-verify listing
prices/status (live MLS changes).
