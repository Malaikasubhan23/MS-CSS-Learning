
---

# HTML Notes – **The Valley of Liora Story Structure**

# HTML Boilerplate:

* `<!DOCTYPE html>`: Declares the document as HTML5.
* `<html lang="en">`: Sets the document language to English.
* `<meta charset="UTF-8">`: Supports all character types.
* `<meta name="viewport"...>`: Makes the page responsive on all devices.
* `<title>`: Sets the title of the browser tab.

# Linking CSS:

* `<link rel="stylesheet" href="style.css" />`: Connects your HTML to the external CSS file.

# Main Content:

The story is divided into "six sections" wrapped in the `<main>` tag:

* `#intro`: Introduction title.
* `#sec1`: Background of the magical valley and Elira.
* `#sec2`: Discovery of the Whispering Tree.
* `#sec3`: Elira's magical awakening.
* `#sec4`: The deeper truth of lost magic and the rising threat.
* `#sec5`: Final resolution — Elira becomes the Heart of Liora.

Each section includes a heading and paragraph for readability and storytelling.

---

# CSS Notes – Styling and Layout

# Global Reset

```css
* {
   margin: 0;
   padding: 0;
   box-sizing: border-box;
   font-family: 'Times New Roman', Times, serif;
}
```

* Resets default browser spacing and ensures consistent sizing.
* Uses a classic serif font for a storytelling theme.

```css
html, body {
   width: 100%;
   height: 100%;
}
```

* Sets full-screen height and width.

---

# Section Styling:

```css
section {
    height: 100vh; /* Full viewport height */
    width: 100%;
    padding: 80px;
    text-align: center;
    font-size: 30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 20px;
}
```

* Every section takes full screen height.
* Flexbox is used to center content both vertically and horizontally.
* `gap: 20px` adds spacing between elements inside each section.

---

# Individual Section Themes:

| Section  | Background Color         | Text Color                 | Purpose                       |
| -------- | ------------------------ | -------------------------- | ----------------------------- |
| `#intro` | Light pink (`#FFD1DC`)   | Deep rose (`#C0395D`)      | Title section                 |
| `#sec1`  | Peach (`#FFE0B2`)        | Orange (`#E67E22`)         | Valley and Elira intro        |
| `#sec2`  | Light purple (`#B7ACF7`) | Dark blue-gray (`#25284A`) | Whispering Tree discovery     |
| `#sec3`  | Light violet (`#F7C0F7`) | Red-pink (`#F73C3F`)       | Elira’s magic awakens         |
| `#sec4`  | Light green (`#D0F0C0`)  | Green (`#27AE60`)          | The threat and truth of magic |
| `#sec5`  | Pale blue (`#D6F0FF`)    | Blue (`#2980B9`)           | Final battle and resolution   |

---

# Suggestions for Improvement

* You can add a `footer` if you'd like to include credits or navigation.
* For better mobile responsiveness, consider adding:

  ```css
  @media (max-width: 768px) {
    section {
      padding: 30px;
      font-size: 20px;
    }
  }
  ```
* Add some `line-height` in paragraphs for better readability:

  ```css
  p {
    line-height: 1.6;
  }

  ```Made by: MALAIKA SUBHAN.