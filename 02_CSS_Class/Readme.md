
---
# HTML Structure Notes**

# Doctype & Language:

   * `<!DOCTYPE html>` declares the document as HTML5.
   * `lang="en"` specifies the language as English.

# Head Section:

   * `<meta>` tags define character encoding and responsive behavior.
   * `<title>` sets the page title.
   * `<link rel="stylesheet" href="style.css">` links the external CSS file.

# Body Content:

   # Main Container: `<main>` wraps all content sections.
   # **Sections:**

     * `#startup` — Introduces the class.
     * `#garden` — Describes a magical garden.
     * `#main` — Introduces a curious boy named Leo.
     * `#saw` — Lists magical things Leo saw.
     * `#secret` — Shares the secret of the magical garden.
  # Footer Section:

      Contains a link, list, and name attributions.
      Note: There is a mistake in your footer tag — change `<footer= id="footer">` to `<footer id="footer">`.

---

# CSS Styling Notes

# Reset & Base Styling:

   * `*` selector resets margin, padding, sets `box-sizing`, and font.
   * `html, body` are set to full width and height.

# Section Styling:

   * Common section style includes padding, full-screen height, center alignment, and font settings.

# Individual Section Colors:

   * `#startup` — Light blue background, dark blue text.
   * `#garden` — Cyan background, bright blue text.
   * `#main` — Salmon background, brownish-red text.
   * `#saw` — Light pink background, deep pink text.
   * `#secret` — Orange background, brown text.

# Footer Styling:

   * Matches the layout of other sections.
   * Background and text color are orange and yellow.

---

# Fixes and Suggestions:

* Fix `footer` tag:Change `footer= id="footer"` to `footer id="footer"`.
* Duplicate ID Warning: You use `#footer` twice in the CSS; although it's valid, it's better to write it once to avoid confusion.
* Optional Enhancement:Add `<head>` styles like:

  ```css
  h1, h2, h3, h4, h5, h6 {
    margin-bottom: 15px;
  }
  a {
    color: inherit;
    text-decoration: underline;
  }
  ----Made by:MALAIKA SUBHAN.