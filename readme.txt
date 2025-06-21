

CSS Types Used:


1. **Inline CSS**
   - Applied directly inside an HTML element using the `style` attribute.
   - Used in this project for setting the background color of the main card container:
     ```html
     <div class="card" style="background-color: #fefae0;">
     ```

2. **Internal CSS**
   - Not used in this project.
   - Typically written inside a `<style>` tag within the `<head>` section of an HTML document.
   - Useful for small projects or one-page sites.

3. **External CSS**
   - Main styling in this project is written in an external CSS file named `style.css`.
   - Linked to the HTML using:
     ```html
     <link rel="stylesheet" href="style.css">
     ```
   - Helps keep HTML cleaner and improves reusability and maintainability of styles.

---

CSS Selectors Used:

- ID Selector
  - Example: `#profile-pic`
  - Targets a unique element (in this case, the profile image).
  - Used to apply specific styles like size, border, and shape.

- Class Selectors
  - Examples: `.card`, `.card-content`, `.bio`, `.contact`
  - Used to apply reusable styles to multiple elements with similar roles or structure.

- Element Selectors
  - Examples: `body`, `p`, `ul`, `li`
  - Used to apply base styling to common HTML tags.

- Group Selector
  - Example: `h1, h3`
  - Groups multiple elements to apply the same styles at once (e.g., heading font color and margin).

- Descendant Selector
  - Example: `.contact p`
  - Selects elements only when they are nested inside a parent with a specific class. In this case, it styles paragraphs inside the contact section differently.

- Attribute Selector
  - Example: `a[href]`
  - Targets anchor tags that contain an `href` attribute, giving them consistent link color and hover behavior.

