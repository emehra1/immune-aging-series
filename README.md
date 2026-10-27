# Immune Aging Series 2027

Site for the Immune Aging Series, evening dinner symposia on immune aging in
Cambridge, Massachusetts, April 2027.

| | |
|---|---|
| **Night I** | Inflammaging: Thu 1 April 2027 |
| **Night II** | Rejuvenating the Immune System: Thu 15 April 2027 |
| **Night III** | Tool Building: date TBD *(contingent on funding)* |

About 100 guests per night. Talks recorded and published; dinner under the Chatham House rule.
A project of the [Harvard College Aging Initiative](https://aging-initiative.org/).

## Files

    index.html     landing page: the plate, the premise, the nights, the five questions, sources
    why-now.html   long-form case with references: what ZEUS changed and why this convenes now
    CNAME          custom domain: immuneagingseries.org

Two static pages, no build step and no dependencies. Fonts come from Google Fonts;
everything else, including the animated hero, is inline.

## Visual system

The engraved scientific plate: jet-black ground, warm bone ink, gold rules, and clay
used exactly once, on ZEUS, the result whose confidence interval crossed the null.
Libre Franklin throughout, using weight contrast rather than decorative italics, with
IBM Plex Mono for labels, numerals and the plate numbers. The layout carries the
character; the type stays quiet.

## The hero

The canvas is a clonal architecture diagram, not decoration. Each ring is a T-cell clone,
radius by clonal frequency; most are hairline outlines, and the few filled in gold have
expanded. Diversity collapsing into a handful of large clones is what immune aging looks
like. Behind it, a flow field of hairline strokes drawn once and drifted.

Everything on the page is a line or a letter: no gradients, no blur, no rounded corners,
no shadows.

## Local preview

    python3 -m http.server 8000

Then open http://localhost:8000.

## Deploying

Static hosting anywhere. For GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.
The site is served at https://immuneagingseries.org. GitHub created the `CNAME` file (the bare
hostname, one line) when the domain was saved under Settings → Pages; keep it at the repo root.
DNS is at Porkbun: four A records on the apex pointing to GitHub Pages (185.199.108.153,
185.199.109.153, 185.199.110.153, 185.199.111.153) and a `www` CNAME to `emehra1.github.io`.
