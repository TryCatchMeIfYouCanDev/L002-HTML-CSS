# SECOND LESSON - HTML & CSS Fundamentals #

## HTML and CSS Roles ##

### HTML ###

* HTML structures a web page, indicating the role of each element.
* All visible content goes inside the `<body>` of the document.
* It is important to organise content into appropriate containers rather than placing it randomly.

### CSS ###

* CSS stylesheets control the **visual appearance** of a page.
* HTML (structure) and CSS (presentation) should remain separate.

## Containers and Semantic Tags ##

### Generic vs Semantic Containers ###

* `<div>`: generic container, provides no semantic meaning.
* Semantic tags (introduced in HTML5) describe the **purpose of content**:

  * `<header>`
  * `<footer>`
  * `<nav>`
  * `<main>`
  * `<section>`
  * `<article>`
  * `<aside>`

### Metaphor for `<div>` ###

* `<div>` is like a moving box without labels.
* Semantic containers label the boxes, giving structure and meaning.

### Example Semantic Layout ###

```html
<header><i><b>This is the Header</b></i></header>
<aside id="sidebarLeft">Left Column</aside>
<article>This is the Article</article>
<aside id="sidebarRight">Right Column</aside>
<footer>This is the Footer</footer>
```

## Global Attributes ##

### ID ###

* Uniquely identifies an element in the document.
* Rules:

  * Unique value
  * Case-sensitive
  * No spaces
  * Cannot start with a number

### Title ###

* Provides additional information, often displayed as a **tooltip**.
* Useful for clickable elements like links.

## HTML Lists ##

### Unordered Lists `<ul>` ###

* Lists elements without a specific order.
* Marker types can be defined with `type` attribute: "disc", "circle", "square".

### Ordered Lists `<ol>` ###

* Lists elements in a specific order.
* `type` attribute can define numbering style: "1", "a", "A", "i", "I".

### List Items `<li>` ###

* Represents each entry in a list.
* Lists can be **nested** to create sub-lists.

### Example Nested Lists ###

```html
<ol type="i">
  <li>Alessandro
    <ul>
      <li>Rome</li>
      <li>06554433</li>
      <li>info@alessandro.it</li>
      <li>Sports
        <ol>
          <li>Tennis</li>
          <li>Football</li>
          <li>Basketball</li>
        </ol>
      </li>
    </ul>
  </li>
  <li>Andrea</li>
  <li>Carlo</li>
</ol>
```

## Tag Types ##

### Block Elements ###

* Occupy the full width and create a line break after closing.
* Examples: `<div>`, `<h1>`.

### Inline Elements ###

* Flow horizontally, do not break the line.
* Examples: `<a>`, `<span>`, `<strong>`.

## Text Formatting Tags ##

### Physical vs Logical ###

* `<b>`: bold (physical)
* `<i>`: italic (physical)
* `<strong>`: bold (semantic/logical, improves screen reader interpretation)
* `<em>`: italic (semantic/logical, emphasises content for accessibility)

## Comments ##

* Syntax:

```html
<!-- This is a comment -->
```

* Used to leave notes for colleagues or clients, or to temporarily disable code.

## DOCTYPE and Validation ###

* `<!DOCTYPE html>`: defines the document type and enables HTML5.
* Example for XHTML 1.0 Transitional:

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "https://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```

* Ensures proper document structure for validators.

## Accessibility ##

* European Accessibility Act (June 28, 2025)
* Italian law: Legge Stanca
* Goals: readable content, simple navigation, forms usable by assistive technology.
* Semantic tags, proper headings, `<strong>` and `<em>` help screen readers.
* WCAG guidelines: [W3C Web Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/)

## Usability and Web Design ##

* Experts:

  * Jakob Nielsen: [NNGroup](https://www.nngroup.com/people/jakob-nielsen/)
  * Steve Krug: “Don’t Make Me Think” ([Sensible.com](https://sensible.com/))
* Principles: navigation must be **intuitive and self-explanatory**.

## Design Tools ##

* Adobe XD: [Get started with Adobe XD](https://www.adobe.com/products/xd.html)
* Figma: [https://www.figma.com/](https://www.figma.com/)
* Balsamiq Mockups: [https://balsamiq.com/wireframes/](https://balsamiq.com/wireframes/)
* Approaches:

  * Desktop First → media queries → mobile
  * Mobile First → modern standard
  * Content First → emphasise important content

## Paragraphs and Placeholder Text ##

* `<p>`: paragraph
* Placeholder: **Lorem Ipsum** ([https://www.lipsum.com/](https://www.lipsum.com/))
* Line break: `<br/>`
* Non-breaking space: `&nbsp;`
* Special characters:

```html
< → &lt;
> → &gt;
" → &quot; or &#34;
```



## Useful Links ##
1. https://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd
2. https://www.nngroup.com/people/jakob-nielsen/
3. https://www.nngroup.com/articles/top-10-mistakes-web-design/
4. https://sensible.com/
5. https://www.amazon.de/dp/0321965515/
6. https://www.flaticon.com/
7. https://helpx.adobe.com/xd/get-started.html
8. https://www.figma.com/de-de/
9. https://balsamiq.com/product/
10. https://www.lukew.com/about/
11. https://en.wikipedia.org/wiki/De_finibus_bonorum_et_malorum
12. https://lipsum.com/
13. https://corsidia.com/materia/web-design/caratterispecialihtml
14. https://www.w3schools.com/html/html_lists.asp
15. https://www.w3.org/WAI/
16. https://www.w3.org/International/i18n-drafts/nav/about
17. https://www.w3.org/mission/security/
18. https://www.w3.org/mission/privacy/
19. https://www.w3.org/ecosystems/automotive-transportation/
20. https://www.w3.org/ecosystems/media/
21. https://www.w3.org/ecosystems/publishing/
22. https://www.w3.org/ecosystems/e-commerce/
23. https://www.w3.org/2013/data/
24. https://www.w3.org/ecosystems/network-communications/
25. https://www.w3.org/WoT/
