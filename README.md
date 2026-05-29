---

## Q1. What is HTML and what is the difference between HTML and HTML5?

HTML (HyperText Markup Language) is the standard language used to create and structure web pages. It helps define elements like headings, paragraphs, images, links, tables, and forms on a website.

The main difference between HTML and HTML5 is that HTML5 is the newer version with more advanced features. HTML5 supports multimedia elements like audio and video without needing extra plugins, includes new semantic tags such as `<header>`, `<section>`, and `<footer>`, and provides better support for modern web applications and responsive design.

---

## Q2. What are semantic HTML tags?

1. Semantic HTML tags clearly describe the meaning of content.
2. They improve readability for developers and browsers.
3. They help with SEO and accessibility.
4. They organize code better.

### Examples:
- `<header>` → Top section
- `<nav>` → Navigation links
- `<section>` → Content section
- `<article>` → Independent content
- `<aside>` → Side content
- `<footer>` → Bottom section

---

## Q3. Difference between `<div>` and `<span>` tags

- `<div>` is a block-level element. It starts on a new line and takes full width. Used for layout.
- `<span>` is an inline element. It does not start on a new line and takes only required space. Used for styling small text.

---

## Q4. Block-level vs Inline elements

### Block-level elements:
- Start on a new line  
- Take full width  
- Used for large sections  

**Examples:** `<div>`, `<p>`, `<h1>`

### Inline elements:
- Do not start on a new line  
- Take only required space  
- Used inside block elements  

**Examples:** `<span>`, `<a>`, `<strong>`

---

## Q5. Purpose of DOCTYPE in HTML

The DOCTYPE declaration tells the browser which version of HTML is used.

### It helps:
- Render page correctly  
- Avoid quirks mode  
- Follow modern rules  

### HTML5 DOCTYPE:
```html
<!DOCTYPE html>

Q6. Difference between id and class
id:
Unique per page
Used once
class:
Can be used multiple times
Used for grouping

Q7. HTML Form
<form>
  <input type="text" placeholder="Enter your name">
  <input type="email" placeholder="Enter your email">
  <button type="submit">Submit</button>
</form>

Q8. Meta tags

Meta tags provide information about the page.

<meta name="description" content="HTML tutorial">

Used for SEO and browser instructions.


Q9. alt attribute in image
<img src="image.jpg" alt="A boy playing football">
Shows text if image fails
Helps screen readers
Improves SEO

Q10. Clickable image
<a href="https://example.com">
  <img src="image.jpg" alt="Click me">
</a>

Q11. Image formats
JPG → Small size, photos, no transparency
PNG → High quality, supports transparency
SVG → Vector, scalable
WebP → Modern, small size + quality

Q12. Semantic tags in HTML5

Examples:
<header> <footer> <section> <article>

Improve structure and readability.


Q13. script, async, defer
script → blocks HTML loading
async → runs when ready (no order)
defer → runs after HTML loads (order maintained)

Q14. Audio & Video
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
</audio>

<video controls width="300">
  <source src="video.mp4" type="video/mp4">
</video>

Q15. Relative vs Absolute path
Relative → local file (images/pic.jpg)
Absolute → full URL (https://example.com/image.jpg)
Q16. data-* attributes
<div data-user-id="101"></div>

Used to store extra data.

Q17. Viewport meta tag
<meta name="viewport" content="width=device-width, initial-scale=1.0">

Makes website responsive.

Q18. SEO in HTML
Proper headings
Title tag
Meta description
Semantic tags
Alt text

Q19. Accessibility best practices
Semantic tags
Alt text
Form labels
Proper headings
Good contrast

Q20. strong vs b, em vs i
strong → important text
b → just bold
em → emphasized text
i → italic only