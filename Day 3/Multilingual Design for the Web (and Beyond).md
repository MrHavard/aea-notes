---
location: San Francisco, USA
alphabet: A
time: 2022-12-14
category: conference notes
hierarchy: none
tags: aeasf, conference, design, development, inspiration
speaker: Preston So
---
Preston So

## Notes

* Are we building widgets that expect a simple swap of content or are different based on language
* Biggest growth market is non-English speaking non-latin alphabet
* Text in all directions RTL, LTR, Vertical
* Annotations and decorations of text
* Logical properties in CSS 
* What about spoken language in audio and video attachments
* One to many relationship between writing language and writing system
* Abugidas - think about formatting text (English vs Devanagari/Thai)
* Language attributes distinguish between writing systems
* keep language attribute as short as possible. Only use locals when necessary i.e. en/zh vs en-us/zh-TW
* Language attributes help with both SEO and synthesized speech from screen readers
* CSS can select on lang attributes and :lang pseudo class is available recently
* Variations in script, e.g. cursive vs print; casual vs formal?
* Locals may use different variations of the script
* font-feature-settings properties to manage variations of font-glyphs being used
* ligatures, subsets, historical forms
* Understanding the culture of use among the users 
* abjad - symbols for consonants with little decorations for vowels
* if using LTR/RTL inputs need to be accounted for i.e. dir="auto"
* writing-mode property - multiline directionality (vertical left to right, vertical right to left)
* Chinese reads vertically top to bottom, Arabic vertical from bottom to top
* Embedded text may flip the orientation to fit surrounding text
* Sideways orientation using sideways-lr/rl for things like tables 
* text-upright-combine can compress text into a combined space based on orientation
* Use HTML attributes vs CSS
* Syllabary encodes a word in a single character cherokee and japanese do this
* Ruby annotations provide phonetic translations
* Like creating definition lists in your text  `<ruby><rb><rt>`
* logographic systems have text decorations - text emphasis is used in other languages (see bouten)
* block and inline don't work for languages that have other directions
* Logical properties help set properties in a language neutral way
* Chen Hui Jing Logical properties list
* SSML used to author dialog for voice interfaces
* Can define gender, pitch, pause, etc
* How do we manage signed languages - no specific support right now
* How does hyphenation work in other languages based on direction
* Inclusivity is important. It's not about putting text in a box.
* Speaks 13-14 languages reads 22
* How does it scale? 
* Can CMS specify each content blocks language and pass that back to the client
* Think about backends too
* 