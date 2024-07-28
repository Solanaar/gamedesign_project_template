> [!WARNING] WIP
# Naming

## Folders
Folders have no capitalized letters and no spaces. Words are separated with underscores ( _ )

## Files
### Game project
### Documentation
For the sake of readability and to benefit from the useful note-linking-feature of Obsidian (_see: [[Using Obsidian]]_) file names can contain spaces. The first word should usually be capitalized, however, exceptions apply (i.e. code references). Words are separated via space.

## Dates
Except when used inline, i.e. mentioning a specific date, when game was released, dates should be written as such YYYY-MM-DD, to allow for easy sorting and searching (especially when using queries).


# Formatting 

## Shortcuts
Shortcuts are all upper-case and surrounded by backticks like this: `CTRL+Z` 

## **Bold** and *Italics*

## Indentations
Indentations can be made by pressing [Tab]. Or by adding a > at the beginning of the line. If there is any break, to continue this indentation, you need to add another >.

Indentations are used when... 

## Lists
### Numbered lists

## Single [Brackets]
Mark questions that should be answered before the note is finished. For example, if a question about a certain feature came up in a meeting, it can be directly referenced inside that features note via [Is this feature necessary and why?].

## Referencing with @

## Headings

## Breaks and Separators
### Line breaks and paragraph breaks
>A line break is a break without any space.
>Like this. It will continue directly on the next line.

>A paragraph break is a break with one space between each line.
>
>Like this. 
### Separators
This is a separator:

---


# Improving the workflow
For people like me, who (1) try to do everything perfect from the beginning, (2) try to plan for every eventuality to mitigate reworking, but also (3) are insanely chaotic and unstructured and (4) forget their structures easily and (5) develop new structures every time they come back to a project, *it is paramount* to remember these general paradigms:
1. A strong foundation leads to easy innovation
2. Start simple
3. Try to not calculate for every eventuality
4. Try instead to calculate for expandability
5. Readability (always expect that when you'll come back you have no memory of any thought processes that went into the structure).
	1. Try to explain every decision as clearly and completely as possible
	2. It can help to think like this will be used by random people that you don't know and can't explain anything to afterwards


# Duplicate note names
>**Rule:** When there are more than one note with the same name that are distinct in a meaningful way (i.e. a person's name also being a name for a location), create 2 notes. Denote the primary type (i.e. "location") in the note name. Add an alias without the type. Add this line and link to the other notes.
>*This article is about the [type]. For other uses, see [[link to other article]].*

>**Syntax** : [Note_Name-Note_Type]

*As a rule of thumb, you do not want special characters besides dash and underscore within your file names. The fact that Obsidian allows it, has long been the bane of plugin developers.*

# On preventing note redundancy
As mentioned in [Duplicate note names], distinct notes with the same name should be separated. This also applies for different aspects of one thing.

Be careful though, as this is a fine, blurred line. Take your time when deciding when to consolidate and when to split notes.

This thought process also applies to categories and tags.


# Linking
It would be more beautiful if only the first instance of every note is linked inside a text.

This becomes a problem when you'll inevitably restructure a note. Now you need to re-organize all the links.

Also using the "outgoing link" feature becomes more time consuming and more prone to error since you now need to ignore every other instance of an already existing link.

So until there is a way to automate linking outgoing links, for the sake of making it easy and fast:

> **Rule**: Every instance of a potential link inside a note will be linked.