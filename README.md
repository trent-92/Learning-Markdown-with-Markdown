Learning-Markdown-with-Markdown
===============================

Introduction
------------

This is an attempt at summarizing Markdown syntax with Markdown. This is a summarized version of [Basics page in Daring Fireball][basics].

**Note:** This document is inspired by advice given in [Daring Fireball][main] :
> The best way to get a feel for Markdown’s formatting syntax is simply to look at a Markdown-formatted document.
> For example, you can view the Markdown source for the article text on this [page][main_markdown].

[basics]: https://daringfireball.net/projects/markdown/basics             "Markdown Basics"
[main]: https://daringfireball.net/projects/markdown/                     "Markdown Main"
[main_markdown]: https://daringfireball.net/projects/markdown/index.text  "Markdown Main in Markdown"

## Headers & Blockquotes & Emphasis

### First Level Header :

    Header    or    #Header
    ======
  
This equals

    <h1>Header</h1>
    
Example
=======
  
### Second Level Header :

    Header    or    ##Header
    ------
  
This equals

    <h2>Header</h2>
    
Example
-------

### Third Level Header :

    ###Header
  
This equals

    <h3>Header</h3>
    
### Example

### Blockquote

    > This is Syntax for blockquote.

This equals

    <blockquote>This is Syntax for blockquote.</blockquote>
    
> Blockquote
> Continues
  
### Phrase Emphasis

    *emphasized word*   or    _emphasized word_
  
This equals

    <em>emphasized word</em>
    
*emphasized*

### Strong Phrase Emphasis

    **Strong Emphasized Word**    or    __Strong Emphasized Word__
  
This equals

    <strong>Strong Emphasized Word</strong>
    
**Strong Emphasis**
    
## Lists

### Unordered List

    * Item1
    + Item2
    - Item3

This equals

    <ul>
    <li>Item1</li>
    <li>Item2</li>
    <li>Item3</li>
    </ul>
    
- This
- Is
- List

### Ordered List

    1. Item1
    2. Item2
    3. Item3
  
This equals

    <ol>
    <li>Item1</li>
    <li>Item2</li>
    <li>Item3</li>
    </ol>
    
1. Ordered
2. List
3. Listed

### Multi-paragraph List

    *   A List Item with
    
        Multiple Paragraphs
        
    *   Just another List Item

This equals

    <ul>
    <li><p> A List Item with</p>
    <p>Multiple Paragraphs</p></li>
    <li><p>Just another List Item</p></li>
    </ul>
    
*   A List Item

    That has Second Paragraph
    
*   Another Item

## Links & Images

### Inline Link

    [example](http://akaintelligence.com "Title")
    
This equals

    <a href="http://akaintelligence.com" title="Title">
    
[example](http://akaintelligence.com "Example")

### Reference Link

    [example][1]
    [1]: http://akaintelligence.com     "AKA Homepage"
    
This equals

    <a href="http://akaintelligence.com" title="AKA Homepage">
    
[example][1]
[1]: http://akaintelligence.com     "AKA Homepage"

### Image

    ![alt text](https://www.gstatic.com/images/branding/googlelogo/2x/googlelogo_color_284x96dp.png "Google Logo")
    
or

    ![alt text][id]
    
    [id]: https://www.gstatic.com/images/branding/googlelogo/2x/googlelogo_color_284x96dp.png "Google Logo"
    
This equals

    <img src="https://www.gstatic.com/images/branding/googlelogo/2x/googlelogo_color_284x96dp.png" alt="alt text" title="Google Logo" />
    
![something text](https://constellation.standup2cancer.org/assets/star-facbd92545e601590a94bd3fd813f643.png "Star")

### Code

    '<blink>' '&mdash;' '&#8212;'
    
This equals

    <code>&lt;blink&gt;</code> <code>&amp;mdash;</code> <code>&amp;#8212;</code>
    
'&mdash;'
