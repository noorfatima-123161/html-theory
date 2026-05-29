## Q1.What is HTML and what is the difference between HTML and HTML5?

HTML (HyperText Markup Language) is the standard language used to create and structure web pages. It helps define elements like headings, paragraphs, images, links, tables, and forms on a website.

The main difference between HTML and HTML5 is that HTML5 is the newer version with more advanced features. HTML5 supports multimedia elements like audio and video without needing extra plugins, includes new semantic tags such as `<header>`, `<section>`, and `<footer>`, and provides better support for modern web applications and responsive design.

---

## Q2.What are semantic HTML tags?

1. Semantic HTML tags are tags that clearly describe the purpose and meaning of the content they contain.

2. They make the structure of a webpage easier to understand for developers and browsers.

3. Semantic tags improve website readability and code organization.

4. They also help with SEO (Search Engine Optimization) and accessibility.

5. Examples of semantic HTML tags:

   * `<header>` → Defines the top section of a page
   * `<nav>` → Defines navigation links
   * `<section>` → Defines a section of content
   * `<article>` → Defines independent content or articles
   * `<aside>` → Defines side content
   * `<footer>` → Defines the bottom section of a page

---

## Q3.What is the difference between <div> and <span> tags?

`<div>` and `<span>` are both HTML tags used to group content, but they are used in different ways:

* `<div>` is a block-level element. It starts on a new line and takes full width. It is used to group larger sections of content.

* `<span>` is an inline element. It does not start on a new line and only takes as much space as needed. It is used to style or group small parts of text.

Simple difference:

* `<div>` → used for layout (big sections)
* `<span>` → used for small text parts or styling inline content

---

## Q4.Explain the difference between block-level elements and inline elements?

Block-level elements:

Start on a new line  
Take full width of the page  
Used for large sections of content  
Examples: <div>, <p>, <h1>

Inline elements:

Do not start on a new line  
Take only as much width as needed  
Used inside block elements for small parts of content  
Examples: <span>, <a>, <strong>

Simple difference:
Block elements are for structure, while inline elements are for styling or small content inside that structure.

---

## Q5.What is the purpose of the DOCTYPE declaration in HTML?

The DOCTYPE declaration tells the browser which version of HTML the page is written in.

It helps the browser to:
- Render the page correctly  
- Avoid quirks mode  
- Follow modern HTML rules  

In HTML5:
```html
<!DOCTYPE html>
Q6.What is the difference between id and class attributes?

id attribute:

Unique for one element
Used only once per page

class attribute:

Can be used on multiple elements
Used for grouping elements

Simple difference:
id = single unique element
class = multiple elements

Q7.How do you create a form in HTML?

A form is created using the <form> tag.

Example:

<form>
  <input type="text" placeholder="Enter your name">
  <input type="email" placeholder="Enter your email">
  <button type="submit">Submit</button>
</form>

A form collects user input and sends it to a server.

Q8.What are meta tags in HTML and why are they used?

Meta tags provide information about a webpage.

They are placed inside <head> and are not visible.

Uses:

SEO
Page description
Browser instructions

Example:

<meta name="description" content="HTML tutorial">
Q9.Explain the purpose of the alt attribute in the <img> tag?

The alt attribute describes the image.

It:

Shows text if image fails
Helps screen readers
Improves SEO

Example:

<img src="image.jpg" alt="A boy playing football">
Q10.How do you make an image clickable in HTML?

Wrap image inside <a> tag.

Example:

<a href="https://example.com">
  <img src="image.jpg" alt="Click me">
</a>
Q11.What is the difference between JPG, PNG, SVG, and WebP?

JPG:

Small size
Good for photos
No transparency

PNG:

High quality
Supports transparency

SVG:

Vector format
Scalable without loss
Best for logos

WebP:

Modern format
Small size + good quality
Q12.What are semantic tags in HTML5?

Semantic tags define meaning of content.

Examples:

<header>
<footer>
<section>
<article>

They improve structure and readability.

Q13.What is the difference between <script>, async, and defer?

script:

Blocks HTML loading

async:

Runs when ready (no order)

defer:

Runs after HTML loads (in order)
Q14.How do you embed audio and video in HTML5?

Audio:

<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
</audio>

Video:

<video controls width="300">
  <source src="video.mp4" type="video/mp4">
</video>
Q15.What is the difference between relative and absolute paths?

Relative:

Local file path
Example: images/pic.jpg

Absolute:

Full URL
Example: https://example.com/image.jpg
Q16.What are data attributes (data-*)?

Used to store extra data in HTML.

Example:

<div data-user-id="101"></div>

Used with JavaScript.

Q17.What is viewport meta tag?

Used for responsive design.

<meta name="viewport" content="width=device-width, initial-scale=1.0">

Makes website mobile friendly.

Q18.How to improve SEO using HTML?
Use headings properly
Add title tag
Add meta description
Use semantic tags
Add alt text
Use proper links
Q19.What are accessibility best practices?
Use semantic tags
Add alt text
Use labels in forms
Use proper headings
Good color contrast
Q20.What is difference between strong vs b and em vs i?

strong:

Important text

b:

Only bold

em:

Emphasized text

i:

Only italic