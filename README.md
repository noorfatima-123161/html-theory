

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
Render the page correctly
Avoid displaying the page in “quirks mode”
Follow modern HTML rules properly

In HTML5, it is written simply as:

```html id="x1q9aa"
<!DOCTYPE html>
```

---

## Q6.What is the difference between id and class attributes?

id attribute:
Used to identify a single, unique element on a page
One id can be used only once in a webpage
Written like: id="header"

class attribute:
Used to group multiple elements together
Can be used on many elements in the same page
Written like: class="box"

Simple difference:
id is for one unique element, while class is for multiple elements that share the same style or behavior.

---

## Q7.How do you create a form in HTML?

You create a form in HTML using the <form> tag.

Inside the form, you add input fields like text, password, email, and a submit button.

Simple example:

```html id="m8k2bb"
<form>
  <input type="text" placeholder="Enter your name">
  <input type="email" placeholder="Enter your email">
  <button type="submit">Submit</button>
</form>
```

In simple words:
A form is used to collect user information and send it somewhere (like a server).

---

## Q8.What are meta tags in HTML and why are they used?

Meta tags are tags in HTML that provide information about a webpage.

They are placed inside the <head> section of the HTML file and are not shown on the webpage.

Why they are used:
To give information about the page (like description, author, keywords)
To help search engines understand the content (SEO)
To control how the page is displayed on different devices

Simple example:

```html id="k3w9cc"
<meta name="description" content="This is a simple HTML tutorial page">
```

---

## Q9.Explain the purpose of the alt attribute in the <img> tag?

The alt attribute in the <img> tag is used to describe the image.

It shows a text description if the image does not load or if the user is using a screen reader.

Purpose:
Helps users understand what the image is about
Improves accessibility for visually impaired users
Useful for SEO (search engines can read it)

Example:

```html id="p9n2dd"
<img src="image.jpg" alt="A boy playing football">
```

---

## Q10.How do you make an image clickable in HTML?

You can make an image clickable by wrapping it inside an anchor (<a>) tag.

When the user clicks the image, it will take them to a link.

Example:

```html id="v6t1ee"
<a href="https://example.com">
  <img src="image.jpg" alt="Click me">
</a>
```

In simple words:
We put the image inside a link, so the image works like a button.

---

## Q11.What is the difference between JPG, PNG, SVG, and WebP image formats in web development?

JPG (JPEG):
Good for photos and colorful images
Small file size
Does not support transparency

PNG:
High quality images
Supports transparency (clear background)
File size is usually larger than JPG

SVG:
Vector format (made with code, not pixels)
Can scale without losing quality
Best for logos and icons

WebP:
Modern format developed by Google
Smaller file size with good quality
Supports both transparency and animation

Simple difference:
JPG/PNG/WebP are for normal images, while SVG is for scalable graphics like logos and icons.

---

## Q12.What are semantic tags introduced in HTML5 such as <header>, <footer>, <section> and <article>?

Semantic tags in HTML5 are tags that clearly describe the meaning of the content they contain.

They make the webpage structure easy to understand for both developers and browsers.

Common semantic tags:

* `<header>` → Used for the top section of a page (logo, title, navigation)
* `<footer>` → Used for the bottom section of a page (copyright, links, info)
* `<section>` → Used to divide content into different sections
* `<article>` → Used for independent content like blog posts or news

Simple meaning:
These tags help organize a webpage in a meaningful way instead of using only `<div>` tags.

---

## Q13.What is the difference between <script>, async, and defer in HTML?

`<script>` tag:

* Used to add JavaScript to a webpage
* By default, it blocks HTML loading until the script is finished running

async:

* Script loads in the background while HTML is loading
* Runs immediately when it is ready
* Order is not guaranteed

defer:

* Script loads in the background while HTML is loading
* Runs only after the full HTML page is loaded
* Keeps scripts in order

Simple difference:
script → blocks page loading
async → runs as soon as ready (no order)
defer → runs after page loads (keeps order)

---

## Q14.How do you embed audio and video in HTML5?

In HTML5, you can embed audio and video using the <audio> and <video> tags.

Audio embedding:

```html id="r2f8ff"
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
</audio>
```

Video embedding:

```html id="n6j3gg"
<video controls width="300">
  <source src="video.mp4" type="video/mp4">
</video>
```

---

## Q15.What is the difference between relative paths and absolute paths in HTML?

Relative path:

* It shows the file location relative to the current file
* Used for files inside the same project
* Example: images/pic.jpg or ../images/pic.jpg

Absolute path:

* It shows the full file location or complete URL
* Used to access files from any location (including internet)
* Example: [https://example.com/images/pic.jpg](https://example.com/images/pic.jpg)

Simple difference:
Relative path is for local project files, while absolute path is the full address of a file or resource.

---

## Q16.What are data attributes in HTML (data-*)? Where are they used?

Data attributes (data-*) are custom attributes in HTML used to store extra information on an element.

They start with data- and can hold any value.

Example:

```html id="t4y1hh"
<div data-user-id="101" data-role="admin">
  User Info
</div>
```

Where they are used:

* To store extra data in HTML elements
* Used with JavaScript to access and use that data
* Helpful for dynamic web applications without changing HTML structure

Simple meaning:
Data attributes are used to attach hidden extra information to elements so JavaScript can use it later.

---

## Q17.What is the purpose of the viewport meta tag in responsive web design?

The viewport meta tag is used to control how a webpage is displayed on different screen sizes (especially mobile devices).

It helps make websites responsive.

Example:

```html id="z8k2ii"
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Purpose:

* Makes the page fit properly on mobile, tablet, and desktop screens
* Sets the width of the page to match the device screen
* Controls zoom level when the page first loads

Simple meaning:
It tells the browser how to adjust the page so it looks good on all devices.

---

## Q18.How can you improve SEO using HTML?

You can improve SEO (Search Engine Optimization) using HTML by writing clean and meaningful code that helps search engines understand your page.

Ways to improve SEO using HTML:

* Use proper heading tags (<h1>, <h2>, <h3>) in a structured way
* Add a clear <title> tag for each page
* Use <meta description> to describe your page
* Use semantic tags like <header>, <section>, <article>
* Add alt text to images
* Use meaningful links (<a> with proper text instead of “click here”)

Simple meaning:
Good HTML structure helps search engines read your website better, which improves ranking and visibility.

---

## Q19.What are accessibility best practices in HTML?

Accessibility best practices in HTML are ways to make websites easy to use for everyone, including people with disabilities.

Best practices:

* Use proper semantic tags like <header>, <nav>, <main>, <footer>
* Add alt text for images so screen readers can describe them
* Use clear and readable headings (<h1> to <h6>)
* Make forms accessible with labels (<label> tag)
* Use meaningful link text instead of “click here”
* Ensure good color contrast for better readability

Simple meaning:
Accessibility in HTML means building websites that everyone can understand and use easily.

---

## Q20.What is the difference between <strong> vs <b> and <em> vs <i> tags?

<strong> vs <b>:

* <strong> → Shows important text (semantic meaning + bold look)
* <b> → Only makes text bold (no meaning, just styling)

<em> vs <i>:

* <em> → Shows emphasized text (semantic meaning + italic look)
* <i> → Only makes text italic (no meaning, just styling)

Simple difference:

* <strong> and <em> = give meaning + style
* <b> and <i> = only style

---
