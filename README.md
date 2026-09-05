# Immune Aging Series 2027

Site for the Immune Aging Series — three evening dinner symposia on immune aging,
Cambridge, Massachusetts, April 2027.

| | |
|---|---|
| **Night I** | Inflammaging — Thu 1 April 2027 |
| **Night II** | Rejuvenating the Immune System — Thu 8 April 2027 |
| **Night III** | Tool Building — Thu 15 April 2027 *(contingent on funding)* |

~75 invited guests per night. Talks recorded and published; dinner under the Chatham House rule.
A project of the [Harvard College Aging Initiative](https://aging-initiative.org/).

## Files

    index.html     landing page — the plate, the premise, the three nights, the five questions
    why-now.html   long-form case: what ZEUS changed and why this convenes now
    CNAME          custom domain (add when the domain is registered)

Two static files, no build step and no dependencies. Fonts come from Google Fonts;
everything else — including the animated hero — is inline.

## Visual system

The engraved scientific plate: jet-black ground, warm bone ink, gold rules, and clay
used exactly once — on ZEUS, the result whose confidence interval crossed the null.
Libre Franklin throughout — weight contrast rather than decorative italics — with
IBM Plex Mono for labels, numerals and the plate numbers. The layout carries the
character; the type stays quiet.

## The hero

The canvas is a clonal architecture diagram, not decoration. Each ring is a T-cell clone,
radius by clonal frequency; most are hairline outlines, and the few filled in gold have
expanded. Diversity collapsing into a handful of large clones is what immune aging looks
like. Behind it, a flow field of hairline strokes drawn once and drifted.

Everything on the page is a line or a letter — no gradients, no blur, no rounded corners,
no shadows.

## Local preview

    python3 -m http.server 8000

Then open http://localhost:8000.

## Deploying

Static hosting anywhere. For GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.
To attach a custom domain, put the bare hostname in `CNAME` (one line, no protocol) and point
the registrar's DNS at GitHub Pages.
