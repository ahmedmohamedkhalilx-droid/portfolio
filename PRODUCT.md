# PRODUCT.md — Ahmed Khalil, freelance web development

## What this is

A one-person freelance practice building production websites for small firms and
businesses, with a specialism in **bilingual English/Arabic sites that work
properly in both directions**. The portfolio site is the sales surface: it exists
to turn a stranger into an enquiry.

## The unique mechanism

Most small-business sites in this market are template installs that look finished
and fail quietly — mail that lands in spam, a menu that does nothing on an iPhone,
an Arabic layout that is the English one flipped badly. This practice ships the
unglamorous layer underneath: deliverability, indexing, touch targets, real RTL,
a deploy pipeline that proves what went live.

## Audience and scene

A business owner or office manager, mid-30s to 60s, in Cairo or the Gulf. Not
technical. Has either been burned by a cheap site or has an ageing one that
embarrasses them. Reads on a phone, often in the evening, often in Arabic. They
are not shopping for frameworks; they are shopping for someone who will not
disappear and whose work will not quietly break.

## What the surface must prove

That one real site was taken all the way — and that the person behind it finds
and fixes the things nobody else checks. Depth over breadth is the honest and
stronger position: there is **one** client project, done thoroughly.

## Real proof available (all verified, all from the HELCO engagement)

- **hanyelaraby.com** — live bilingual site for Hany ElAraby & Co, an Egyptian
  audit, tax and advisory firm. English and Arabic, full RTL.
- The firm's domain had **no SPF and no DMARC record at all**; every email it
  sent was unauthenticated. Diagnosed via public DNS and fixed at the zone.
- Contact and CV pipeline on a **static site with no backend** — PHP mail with
  attachment support, honeypot and timing spam filters, routed to separate HR
  and business inboxes.
- **24 sub-44px touch targets reduced to 0**; a 2.8:1 contrast failure raised to
  5.32:1; forms rebuilt to stop iOS Safari's focus-zoom trap.
- An **iOS-only defect** where Safari withholds click events from
  non-interactive elements — cards that passed every emulator did nothing on a
  real iPhone.
- A **host-level caching fault** serving visitors a stale build after every
  deploy, proven from response headers and fixed with `X-Accel-Expires` once
  `Cache-Control` proved to be ignored.
- Technical SEO from nothing: sitemap, robots, per-page canonical and hreflang
  across two locales, `AccountingService` structured data, HTTP→HTTPS.
- **Zero dead links or dead anchors** across 18 pages in two languages, verified
  by a crawler written for the project.

## Action

One primary action: start a conversation. Email is the channel.

## Constraints and honesty rules

- One client project. Do not imply a roster, a team, or years of trading.
- No invented testimonials, client counts, prices, or availability claims.
- Every metric on the surface must trace to a measurement actually taken.
- Client is named with permission (confirmed 2026-09-28).
- No source-code links and no code on the surface. The audience buys an
  outcome, not a repository; findings are stated in plain English.

## Assumptions to confirm

- Contact email: `ahmedmohamedkhalilx@gmail.com` (chosen over the AUC address as
  the better channel for client work). **Unconfirmed by the user.**
- No phone number or WhatsApp published — omitted rather than invented.
- No rates published.
