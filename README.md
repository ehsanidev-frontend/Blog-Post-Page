# Blog Post Page

A semantic HTML blog post page built as part of the [roadmap.sh](https://roadmap.sh/projects/blog-post-page) frontend projects.

## Project URL

https://roadmap.sh/projects/blog-post-page

## Overview

This project is a single blog post page that demonstrates the use of **semantic HTML** to create accessible, SEO-friendly, and maintainable markup. The page includes a site header, navigation, a full blog article, a blockquote, code samples, and a footer.

## Features

- Semantic HTML5 structure (`<header>`, `<nav>`, `<main>`, `<article>`, `<figure>`, `<footer>`)
- Accessible navigation with `<nav>` and `<ul>`
- Proper heading hierarchy (`<h1>` → `<h2>`)
- Article with author and date metadata
- Figure with image and caption (`<figure>` + `<figcaption>`)
- Blockquote with citation (`<blockquote>` + `<cite>`)
- Inline code and code block samples (`<code>` + `<pre>`)
- SEO-friendly meta tags (charset, viewport, description)

## File Structure

```
.
├── post.html
├── README.md
└── images/
    └── mountains-at-sunrise.jpeg
```

## Semantic Elements Used

| Element         | Purpose                                              |
| --------------- | ---------------------------------------------------- |
| `<header>`      | Site header containing title and navigation          |
| `<nav>`         | Main navigation menu                                 |
| `<main>`        | Main content area of the page                        |
| `<article>`     | Self-contained blog post content                     |
| `<figure>`      | Image with its caption                               |
| `<figcaption>`  | Caption for the figure                               |
| `<blockquote>`  | Quoted content from an external source               |
| `<cite>`        | Source of the quote                                  |
| `<code>`        | Inline code snippet                                  |
| `<pre>`         | Preformatted code block                              |
| `<footer>`      | Site footer with copyright                           |

## Best Practices Followed

- One `<h1>` per page for the main article title
- Descriptive `alt` text for images
- Logical heading order (no skipped levels)
- Content grouped inside meaningful landmarks
- External links with descriptive link text

## Areas for Improvement

The following improvements can be applied to make the markup even more semantic:

1. **Replace `<u>` with `<strong>` or `<em>`** — `<u>` is for visual underline only and carries no semantic emphasis. Use `<strong>` for strong importance and `<em>` for stress emphasis.
2. **Replace decorative `<span>` with `<p>`** — `<span>` is an inline, non-semantic element. Introductory sentences before lists or code blocks should use `<p>`.
3. **Avoid `<br />` for paragraph breaks** — Each paragraph should be wrapped in its own `<p>` element.
4. **Fix incomplete link** — `href="http://"` should point to the real HTML Living Standard URL: `https://html.spec.whatwg.org/`.
5. **Consider moving `<blockquote>` inside `<article>`** — If the quote is part of the article, it should live inside it.
6. **Clean up `<pre>` indentation** — Extra whitespace inside `<pre>` is rendered literally.

## How to Run

1. Clone or download the project.
2. Open `post.html` directly in any modern web browser.
3. No build step or dependencies required.

## Resources

- [roadmap.sh Blog Post Page Project](https://roadmap.sh/projects/blog-post-page)
- [MDN: HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [HTML Living Standard](https://html.spec.whatwg.org/)
- [MDN: Block-level elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements)
- [MDN: Inline elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements)

## License

This project is for educational purposes as part of the roadmap.sh curriculum.