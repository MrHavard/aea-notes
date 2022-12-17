---
location: San Francisco, USA
alphabet: A
time: 2022-12-12
category: conference notes
hierarchy: none
tags: aeasf, conference, design, development, inspiration
speaker: Chris Coyier
---
Chris "Clutch" Coyier

## Notes  
  
• [breakfast-burritos.chriscoyier.net](http://breakfast-burritos.chriscoyier.net/)  
• container queries reduce micromanagement of content on a page  
• pollyfill for container queries  
• animation the WAAPI animations api, can be used via JS without a library  
• scroll-linked animations (just css)  
• FLIP - First Last Invert Play - make more performant animation  
• Don't have to micromanage the animation  
• Self hosting fonts is a great idea  
• WOFF2 is fine for everyone  
• Font display swap to display fallback first and then swap when webfont loads  
• Use optional to show on next load  
• Variable fonts to optimize font loading sizes using a single file with all font variations  
• Fluid type to be responsive (use clamp to keep within bounds)  
• Container units cqw (container query width) cqi for inline size  
• Images are easy (not) size, format, lazy loading, preconnect/cdn, optimization  
• image cdn's can process the images and provide all the variations, act as a proxy (see cloudinary, cloudflare)  
• Chris likes the word clutch  
• Component is arbitrary, it's whatever your team decides it is  
• Shoutout to css-modules, likes local scope for components  
• back-of-front, front-of-front, designer all together  
• Component is responsible for getting it's own data  
• astro.fetchContent (from markdown file?)  
• layout templates?  
• Do as much as possible at the edge  
• Use edge functions to get data from CDN (cloudflare workers)  
  
## Reflections  
• lots of layers...