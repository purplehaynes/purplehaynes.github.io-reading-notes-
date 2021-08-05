# What is CSS?

- CSS stands for Cascading Style Sheets
- Allows you to create great looking web pages

### What is CSS used for?

- CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.
- CSS can be used for very basic document text styling — for example changing the color and size of headings and links

### How do you use CSS?

- There are three ways to use CSS: External, Internal, and Inline

- External CSS

  - External styles are defined within the `<link>` element, inside the `<head>` section of an HTML page:

  ```
  <!DOCTYPE html>
  <html>
  <head>
  <link rel="stylesheet" href="mystyle.css">
  </head>
  <body>

  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>

  </body>
  </html>
  ```

  - An external style sheet can be written in any text editor, and must be saved with a .css extension.
  - The external .css file should not contain any HTML tags.

- Internal CSS

  - An internal style sheet may be used if one single HTML page has a unique style. The internal style is defined inside the `<style>` element, inside the head section.

  ```
  <!DOCTYPE html>
  <html>
  <head>
  <style>
  body {
      background-color: linen;
  }

  h1 {
      color: maroon;
      margin-left: 40px;
  }
  </style>
  </head>
  <body>

  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>

  </body>
  </html>
  ```

- Inline CSS

  - An inline style may be used to apply a unique style for a single element. To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

  ```
  <!DOCTYPE html>
  <html>
  <body>

  <h1 style="color:blue;text-align:center;">This is a heading</h1>
  <p style="color:red;">This is a paragraph.</p>

  </body>
  </html>
  ```

  **Fair Warning:** An inline style loses many of the advantages of a style sheet (by mixing content with presentation). Minimize using this method.
