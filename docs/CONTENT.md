# Project-page content checklist

Use this document to gather the final material before editing `index.html`.
Keeping the answers concise will make the page easier to scan.

## Identity

- **Expanded project name:** What does “HiL-HySAC” stand for?
- **One-sentence description:** 20–35 words, understandable without the paper.
- **Venue and year:** For example, “Conference 2026”.
- **Authors:** Full display names, in paper order.
- **Affiliations:** Institution names and author-to-affiliation mapping.
- **Contact:** A public project email or corresponding-author address.

## Project links

- **Paper:** Publisher, proceedings, or arXiv URL.
- **Code:** Public source repository URL.
- **Models/checkpoints:** Direct landing-page URL.
- **Dataset:** Dataset landing-page URL and access conditions.
- **Video/demo:** YouTube, Vimeo, or an accessible MP4/WebM file.

Remove unavailable resource rows instead of publishing dead links.

## Overview

Provide the final abstract or a shorter project-page version containing:

1. the problem and why it matters;
2. the limitation of existing work;
3. the central technical idea;
4. the evaluation setting; and
5. the main quantitative result.

Aim for 100–160 words. Define acronyms on first use.

## Method

For each of the three method cards, provide:

- a two- or three-word stage name;
- a 20–35 word explanation; and
- the matching label used in the method diagram.

Add a method overview figure to `assets/`. SVG is preferred for diagrams; WebP
is preferred for photographic or rendered content. Every figure should include
descriptive alternative text in `index.html`.

## Results

Choose one lead figure that communicates the main finding without requiring the
paper. Provide:

- a concise caption explaining the comparison;
- the evaluation dataset/environment;
- the number of seeds or trials, if applicable; and
- whether uncertainty bars represent standard deviation, standard error, or a
  confidence interval.

Fill the three headline metrics with a value and a short label. Avoid reporting
percent improvement unless the baseline and calculation are unambiguous.

## Citation

Paste the official BibTeX exactly as supplied by the publisher or preprint page.
Then:

1. replace the sample inside `<pre id="bibtex">`;
2. remove the element’s `hidden` attribute;
3. remove `disabled` from the “Copy BibTeX” button; and
4. replace “BibTeX will be added on publication” with a useful instruction.

## Social preview

Create a 1200 × 630 px preview image containing the project title, short
description, and one recognizable visual. Save it as
`assets/social-card.png` and add the `og:image` tag described in the README.

## Accessibility and release review

- All meaningful images have accurate `alt` text.
- Decorative images use empty `alt=""` or are hidden from assistive technology.
- Heading levels remain sequential.
- Text is understandable without relying on color alone.
- Links describe their destination.
- The page is usable with a keyboard.
- Reduced-motion preferences are respected.
- Content has been reviewed by at least one project author.
