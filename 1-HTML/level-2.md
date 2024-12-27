<h1 align="center"> Basics of HTML  🚀</h1>

## Basic terminology
- **Tag** - A tag is a piece of text that is enclosed in angle brackets. It is used to define the structure of an HTML document.
- **Attribute** - An attribute is a piece of text that is placed inside the opening tag of an HTML element. It is used to provide additional information about the element.
- **Element** - An element is a piece of text that is enclosed in angle brackets and can have attributes. It is used to define the content of an HTML document.



> Example 1:

<code>&lt;p&gt; This is a paragraph&lt;/p&gt;</code>

<ul>
    <li><strong>Tag:</strong> <code>&lt;p&gt;</code> and <code>&lt;/p&gt;</code></li>
    <li><strong>Element:</strong> <code>&lt;p&gt; This is a paragraph&lt;/p&gt;</code> (this entire thing is an element)</li>
    <li><strong>Content:</strong> "This is a paragraph"</li>
</ul>

> Example 2:  

<code>&lt;img src="myimage.jpg" alt="A beautiful landscape" width="300"&gt;</code>

<ul>
    <li><strong>Tag:</strong> <code>&lt;img&gt;</code> and <code>&lt;/img&gt;</code></li>
    <li><strong>Element:</strong> <code>&lt;img src="myimage.jpg" alt="A beautiful landscape" width="300"&gt;</code></li>
    <li><strong>Attributes:</strong></li>
        <ul>
            <li><code>src="myimage.jpg"</code></li>
            <li><code>alt="A beautiful landscape"</code></li>
            <li><code>width="300"</code></li>
        </ul>
</ul>

## Some Frequently Used Tags 
- **Heading Tag** - Used to display headings in HTML
```
h1, h2, h3, h4, h5, h6 
```

- **Paragraph Tag** - Used to add paragraphs in HTML
``` 
<p> This is a sample paragraph </p> 
```

- **Anchor Tag** - Used to add links to your page
``` 
<a href="https://google.com"> Google </a>  
```

- **Image Tag** - Used to add images to your page
```
<img src="/image.png" alt="Random Image">
```

- **Br Tag** - Used to add next line(line breaks) to your page
```
<br>
```

- **Bold, Italic & Underline Tags** - Used to highlight text in your page
``` 
<b> Bold </b> 
```  
<b> Bold </b>

```
<i> Italic </i> 
``` 
<i> Italic </i>

```
<u> Underline </u> 
``` 
<u> Underline </u>

- **Big & Small Tags** - Used to display big & small text on your page
```
<big> Big </big>
``` 

```
<small> Small </small>
```

- **Hr Tag** - Used to display a horizontal ruler, used to separate content
``` 
<hr>
```

- **Subscript & Superscript Tag** - Used to display a horizontal ruler, used to separate content
```
<sub> subscript </sub>
H <sub> 2 </sub> O
```
OUTPUT: 
H <sub> 2 </sub> O

```
<sup> superscript </sup>
A <sup> n </sup> + B
```
OUTPUT: 
A <sup> n </sup> + B

- **Pre Tag**- Used to display text as it is (without ignoring spaces & next line)

``` 
<pre> This
is a sample
text.
</pre>
```
OUTPUT : 
<pre> This
is a sample
text.
</pre>


## Attributes examples

```
<p id="my-id" class="my-class">Hello world</p>
<img src="image.jpg" alt="Image">
<a href="https://www.google.com">Google</a>
<input type="text" placeholder="Enter your name">
<button>Click me</button> 
```

- ```id="my-id"``` - Adds an ```id``` attribute with the value my-id
- ```.my-class``` - Adds a ```class``` attribute with the value my-class
- ```src="image.jpg"``` - Adds a src attribute with the value image.jpg
- ```alt="Image"``` - Adds an alt attribute with the value Image
- ```href="https://www.google.com"``` - Adds a ```href``` attribute with the value https://www.google.com
- ```type="text"``` - Adds a ```type``` attribute with the value text
- ```placeholder="Enter your name"``` - Adds a ```placeholder``` attribute with the value Enter your name

Some attributes are global attributes and can be used on any HTML tag. Some attributes are specific to certain tags and can only be used with that tag. For example, the ```href``` attribute is a specific attribute for the ```<a>``` tag, and the ```title``` attribute is a global attribute that can be used on any HTML tag.

> We will be looking into attributes more in the next lesson.





