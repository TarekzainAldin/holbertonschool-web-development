Understand the Basics of CSS
CSS Overview: CSS (Cascading Style Sheets) is used to style and layout HTML elements.
Adding Style:
Inline: <p style="color: red;">Text</p>
Internal: Inside <style> tags in the <head> of the HTML.
External: Link a .css file using <link rel="stylesheet" href="styles.css">.
2. Key CSS Concepts
Class: A reusable CSS rule applied using class="classname" in HTML.
Selectors:
Target specific elements (e.g., .class, #id, element).
Specificity:
Inline styles have the highest specificity.
IDs (#id) are more specific than classes (.class), which are more specific than tags.
Box Model:
Consists of content, padding, border, and margin.
3. Tools and Validators
Use the W3C CSS Validator to ensure CSS compliance.
Use W3C HTML Validator to validate your HTML.
Steps for Your Tasks
Task 0: README and Objectives
Create a detailed README.md file explaining the project objectives and the learning goals. Use the structure I shared earlier for creating a professional README.
Task 1: Replicate the Figma Design
Access the Figma file.
Analyze:
Fonts, colors, margins, paddings, and layout.
Duplicate to your drafts to inspect design elements.
Task 2: CSS File
Create a styles.css File: Place all styles in this external stylesheet.
Link it to your HTML file:
html
Copy code
<link rel="stylesheet" href="styles.css">
Task 3: Key CSS Features to Implement
Selectors:
Use tag selectors for default styles (e.g., body, p, h1).
Use classes for reusable styles (e.g., .button, .card).
Box Properties:
Define width, height, margin, padding, and border for layout.
Typography:
Use font-family, font-size, and color.
Extract these details from the Figma file.
Positioning:
Use position (relative, absolute, fixed) to align elements as needed.
Flexbox/Grid:
Use display: flex or display: grid for layout alignment.
Task 4: Specificity Management
Avoid inline styles; prefer external CSS for maintainability.
Use appropriate selectors (class or ID) based on specificity needs.
Task 5: Final Validation
Validate your HTML and CSS files using W3C validators.
Test in multiple browsers to ensure consistency.
Resources to Help
CSS Specificity Explained
MDN Web Docs on Box Model
Flexbox Guide