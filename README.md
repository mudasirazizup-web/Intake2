# Intake2

# 🌐 Basic HTML Tags – Detailed Guide

This document expands on the basic HTML tags with **more detailed explanations, attributes, and examples** to help you understand how each tag works in real-world usage.

---

## 🧱 1. HTML Document Structure

```html
<!DOCTYPE html> <!-- Declares HTML5 -->
<html lang="en"> <!-- Root element, lang helps accessibility -->

<head>
    <meta charset="UTF-8"> <!-- Supports all characters -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Responsive design -->
    <title>My Web Page</title> <!-- Browser tab title -->
</head>

<body>
    <!-- Visible content goes here -->
</body>
</html>
```

### 🔍 Details:

* `<!DOCTYPE html>` → tells browser it's HTML5
* `<html>` → wraps entire page
* `<head>` → metadata (not visible)
* `<body>` → visible content

---

## 🏷️ 2. Headings (`<h1>` to `<h6>`)

```html
<h1>Main Title</h1>
<h2>Sub Title</h2>
<h3>Section Title</h3>
```

### 🔍 Details:

* `<h1>` is the most important (use once per page for SEO)
* `<h6>` is the least important
* Helps structure content for users and search engines

---

## 📄 3. Paragraph (`<p>`)

```html
<p>This is a paragraph of text.</p>
```

### 🔍 Details:

* Automatically adds space before and after
* Used for blocks of text

---

## ↩️ 4. Line Break (`<br>`)

```html
<p>Hello<br>World</p>
```

### 🔍 Details:

* Breaks line without starting a new paragraph
* Self-closing tag (no closing tag needed)

---

## 🔗 5. Anchor Tag (`<a>`)

```html
<a href="https://example.com" target="_blank">Visit Site</a>
```

### 🔍 Attributes:

* `href` → URL destination
* `target="_blank"` → opens link in new tab

### 💡 Tip:

Always include `https://` for external links

---

## 🖼️ 6. Image Tag (`<img>`)

```html
<img src="photo.jpg" alt="A photo" width="300" height="200">
```

### 🔍 Attributes:

* `src` → image path
* `alt` → description (important for accessibility & SEO)
* `width`, `height` → control size

### ⚠️ Note:

`<img>` is self-closing

---

## 📋 7. Lists

### 🔹 Unordered List

```html
<ul>
    <li>Apple</li>
    <li>Banana</li>
</ul>
```

### 🔹 Ordered List

```html
<ol>
    <li>Step One</li>
    <li>Step Two</li>
</ol>
```

### 🔍 Details:

* `<ul>` → bullet points
* `<ol>` → numbered list
* `<li>` → list item

---

## 📊 8. Table

```html
<table border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>22</td>
    </tr>
</table>
```

### 🔍 Tags:

* `<table>` → table container
* `<tr>` → row
* `<th>` → header cell (bold)
* `<td>` → data cell

---

## 📝 9. Forms

```html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">

    <br><br>

    <input type="submit" value="Send">
</form>
```

### 🔍 Attributes:

* `action` → where form data goes
* `method` → `get` or `post`
* `input type="text"` → text field
* `input type="submit"` → button

---

## 📦 10. `<div>` (Block Element)

```html
<div>
    <p>This is inside a div</p>
</div>
```

### 🔍 Details:

* Block-level container
* Takes full width
* Used for layout and grouping

---

## 🧵 11. `<span>` (Inline Element)

```html
<p>This is <span style="color:red;">red</span> text.</p>
```

### 🔍 Details:

* Inline container
* Used for styling part of text
* Does not break line

---

## 💬 12. Comments

```html
<!-- This is a comment -->
```

### 🔍 Details:

* Not displayed in browser
* Used for notes or explanations

---

## ⚙️ 13. Common Attributes

| Attribute | Description          |
| --------- | -------------------- |
| `id`      | Unique identifier    |
| `class`   | Used for CSS styling |
| `style`   | Inline CSS           |
| `title`   | Tooltip text         |

```html
<p id="intro" class="text" style="color:blue;" title="Tooltip">
    Example text
</p>
