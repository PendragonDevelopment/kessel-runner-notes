# Intro to HTML and CSS

## What is HTML and CSS

- HTML: HyperText Markup Language
- CSS: Cascading Style Sheets
- HTML and CSS are two of three front end languages
- Front end languages (client-side) is what web browsers use to translate requests and responses to the back end languages (server-side)
- Front end languages maintain a separation of concerns:
  - HTML: Structure
  - CSS: Presentation
  - JavaScript: Interaction
- Standards organization: W3C (WorldWide Web Consortium)
- JavaScript maintained by ECMA (European Computer Manufacturers Association)
- Standards organizations maintain a vendor neutral implementation for each language
- HTML developed by Tim Berners-Lee at CERN in the late 80's/early 90's (first documented in 1991)
- CSS developed by Håkon Wium Lie in 1994 (officially adopted in 1996)
- HTML was developed to structure and connect documents on the web
- CSS was developed to style markup documents from various sources and with cascading rules

```html
<p>This is a paragraph.</p>
<p class="big">This is a larger paragraph.</p>
```

```css
p {
  color: black;
}
p.big {
  size: 14px;
}
```
- HTML is made up of elements that describe the structure and content of a document (usually a web page)
- `<p>`, `<a>`, `<ul>` are all examples of HTML elements/tags
- Block level elements: used as wrappers to partition content that logically belongs together in a document
  - `<header>`, `<section>`, `<footer>`, `<div>`, `<p>`
- Inline elements describe the type of content that is wraps
  - `<a>`, `<span>`, `<img>`
- The "block-level" category roughly corresponds to the category of flow content in HTML5, while "inline" corresponds to phrasing content