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
