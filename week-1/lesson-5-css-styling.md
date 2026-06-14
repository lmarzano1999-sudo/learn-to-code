# Lesson 5: CSS — Making Your Webpage Look Good

**Week 1 · Lesson 5 of 5 · ~60 minutes**

---

## 🎯 What You'll Learn

How to use CSS to style your HTML — colors, fonts, layout, spacing, and more. This is where your webpage goes from plain text to something that actually looks designed.

---

## 🧠 The Concept

**CSS** (Cascading Style Sheets) controls how HTML *looks*. If HTML is the skeleton, CSS is the skin, clothes, and makeup.

CSS works by *selecting* an HTML element and applying *rules* to it.

```css
selector {
  property: value;
}
```

---

## 📚 Essential CSS

```css
/* Colors and backgrounds */
h1 {
  color: #2c3e50;
  background-color: #ecf0f1;
}

/* Fonts */
body {
  font-family: Arial, sans-serif;
  font-size: 16px;
  line-height: 1.6;
}

/* Spacing */
p {
  margin: 20px;       /* space outside the element */
  padding: 10px;      /* space inside the element */
}

/* Width and height */
img {
  width: 300px;
  height: auto;       /* keeps the aspect ratio */
}

/* Borders */
div {
  border: 2px solid #333;
  border-radius: 8px; /* rounded corners */
}

/* Centering content */
.container {
  max-width: 800px;
  margin: 0 auto;     /* centers the container */
}

/* Flexbox — the most useful layout tool */
.row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 20px;
}

/* Hover effects */
a:hover {
  color: red;
  text-decoration: underline;
}

/* Classes (reusable styles) */
.highlight {
  background-color: yellow;
  font-weight: bold;
}
```

---

## 🔗 Linking CSS to HTML

Create a file called `styles.css` and link it in your HTML `<head>`:

```html
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```

---

## ✍️ Hands-On Exercise

Take the "About Me" page you built in Lesson 4 and style it:

1. Create a `styles.css` file in the same folder as your `index.html`
2. Link it in your HTML
3. Set a `font-family` on `body`
4. Give your `h1` a color and increase its size
5. Add a `.container` div around all your content and center it with `max-width: 700px; margin: 0 auto;`
6. Style your links so they change color on hover
7. Add some `padding` to your page so the text isn't squished against the edges

---

## 🚀 Challenge

Make your page look genuinely good. Try:
- A dark background with light text, or vice versa
- A Google Font (visit fonts.google.com and follow the instructions)
- A colored header bar at the top using a `<header>` tag
- Make your list items look like cards with `border`, `padding`, and `border-radius`

---

## 💡 Tips

- Open DevTools in your browser (F12 or right-click → Inspect) to live-edit CSS
- `Flexbox` is the most important layout tool to learn — Google "flexbox guide css-tricks" for the best reference
- CSS has hundreds of properties — don't memorize them, just look them up as you need them

---

## 🏁 Week 1 Complete!

You now know:
- How to use the terminal
- How to track changes with Git
- How to store and share code on GitHub
- How to build a webpage with HTML
- How to style it with CSS

**Come back next Sunday for Week 2: Python Programming Basics** 🐍

In the meantime, keep building on your About Me page — it'll become a real portfolio site by the end of the course!
