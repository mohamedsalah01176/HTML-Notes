HTML  
  - HyperText Markup Language  
  - It is not a programming language; it is a markup language.  

<!DOCTYPE>  
  - We use it to tell the browser the version of HTML.  
  - It helps render the page in standard mode.  

Types of Tags  
  - Open/Close tag: <p>content</p>  
  - Self-closing tag: <input>  

Document Tree  
  - <head></head>  
    -- Used to add page details to improve SEO.  
    -- <meta>: Describes the page's data.  
  - <body></body>  

Comments  
  - <!-- comment -->  
  - Used to describe the code for the team.  

<h1>  
  - The page should contain only one <h1> to improve SEO.  

Global Attributes  
  - class, hidden, id, title, etc.  

Specific Attributes  
  - src, alt, href, type, etc.  

Formatting Text  
  - Bold  
    -- <b> => bold  
    -- <strong> => bold and important  
  - Italic  
    -- <i> => italic  
    -- <em> => italic with emphasis  
  - Highlighted text  
    -- <mark>  
  - Underline  
    -- <u>  
  - Smaller text  
    -- <small>  
  - Strikethrough  
    -- <del> => helpful for SEO  
  - Subscript  
    -- <sub>H2O</sub>  
  - Superscript  
    -- <sup>2</sup> (e.g. 2²)  

Anchor Tag  
  - Used to navigate between pages, sections (by ID), or social media.  
  - Inline element.  
  - target attribute:  
    -- _blank => opens the link in a new tab  

Images  
  - src  
    -- Relative path  
    -- Absolute path  
  - alt (alternative text)  
    -- Appears if the image is not found and helps SEO  

Lists  
  - Unordered List  
    -- <ul> => <li>  
    -- Displays bullets  
    -- Can nest <ul> inside another  
  - Ordered List  
    -- <ol> => <li>  
    -- type attribute => numbers, letters, etc.  
    -- start attribute => custom starting number  
  - Description List  
    -- <dl> => <dt> (term) => <dd> (description)  

Table  
  - <table>  
    -- <caption> => Table title  
    -- <thead> => <tr> => <th>, <td>  
    -- <tbody> => <tr> => <td>  
    -- <tfoot> => <tr> => <td>  
    -- colspan => merge columns  

<span>  
  - Inline element  

<br>  
  - Breaks to a new line  

<hr>  
  - Horizontal line  
  - Block element  

<div>  
  - Used as a container  
  - Block element  

HTML Entities  
  - Example: &lt;, &gt;, &amp;, &nbsp;  

HTML5  
  - Semantic Elements  
    -- header, nav, section, aside, main, article, footer  
    -- Makes code clean and improves SEO  
    -- Block elements  
  - Video  
    -- <source>  
    -- Attributes: controls, muted, autoplay, loop, poster  
    -- <track>: for captions or subtitles  
  - Audio  
    -- <source>  

Input  
  - Inline element  
  - Self-closing tag  
  - type => search, url, date, etc.  
  - Common attributes: value, name, required, placeholder, autofocus  
  - readonly => included in the request  
  - disabled => not included in the request  

Form  
  - action attribute: where to send the data  
  - method:  
    -- GET => sends data in the URL  
    -- POST => more secure because data is hidden
