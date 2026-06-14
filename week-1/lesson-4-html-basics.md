# Lesson 4: HTML — Building the Skeleton of a Webpage

**Week 1 · Lesson 4 of 5 · ~60 minutes**

---

## 🎯 What You'll Learn

How to write HTML to define the structure of a webpage — the same language every website uses.

---

## 🧠 The Concept

**HTML** (HyperText Markup Language) describes the *structure* of a webpage using **tags**. It is not really a programming language — it is a markup language.

Think of HTML as the skeleton of a building. It defines what is there (walls, floors, doors) but not what color they are or how they look. That is CSS's job (next lesson).

---

## 📚 Essential HTML Tags

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>My Page</title>
  </head>
  <body>

    <!-- Headings -->
    <h1>Big Heading</h1>
    <h2>Smaller Heading</h2>

    <!-- Paragraph -->
    <p>This is a paragraph of text.</p>

    <!-- Links -->
    <a href="https://github.com">Visit GitHub</a>

    <!-- Images -->
    <img src="photo.jpg" alt="A description of the image">

    <!-- Unordered list -->
    <ul>
      <li>First item</li>
      <li>Second item</li>
    </ul>

    <!-- Ordered list -->
    <ol>
      <li>Step one</li>
      <li>Step two</li>
    </ol>

    <!-- Container -->
    <div>
      <p>Content inside a container</p>
    </div>

    <!-- Bold and italic -->
    <p>This is <strong>bold</strong> and this is <em>italic</em>.</p>

  </body>
</html>
```

---

## ✍️ Hands-On Exercise

1. Open VS Code
2. Create a new file called `index.html`
3. Type `!` and press Tab — VS Code auto-generates a full HTML template (this is Emmet)
4. Inside `<body>`, add an `<h1>` with your name
5. Add a `<p>` describing yourself
6. Add a `<ul>` with 3 things you want to learn
7. Add an `<a>` link to your GitHub profile
8. Save, then double-click the file — it opens right in your browser!

---

## 🚀 Challenge

Build a simple "About Me" page with:
- Your name as an `<h1>`
- A short bio paragraph
- A list of your skills (sales skills absolutely count!)
- A link to something you find interesting

---

## 💡 Tips

- Every opening tag needs a closing tag: `<p>text</p>`
- Some tags are self-closing: `<img>`, `<br>`, `<input>`
- Right-click any webpage → "Inspect" to see the HTML behind it
- VS Code's Live Preview extension shows changes in real time

---

## ✅ Next Up

**Lesson 5: CSS** — making your webpage look genuinely good
