---
location: San Francisco, USA
alphabet: A
time: 2022-12-12
category: conference notes
hierarchy: none
tags: aeasf, conference, design, development, inspiration
speaker: Rachel Andrew
---
Rachel Andrew

## Notes

• Covid kicked off a boon in CSS features  
• If I would have asked people what they wanted, the would have said faster horses.  
• grid template layout - do developers care about it?  
• why use grid vs flexbox -  
• grid usage is very low only 12%, most using flexbox  
• flexbox provided faster horses  
• container queries like media queries  
• very simple so why did it take so long? needed underlying tech update to keep loop from happening  
• Containers need some size definition  
• Use has() to see what's in the box versus having to use css classes too much  
• has() + container queries super power (allows expressive variations)  
• subgrid - safari and firefox, chrome soon  
• Inherent accessibility issues since layout can move content around page out of tab order. Layout may need some alignment with tab order based on screen type  
• Don't add anything new to css layouts until accessibility is fixed  
• How would screen readers deal with the content order change as CSS moves things vs how they're displayed? reading-order property  
• Auto would follow the grid definition to keep developers from having to keep track of each boxes layout  
• Still allows developers to assign in case they need control  
• Frameworks may inflate adoption rates; Sometimes you can measure framework adoption vs organic by looking at specific code usage  
• Frameworks may have lag because they'll break things and people complain. Individual developers will be able to move faster on adoption  
•  
  
## Reflections  
• how do we tag which features can be used where "Ready for Design System" or the like