# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: HTML Structure

What is the difference between the `<head>` and `<body>` sections of an HTML document? What kind of content goes in each?

**Your Answer:**
The <head> is the section at the top of an HTML document that contains information about the webpage, not the content that is shown on the page. It includes things like the page title, metadata, links to stylesheets, and scripts.

The <body> contains the main content of the website that users can see and interact with, such as text, images, links, buttons, and forms.

## Question 2: Semantic HTML

Why should we use semantic elements like `<header>`, `<main>`, and `<footer>` instead of using `<div>` tags for everything?

**Your Answer:**
Semantic elements like <header>, <main>, and <footer> should be used instead of <div> tags because they clearly define different sections of a webpage. This makes the code easier to read, understand, and maintain, and it helps separate styles and behaviors more effectively.

## Question 3: CSS Selectors

Given the following HTML:

```html
<ul>
  <li class="vegetable">Carrots</li>
  <li class="vegetable">Broccoli</li>
  <li class="fruit" id="favorite">Mango</li>
</ul>
```

Write THREE different CSS rules:

1. One that makes ALL list items have a `yellow` background
2. One that makes only the vegetables have `green` text color
3. One that makes only the Mango `bold`

**Your Answer:**

```css
li {
  background-color: yellow;
}
.vegetable {
  color: green;
}
#favorite {
  font-style: bold;
}
```

## Question 4: The Box Model

In your own words, explain the four parts of the CSS box model (content, padding, border, margin). What is the purpose of each part?

**Your Answer:**

## Question 5: Box-Sizing

What problem does `box-sizing: border-box` solve? Why do we include it in a CSS reset at the top of our CSS files?

**Your Answer:**
box-sizing: border-box solves the problem of elements becoming larger than expected when padding and borders are added. It makes sure the width and height of an element include its padding and border. We include it in a CSS reset so layouts are more predictable and consistent across all elements and browsers.

## Question 6: Display Property

What is the difference between `display: block`, `display: inline`, and `display: inline-block`? Give an example of when you might use `inline-block`.

**Your Answer:**
`display: block` makes an element take up the full width of its container and start on a new line.
`display: inline` keeps elements on the same line and only takes up as much width as the content, but it does not allow width or height to be set.
`display: inline-block` keeps elements on the same line like inline elements, but also allows you to set width, height, padding, and margins.
