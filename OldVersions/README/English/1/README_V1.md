
***

![/MediaWiki_Sunflower.png](/MediaWiki_Sunflower.png)

### Learning WikiText

I am pretty inexperienced with WikiText at the moment, but I still have more to learn. This document will go over my current knowledge of the WikiText markup language.

This document uses version 1.3.11 of the Wikimedia Wikitext markup specification for the WikiText markup language.

#### Comments in WikiText

Comments in WikiText are the same as most other markup languages (such as XML, HTML, etc.) they are written like this:

```wikitext
<!-- This is a comment !-->
<!-- The same syntax for single-line
comments is also used in block comments.
!-->
```

#### Break keyword in WikiText

WikiText does not support the break statement/keyword, it has no need for it.

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

#### Headings in WikiText

Headings in WikiText work like so:

# Heading 1

It is advised to skip heading 1, as it is the same level of the page name.

## Heading 2

```wikitext
== Heading level 2 ==
```

### Heading 3

```wikitext
=== Heading level 3 ===
```

### Heading 4

```wikitext
==== Heading level 4 ====
```

### Heading 5

```wikitext
===== Heading level 5 =====
```

### Heading 6

```wikitext
====== Heading level 6 ======
```

Just like HTML and other document standards, a 7th heading level does not exist. Attempting to do so will result in plain unformatted text, rather than a heading

####### Heading 7 (non-existant)

```wikitext
======= Heading 7 (non-existant) =======
```

#### Table of contents

A document with 4 or more headings will automatically render with a table of contents unless it is defined by the magic word `__NOTOC__`

```wikitext
__NOTOC__

=== Etymology ===

Lorem Ipsum

=== History ===

Warfare, invasions, Caesar, expansion, conquest.

=== Fall ===

Fall of the Western Roman Empire.

=== Middle ages ===

Holy Roman Empire

=== Fall 2 ===

Fall of the Holy Roman Empire
```

Without it, a table of contents is automatically generated:

```wikitext
=== Etymology ===

Lorem Ipsum

=== History ===

Warfare, invasions, Caesar, expansion, conquest.

=== Fall ===

Fall of the Western Roman Empire.

=== Middle ages ===

Holy Roman Empire

=== Fall 2 ===

Fall of the Holy Roman Empire
```

#### Lists in WikiText

Lists can be formed in WikiText in multiple ways. The following examples showcase bullet lists.

##### Bullet list

```wikitext
* Start
* Each
* Bullet
* List
* Entry
* With
* An
* Asterisk
```

#### Bold in WikiText

Text can be bolded in WikiText by doing the following:

```wikitext
This text is not bold

'''This text is bold'''
```

#### Italics in WikiText

Text can be italicized in WikiText by doing the following:

```wikitext
This text is not italicized

''This text is italicized''
```

#### Code blocks in WikiText

A code block can be formed in WikiText by doing the following:

```wikitext
<syntaxhighlight lang="python">
print("Hello, WIkiText")
</syntaxhighlight>
```

##### Images in WikiText

Referencing an image in WikiText is very easy, and is done like so:

```wikitext
[[File:filename.extension|options|caption]]

[[File:Example.svg|options|A good example image]]
```

#### Horizontal Lines in WikiText

Horizontal Lines/divider lines are supported in WikiText. They can be defined like so:

```wikitext

***

== Section 1 ==

---

== Section 2 ==

***

```

#### Hyperlinks in WikiText

Hyperlinks are supported in WikiText. They can be defined like so:

```wikitext
https://wikipedia.org/
```

You must fill every entry in the table, or it won't render.

#### Infoboxes in WikiText

I am still trying to figure out how to make a functional infobox for Wikipedia. This is as close as I can currently get:

```wikitext
<code><nowiki>{{</nowiki>[[User:UBX/Programmer]]<nowiki>}}</nowiki></code>
```

_/!\ This example has not been tested yet, and may not work_

#### Videos in WikiText

I don't know how to embed videos in WikiText yet, as I never tried.

#### Audio in WikiText

I don't know how to embed audio files/clips in WikiText yet, as I never tried.

#### Source

The majority of my WikiText knowledge comes from experimenting, viewing Wikipedia page source code, and reading Wikimedia documentation on the MediaWiki specification page and Wikipedia.

Notable resources:

[SeansLifeArchive/Extras/Wikipedia](https://github.com/seanpm2001/SeansLifeArchive_Extras_Wikipedia/)

[Help:Formatting - MediaWiki](https://www.mediawiki.org/wiki/Help:Formatting/)

[Wikipedia (English)](https://en.wikipedia.org/wiki/)

#### Other knowledge of WikiText

1. WikiText is not a curly bracket language, and also does not use semicolons at the end of each line

2. WikiText is a lighweight markup language

3. WikiText is most widely used for documentation, notably Wikipedia articles, and articles on WikiMedia sister projects,.

4. WikiText uses the `*.wiki` file extension

5. WikiText is a language recognized by GitHub, but you have to use a `.gitattributes` file to recognize it in the GitHub Linguist

6. WikiText is a markup language

7. WikiText is owned by MediaWiki, which is not to be confused with WikiMedia.

8. I am using the old sunflower MediaWiki logo, as I prefer it over the 2020 April 1st logo

9. No other knowledge of WikiText at the moment.

***

**File version:** `1 (2022, Monday, April 18th at 1:17 pm PST)`

***
