
---
## HTML and CSS Notes: Multi-Section Website Project

---

### 1. Overview of the Project

This project demonstrates how to create a structured multi-section webpage using external CSS. It includes:

* A navigation bar
* Main content sections (Home, Services, About)
* A footer with links and social media references
* An external stylesheet linked via `<link>`

---

# 2. Corrections and Best Practices

# a. Correct the CSS File Name Case

**Incorrect:**

```html
<link rel="stylesheet" href="style.CSS">
```

**Correct:**

```html
<link rel="stylesheet" href="style.css">
```

Filenames are case-sensitive on most servers. Always use lowercase for consistency.

---
# b. Fix Invalid HTML Attribute

**Incorrect:**

```html
<a stylecenter="#home">Home</a>
```

**Correct:**

```html
<a href="#home">Home</a>
```

The attribute `stylecenter` is invalid. Use `href` to link to sections correctly.

---

# c. Match Section ID References

Your section has:

```html
<section id="service">
```

But the navigation links to `#services`. The ID should match the link:

**Corrected section:**

```html
<section id="services">
```

Consistency between IDs and links ensures proper navigation.

---

# d. Fix Font-Family Syntax

**Incorrect:**

```css
font-family: Georgia,;
```

**Correct:**

```css
font-family: Georgia, serif;
```

Always provide a fallback font in case the primary one isn't available.

---

# 3. Suggested Improvements

# a. Add Padding and Spacing to Sections

--css
section {
    padding: 20px;
    margin-bottom: 20px;
}
```

This improves the visual layout and spacing between sections.

---

# b. Improve Navigation List Styling

--css
ul {
    list-style: none;
    padding: 10px;
    text-align: center;
}

ul li {
    display: inline-block;
    margin: 10px;
}
```

This makes the navigation horizontal and visually appealing.

---

# c. Add Button Styling

--css
button {
    background-color: teal;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: darkslategray;
}
```

Styled buttons enhance user experience and visual design.

---

# 4. Structure Summary

* The HTML layout includes a `<nav>`, `<main>`, and `<footer>`.
* Each section is styled with an external CSS file.
* The CSS uses reset styles, font settings, color schemes, and layout adjustments.

--- Made by: MALAIKA SUBHAN.