---
location: San Francisco, USA
alphabet: A
time: 2022-12-12
category: conference notes
hierarchy: none
tags: aeasf, conference, design, development, inspiration
speaker: Jeremy Keith
---
Jeremy Keith

## Notes

• Two styles of programming, imperative and declarative  
• Declarative is typically domain specific (SQL, GraphQL, etc)  
• "Vague but exciting..."  
• Power of Least Powerful (HTML, CSS, both are fault tolerant)  
• Every line of CSS you write is a suggestion to the browser  
• CSS originally had a measure of "influence" to specify how much your cared about a property setting (precursor to !Important and @prefers)  
• JavaScript is imperative and not fault tolerant (brittle) more powerful  
• constraint validation API  
• Declarative solutions should cover 80% of use cases and imperative 20%  
• geo location and web share api are JS only, web share needs a button/interactive element  
• Why isn't there a button type="share"  
• [github.com/adactio/share-button-type](http://github.com/adactio/share-button-type)  
• ARIA as another slice of the webstack (HTML, CSS, JS, +ARIA)  
• "JavaScript should only do what only JavaScript can do"  
• People who use imperative vs declarative might be trying to have control (i.e. people who create a div and then make it perform like a button)  
• cal(0.5rem + 0.666vw) takes into account user scaling  
• clamp() can restrict within a range  
• Giving up control. You cannot now what the specific output will look like at every level of screen size/zoom  
• It's about setting boundaries for the computer  
• [every-layout.dev](http://every-layout.dev/)  
• [buildexcellentwebsit.es](http://buildexcellentwebsit.es/)  
• Whether declarative > imperative is about culture  
• Do you measure the outcomes or outputs (time vs product)  
• Make company culture explicit through Design Systems  
• "The way we do things around here"  
• analytical vs systems thinking (zooming in vs zooming out)  
• Set design principles and use calculations to achieve result (can those rules be defined)  
• Classical vs Jazz teams (reading sheet music vs improvisation) (depends on the team)  
• [cloudfour.com/thinks](http://cloudfour.com/thinks)  
• Tools reflect imperative mindset (high fidelity and detailed)  
• Designing in the browser or deciding in the browser  
• Tailwind and CSS-in-JS treat C in CSS as a bug not as a way to amplify CSS  
• imperative make sense in print, native, desktop apps not so much for the web  
• It's all about uncertainty  
• Control is an illusion  
• Reread Dao of Web Design on ALA  
• Use the tools the way they are meant and use supplementary tools to cover gaps. Don't try to make figma into the browser  
• "web design" tools are jack of all trades master of none  
• Figma is already in the web it could make the leap to be more web-like, but there's no good tool for web design today  
• The more control you assert over accessibility you may make it less accessible (more ARIA is not better because you are making assumptions about use - fall back to Rule of Least Power)  
• ARIA is meant as a polyfill for accessibility  
• progressive enhancement - it won't look the same in all browsers - let it go  
• Struggle of building a design system that doesn't fit the community direction. Declarative design vs Imperative developers - especially hard in a mobile first and contractor heavy houses  
•  
  
## Reflections  
• Trying to fix a problem so hard aka "Never go full retard"