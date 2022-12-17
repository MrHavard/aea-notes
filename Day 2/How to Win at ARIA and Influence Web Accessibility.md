---
location: San Francisco, USA
alphabet: A
time: 2022-12-13
category: conference notes
hierarchy: none
tags: aeasf, conference, design, development, inspiration
speaker: Tolu Adegbite
---
Tolu Adegbite

## Notes

* Designers/Developers don't need to now ARIA back to front
* Use native components as much as possible
* Tooltip problems: getting focus and escaping/closing
* Carousel is the least favorite component
* w3c aria components documentation
* Landmarks correspond to native html components 
* Sometimes they don't work in specific browsers and need additional ARIA markup for consistency (not normally a good idea for other ARIA roles/attributes)
* Use fieldsets for grouping and context
* If the data requires more than a basic table take a step back and talk about whether table is the right thing to use (just because it's possible doesn't mean you should)
* Feed fuels "doomscrolling" and needs feedback to user indicating where you are in page/results
* Using landmarks help someone skip past other parts of the page
* WAI-ARIA 1.2 due next year
* No ARIA > bad ARIA 
* "Loving the page to death"
* Role is a promise/contract
* Might be better to skip if you don't understand it
* Use ARIA to fill gaps, not duplicate what already exists (except Landmarks)
* Widget - mostly describes JS usage for interaction
* Document structure - headings, articles, main, search, etc.
* Complimentary landmark (an aside or supplementary information)
* contentinfo for copyright and things that usually go into footer
* Landmarks are important to speed navigation and reduce repetitive interaction
* Don't want to make it so that only certain people can access content
* labeledby and describedby  and label have different purposes, label vs help vs text for unlabeled content
* svg inconsistent support role="img" aria-label="some text description"
* aria-live can control how intrusive the element is to the user
* avoid positive tabindex values. Stick to -1 or 0 with caution 0 for interactive elements to get them into tab order
* Roles must be valid and existing - don't make them up
* Make sure roles work together (i.e. some only work with certain attributes/nesting)
* wave toolbar, axe tool, google developer tools

## Reflections