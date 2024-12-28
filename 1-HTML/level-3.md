<h1 align="center">  Understanding HTML Structure: Semantic Tags and Basic Layout 🚀</h1>

## Page Layout Techniques

> using Semantic tags for layout
using the Right Tags

```
<header>
<main>
<footer>
```

- ```Semantics``` in coding defines the intended behavior of a program or code snippet.
- It focuses on what the code is supposed to do, rather than just how it's written.
- Violations of semantics lead to incorrect or unexpected results, even if the code is syntactically correct.

## Inside Main Tag

> To illustrate the potential contents of the ```<main>``` tag

- Section Tag - For a section on your page
<section>
```
- Article Tag - For an article on your page
```
<article>
```
- Aside Tag - For content aside main content(ads)
```
<aside>
```

## Revisiting Anchor Tag
- Here, ``` target="_main" ``` is used for ```new tab```
```
<a href="https://google.com" target="_main"> Google </a>
```

- Here, ``` <img src="link"> ``` is used for ```clickable pic ```
```
<a href="https://google.com"> <img src="link"> </a>
```

## Revisiting Image Tag
- Here, ```height=50px``` is used for ``` set height ```
```
<img src="link" height=50px >
``` 
- Here, ```width=50px``` is used for ```set width```
``` 
<img src="link" width=50px >
```
 
## Div Tag
- ```Div``` is a container used for other HTML elements
- ```Block Element``` (takes full width)

## List : Div Tags
- ```<address>``` : Provides contact information for the author/owner of the document or part of it.
- ```<article>``` : Defines a self-contained, independent, and potentially reusable piece of content.
- ```<aside>``` : Contains content that is tangentially related to the surrounding content (e.g., a sidebar).
- ```<blockquote>``` : Indicates a long quotation.
- ```<canvas>``` : Used to draw graphics on a web page via JavaScript.
- ```<dd>``` : Defines a description/value for a term defined in a ```<dt>``` element.
- ```<div>``` : A generic container for grouping and styling blocks of content.
- ```<dl>``` : Defines a description list (list of terms and their descriptions).
- ```<dt>``` : Defines a term/name in a description list.
- ```<fieldset>``` : Groups related elements in a form.
- ```<figcaption>``` : Provides a caption for a ```<figure>``` element.
- ```<figure>``` : Groups media content and its caption together.
- ```<footer>``` : Defines a footer for a document or section.
- ```<form>``` : Used to create an HTML form for user input.
- ```<h1> - <h6>``` : Defines headings for sections of a page, with ```<h1>``` being the largest and ```<h6>``` the - smallest.
- ```<header>``` : Defines a header for a document or section.
- ```<hr>``` : Defines a thematic break between paragraph-level content.
- ```<li>``` : Defines a list item in an ordered or unordered list.
- ```<main>``` : Represents the main content of a document.
- ```<nav>``` : Contains navigation links.
- ```<noscript>``` : Defines content that will be displayed if JavaScript is not supported.
- ```<ol>``` : Defines an ordered list.
- ```<p>``` : Defines a paragraph of text.
- ```<pre>``` : Displays text with preserved spaces and line breaks.
- ```<section>``` : Defines a section in a document.
- ```<table>``` : Defines a table for tabular data.
- ```<tfoot>``` : Defines a footer for a table.
- ```<ul>``` : Defines an unordered list.
- ```<video>``` : Used to embed a video in a web page.

## Span Tag
- ```Span``` is also a container used for other HTML elements
- ```Inline Element``` (takes width as per size)

## List : Span Tags
- ``` <a>``` : Defines a hyperlink.
- ``` <abbr>``` : Defines an abbreviation.
- ``` <acronym>``` : Defines an acronym (deprecated in HTML5).
- ``` <b>``` : Defines bold text.
- ``` <bdo>``` : Defines the text direction (deprecated in HTML5).
- ``` <big>``` : Defines larger text (deprecated in HTML5).
- ``` <br>``` : Inserts a single line break.
- ``` <button>``` : Defines a clickable button.
- ``` <cite>``` : Defines the title of a work (e.g., a book, a song, a movie, a TV show, a poem, a painting, a - sculpture, etc.).
- ``` <code>``` : Defines a piece of computer code.
- ``` <dfn>``` : Defines a term and its meaning.
- ``` <em>``` : Defines emphasized text.
- ``` <i>``` : Defines italic text.
- ``` <img>``` : Defines an image.
- ``` <input>``` : Defines an input control for user input.
- ``` <kbd>``` : Defines keyboard input.
- ``` <label>``` : Defines a label for an ```<input>``` element.
- ``` <map>``` : Defines an image map (clickable areas within an image).
- ``` <object>``` : Defines a container for external content (e.g., an image, a video, a Java applet).
- ``` <tt>``` : Defines teletype text (deprecated in HTML5).
- ``` <var>``` : Defines a variable.
- ``` <output>``` : Defines the result of a calculation.
- ``` <q>``` : Defines a short quotation.
- ``` <samp>``` : Defines sample output from a computer program.
- ``` <script>``` : Defines a client-side script (e.g., JavaScript).
- ``` <select>``` : Defines a drop-down list.
- ``` <small>``` : Defines smaller text.
- ``` <span>``` : Defines an inline container for grouping and styling inline elements.
- ``` <strong>``` : Defines important text.
- ``` <sub>``` : Defines subscript text.
- ``` <sup>``` : Defines superscript text.
- ``` <textarea>``` : Defines a multi-line text input control.
- ``` <time>``` : Defines a time/date