1. Types of CSS Used:
• Inline CSS:
  Used in the <section> tag to apply a linear gradient background directly.
• Internal CSS:
  Written inside the <style> block in the <head> section.
  Used to style headings (h1, h2), the bio class, and contact section paragraphs.
• External CSS:
  Most of the styling is done in the external style.css file.
  It includes styling for layout, image, card effects, hover transitions, and lists.

2. CSS Selectors Used:
• ID Selector:
  #profile-pic is used to style the profile image with size, border, and shadow.

• Class Selectors:
  .profile-card is used to apply shadow and hover effect on the card.
  .bio is used to style the short description text.
  .hobbies and .contact are used for styling hobbies list and contact section.

• Element Selectors:
  body, ul, li, a, img are styled directly using element selectors.

• Group Selector:
  h1, h2 are styled together for common heading styles.

• Descendant Selector:
  .contact a is used to style only the anchor tags inside the contact section.

• Attribute Selector:
  a[href] is used to style all links that contain an href attribute.

3. Bonus Features Implemented:
• Hover effect on contact links using a[href]:hover.
• Box-shadow and hover animation on the entire profile card using .profile-card.
• Hover background color effect on each hobby list item.