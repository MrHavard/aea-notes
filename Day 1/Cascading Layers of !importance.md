---
location: San Francisco, USA
alphabet: A
time: 2022-12-12
category: conference notes
hierarchy: none
tags: aeasf, conference, design, development, inspiration
speaker: Miriam Suzanne
---
Miriam Suzanne

## Notes

• Browsers provide a default design to content  
• The fact that we control a paper page limits its usefulness  
• @prefers @supports how do we plan for unknowable  
• restrictions restrict designer creativity  
• user > author > implementer  
• 700 css properties???  
• There can be only ONE!  
• Cascading and inheritence  
• Multiple styles can enter only one can leave (coin sorter)  
• Who requested it and how much do they care  
• Browser defaults (user agent styles) give basic readability  
• User styles from user preferences  
• Author stylesheets  
• "Are we the baddies?"  
• !important is binary priority 100% or 0%  
• Universal Element Reusable Unique (globals, elements, classes, ids)  
• broad reach and low specificity is the ideal  
• settings tools generic elements objects components overrides/utilities  
• Assumptions often fail at scale (multiple classes vs bem)  
• !important as a hand grenade (causes frustrations)  
• Cascade Layers - broad support + pollyfill  
• @layer contains specificity (order of import)  
• Can set order by doing list of names @layer name, name, name;  
• Can be nested  
• layer component + layer state or @layer component.state  
• Managing priorities and describing intent  
• More cascade control and less use of !important  
• Origins?  
• Protect styles form future layers, use !important  
• unlayered styles take precedence. Try to get everything in a layer for more flexibility  
• Tools won't let you use features until they add it (i.e. css-in-js, nx, etc) (will the tool get in your way  
• Goes back to the origins of CSS being able to define a sliding scale of importance vs binary  
• No harm in using layers but not the only tool  
• other ways to manipulate specificity using [id="example"] or :where()  
• upcoming @scope (root) to (boundary) to help with specificity  
• Much of this negates need for bem or local scoping techniques with default css  
• Nesting style into the HTML using scope slightly different than shadow dom without the restrictions for styles going into/out of the shadow dom  
• available in chromium canary  
• Don't fear the cascade  
• Check website on how to enable disable layers  
• Pollyfill with pre-processor for older browser  
  
## Reflections  
• We use !important as a hack to the boost specificity when things are broken in our own system, not interacting with user preferences.  