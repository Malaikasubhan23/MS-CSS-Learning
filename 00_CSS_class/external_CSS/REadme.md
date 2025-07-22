
---
#HTML + CSS Notes:External & Inline CSS

---

#what is CSS.

(Cascading-stylesheet) is used to style and design HTML elements. It controls layout, colors, fonts, spacing, and more, making web pages visually appealing.

---

### 2. Types of CSS

#### A. Inline CSS

* Written directly inside an HTML tag using the `style` attribute.
* Affects only that specific element.
* Useful for quick styling but not recommended for large projects.

**Example:**

```html
<h1 style="color: black; background-color: burlywood;">CSS Class# 01</h1>
```

#### B. External CSS

* Written in a separate css file (e.g., `style.css`).
* Linked to the HTML file using a `<link>` tag inside the `<head>`.
* Ideal for maintaining clean, reusable, and consistent design across multiple pages.

**Example HTML:**

```html
<link rel="stylesheet" href="style.css">
```

**Example CSS (style.css):**

```css
h1 {
  color: black;
  background-color:burlywood;
}

p {
  color: white;
  background-color: darkcyan;
}

button {
  color: brown;
  background-color: yellow;
}

---

Full Code Example

#External CSS Example

**HTML File (index.html):**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>External_CSS</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1>MS web development <br>& designer</h1>
  <p>Welcome to our website.</p>
  <div id="click">
    <button>click</button>
  </div>
</body>
</html>
```

**style.css File:**

```css
h1 {
  color: black;
  background-color:burlywood;
}

p {
  color: white;
  background-color: darkcyan;
}

button {
  color: brown;
  background-color: yellow;
}

#inline CSS Example

html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Inline CSS</title>
</head>
<body>
  <h1 style="color: black; background-color: burlywood;">CSS Class# 01</h1>
  <p style="color:white; background-color: darkcyan;">
    Lorem ipsum dolor sit amet consectetur, adipisicing elit...
  </p>
  <button style="color:brown; background-color: yellow;">Click Resume</button>
</body>
</html>
```

---

### 4. Summary Table

| Type         | Description                   | Advantages                  | Disadvantages                   |
| ------------ | ----------------------------- | --------------------------- | ------------------------------- |
| Inline CSS   | CSS inside HTML tags          | Quick, easy for small tasks | Hard to manage, not reusable    |
| External CSS | CSS in a separate CSS file | Clean, reusable, organized  | Requires linking and extra file |

--- Made by:MALAIKA SUBHAN.
