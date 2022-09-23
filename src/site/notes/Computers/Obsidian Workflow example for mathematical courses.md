---
{"dg-publish":true,"permalink":"/computers/obsidian-workflow-example-for-mathematical-courses/","dgHomeLink":true,"dgPassFrontmatter":false}
---

# Obsidian Workflow example for mathematical courses
This is an suggestion on how to use Obsidian for university courses that are mathematical, especially when the lectures are divided in definitions, theorems, examples, corollaries, etc. 

The goal of this document is only to provide a starting point for someone who doesn't really know Obsidian but wants to implement it as simply as possible in their everyday math-learning habits.

For general information about how to use Obsidian, see https://help.obsidian.md

## Why I use it
- I don't like scrolling through endless PDFs and wanted to have something less "linear" than the professor's notes and more reusable than my own handwritten notes. 
- Also, reading through a PDF doesn't help me memorize information, nor find it quickly. I need to see several definitions and theorems at the same time, and read each of them over and over again. 
- I also want to make connections in my mind between things that would be taught separately, and separate some things that are taught together. 

## How to write a note 
- Generally, each theorem, each definition and each corollary has its own note with a specific template. Examples and remarks are added inside of the corresponding note, separated by a separator line (syntax: ```---```). 
- There is a collection note for each chapter/section of the lecture, that links to every note brought up by the professor in that section. With the **page preview plugin**, this is easier to navigate than the lecture notes, because you don't have to scroll down and loose sight of what you were reading before. 
- There are also "collection notes" that create a connection between notes that was not explicitly given in the lecture. This is a way for a student to make interesting connections between different concepts that were presented accross several different chapters throughout the course. For example, you could make a list of all the ways you solved the same physics problem, or all the functions that have a common property. 
- It is also a way to find specific tools quickly, for example, you could set up a list of all the operators you used in a physics class. 

## Metadata, tags and templates
- To use **templates**, activate the plugin in the `settings > core plugins`. 
- [[Templates/simple note|This]] is the template I use for a template about a single theorem/definition. Sometimes, I add remarks about the concept or examples (from the lecturer or my own) inside the same note, separated with a `---`. For theorems I might add a proof, also visually separated. 
- In the top of the template, there is a frontmatter that lets you enter other names for the note, and tags. The tags are simply the location of that definition/theorem in each university course. For example if I saw a concept in my logics class, but also in my linear algebra class, then the note could have both tags `#linearAlgebra/VectorSpaces`and `#logic`. See Obsidian help for more information about Tags and YAML Frontmatter. 
- Writing in LaTeX can take a lot of time, and some definitions are not worth taking the time to copy them (if you already know them well), but are still worth keeping in your vault. To save time on those notes you can use the software MathPix, which lets you take a picture of an equation (even handwritten!) and transform it automatically into a LaTeX text. 

## Useful core plugins
- Audio recorder
- *Backlinks*
- Command palette
- File explorer
- File recovery
- Graph view
- Note composer
- Outgoing links
- Outline
- *Page preview*
- Quick switcher
- Random notes
- *Search*
- Slash commands
- Tag pane
- *Templates*

## Useful community plugins
- advanced tables
- calendar
- checklist
- clear unused images
- **custom frames** for Moodle, MOOCs, Notion, any resource you use often: it lets you access it from your Obsidian vault, and use it without the disctractions of a browser. 
- Discord Rich Presence (just for fun 😉) 
- emoji shortcodes 
- **extended mathJax** to create shortcuts for latex (`\newcommand`)
- **spaced repetition** to get reminded to reread each note on the right day for your memory
- **Tag wrangler** to rename and merge tags and improve the tag search 

## Ressources
- _Mathpix_ https://mathpix.com/
- Videos about the "second brain"/"Zettelkasten" note-taking method
	- _My Second Brain in Notion - Full Setup_ https://youtu.be/4bxpsvcW2mc
- Other videos about Obsidian
	- _Obsidian: The Most Secure Notion Alternative_ https://youtu.be/ms4cWMsOITs
	- _Top 10 Obsidian Plugins_ https://youtu.be/W7kTtn9empU