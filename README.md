# HTML Basics

## 📌 About

This project is a quick reference guide to basic HTML elements, structure, attributes, and semantic tags. It’s designed to help beginners write clean, accessible, and SEO-friendly HTML.

---

## 🧱 HTML Overview

* **HTML**: HyperText Markup Language
* Not a programming language — it’s a markup language for structuring content on the web.

## <!DOCTYPE>

* Declares the HTML version to the browser.
* Ensures the page is rendered in standards mode.

## 🏷️ Types of Tags

* **Open/Close tag**: `<p>content</p>`
* **Self-closing tag**: `<input />`

## 🌲 Document Tree

* `<head>`: Contains metadata to help with SEO.

  * `<meta>`: Describes page content.
* `<body>`: Contains visible content.

## 💬 Comments

* Syntax: `<!-- comment -->`
* Used to describe code for collaboration.

## 🔠 Headings

* Only one `<h1>` per page for SEO optimization.

## 🌍 Global Attributes

* Examples: `class`, `id`, `hidden`, `title`

## 🎯 Specific Attributes

* Examples: `src`, `alt`, `href`, `type`

## ✍️ Text Formatting

* **Bold**

  * `<b>`: Bold text
  * `<strong>`: Bold and important
* **Italic**

  * `<i>`: Italic text
  * `<em>`: Emphasized text
* **Other Tags**

  * `<mark>`: Highlighted
  * `<u>`: Underlined
  * `<small>`: Smaller text
  * `<del>`: Strikethrough (for SEO relevance)
  * `<sub>`: Subscript (e.g., H<sub>2</sub>O)
  * `<sup>`: Superscript (e.g., 2<sup>2</sup>)

## 🔗 Anchor Tag

* Used for linking pages, sections (by ID), or social media.
* `target="_blank"`: Opens link in new tab

## 🖼️ Images

* `src`: Source (relative or absolute path)
* `alt`: Alternative text for SEO and fallback

## 📋 Lists

* **Unordered**: `<ul>` with `<li>`
* **Ordered**: `<ol>` with `<li>`

  * `type`, `start` attributes for numbering style
* **Description List**: `<dl>`, `<dt>`, `<dd>`

## 📊 Tables

* `<table>` structure with:

  * `<caption>`: Title
  * `<thead>`, `<tbody>`, `<tfoot>`
  * `<tr>`, `<th>`, `<td>`
  * `colspan`: Merges cells across columns

## 📌 Inline & Block Elements

* `<span>`: Inline
* `<br>`: Line break
* `<hr>`: Horizontal line (block)
* `<div>`: Block-level container

## 🔡 HTML Entities

* Syntax: `&entity;` (e.g., `&lt;`, `&amp;`)

## 🆕 HTML5 Semantic Tags

* Elements: `header`, `nav`, `section`, `aside`, `main`, `article`, `footer`
* Purpose: Clean structure + better SEO

## 🎞️ Multimedia

* **Video**: `<video>` + `<source>`

  * Attributes: `controls`, `muted`, `autoplay`, `loop`, `poster`
  * `<track>`: Add captions or translations
* **Audio**: `<audio>` + `<source>`

## 📝 Input

* Inline, self-closing
* `type` (e.g., `text`, `url`, `date`), `value`, `name`, `placeholder`, `required`, `autofocus`
* `readonly`: Sent in request
* `disabled`: Not sent

## 📮 Forms

* `action`: Destination URL
* `method`: `GET` (data in URL) or `POST` (hidden, more secure)

* what is default mode for rendering html page?
 standard and quirks mode

---------


- **Question**: What are ARIA roles, and how do you use them to improve accessibility?
- **Answer**: ARIA (Accessible Rich Internet Applications) roles provide additional semantic information to assistive technologies. For example, `role="button"` can make a div element behave like a button to screen readers. They are used to improve the accessibility of dynamic content


- **Question**: What are data attributes in HTML and how do you use them?
- **Answer**: Data attributes are custom attributes prefixed with `data-`, used to store extra information on HTML elements without using global attributes or JS variables. Example:

----------

what's geolocation?
API lets you share your location with your favorite websites. A JavaScript can capture your latitude and longitude 

------

What are the graphics elements in html5?/ SVG vs Canvas?

----

What Are Web Workers in HTML5?
Web Workers are a feature in HTML5 that allow you to run JavaScript code in the background, separately from the main thread (the UI thread).
This means heavy tasks can run without freezing or slowing down the user interface.

---

What is HTML5 Web Storage?
HTML5 Web Storage is a feature that allows websites to store data in the browser, more efficiently and securely than traditional cookies.

7	What is Server Side Events in HTML5?

---

8	What are web sockets?

---

11	how to support old browsers with svg?

---

What Is Browser Optimization?
Browser optimization means making your website or web application load faster, run smoother, and use less memory or CPU when viewed in a web browser.

---


Why is it generally a good idea to position CSS <link>s between <head></head> and JS <script>s just before </body>? Do you know any exceptions?

✅ Why Place <link> (CSS) in <head> and <script> (JS) before </body>?
🔷 CSS <link> in <head>:
Reason: The browser needs to load and apply styles before rendering the page.

If you delay loading CSS, users might see an unstyled page briefly (FOUC – Flash of Unstyled Content).

Placing it in <head> ensures smooth, styled loading.

🔷 JS <script> before </body>:
Reason: JavaScript can block HTML parsing.

Putting scripts at the end allows the HTML to load first, making the page appear faster to the user.


----------

why html is hyper?

The term "hyper" means beyond or non-linear.

Unlike traditional text (like in books, which you read line by line, page by page), hypertext lets you:

Jump from one page to another using hyperlinks

Navigate across different parts of the web

Move beyond the limits of sequential reading


----------


what type of elements in html ? 
  structure element => html body head section artical ....
  text element => h1 to h6, p, div, span ....
  Media Elements => video , audio, convas ...
  lists => ol ul 
  tables => table tbody thead ....
  Forms => form input label .....

---------

What is the meta Tag that make media query work ?


-------

how browser understand the html tags?

-----

what is the tag that hasn’t any  data appear in browser window , and what is contain?

--------

tell me 5 uses of anchor link ?

--------

How can I run java script code through <a> tag?
  excute a function at onClick
  write javascript in href


-------

can I use negative number in row or column span ?  
 No

--------

if ID is not unique what is issues will happen in html , CSS and JS?

-----


what are 3 ways used for rendering java script ?
  inline => onClick
  internal => <script></script>
  external => file.js

------

what difference between no script and script?

-----

what different types of linking resources ?
  script, link, image, a

------

Define Image Map?

------

what is names of shapes used in image map?

-------

how can I upload image from type image only?
<input type="file" accept="image/*">

-------

why we can use input with hidden type ?  


-----

why name and value are important in any element input ?
