---
location: San Francisco, USA
alphabet: A
time: 2022-12-14
category: conference notes
hierarchy: none
tags: aeasf, conference, design, development, inspiration
speaker: Eric Meyer
---
Eric Meyer

## Notes

* 26 years since css 1, followed quickly by css 2 seventeen months later
* Looking at ideas from the community browser makers have to figure out performance/memory
* Browsers have to render pages at a minimum of 60fps (floor)
* Introduced in jQuery based on css proposal in 2007
* eye/o also created a abp-has() (ad block plus) 
* hired igalia to advance the web feature in the CSS standard
* prototype in chromium 
* Went from 13% to 84% in about a year
* Plan for future use for external
* Use now for internal where browser can be controlled
* be careful of side-effects and picking up the wrong elements
* has() = hasRelationship()
* NO NESTING no :has(:has())
* NO PSEUDO ELEMENTS ::before, ::after
* NO INSIDE pseudo elements ::slotted(:has())
* NO AFTER pseudo element ::first-line:has()
* NO VISITED :has(a:visited)
* forgiving-relative-selector-list goes inside the has()
* parts that aren't valid are dropped
* performance is around 1.5ms
* pseudo focus within possibilities
* using for validation
* Sometimes it takes someone from outside the team to spark innovation
* 

## Reflections

* I can :has()
* shame bookmarklet for QA