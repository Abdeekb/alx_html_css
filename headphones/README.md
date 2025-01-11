# Headphones Website Project

This project is part of the ALX HTML & CSS curriculum. It showcases a responsive webpage for a fictional headphones store, designed with Figma's mockup and enhanced with responsive and interactive features.

## 🎯 Objective
Create a visually appealing webpage based on a Figma design.
Implement responsive behavior for screens 480px or smaller.
Add hover/active interactions for buttons and links.
Center content on the page with a maximum width of 1000px.

## 🖥️ Features
### Responsive Design:
- The webpage seamlessly adapts to mobile screens when the screen width is 480px or less.
- All elements are reorganized for an optimal user experience on smaller devices.

### Hover/Active States:
- Links: On hover or active, the color changes to `#FF6565`.
- Buttons: On hover or active, the button opacity changes to 0.9.

### Content Centering:
- All content is centered within a maximum width of 1000px on the page.

## 🛠️ Technical Details
### 1. Fonts
- Fonts used in the Figma design:
  - [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
  - [Spin Cycle OT](https://fonts.google.com/specimen/Spin+Cycle+OT)
- Ensure these fonts are installed on your system for proper rendering.

### 2. CSS Implementation
The hover/active states for links and buttons are implemented with the following styles:

```css
/* Links hover/active state */
a:hover, a:active {
    color: #FF6565;
}

/* Buttons hover/active state */
button:hover, button:active {
    opacity: 0.9;
}

The maximum width of content is defined using the following rule:
/* Center content and set max width */
.container {
    max-width: 1000px;
    margin: 0 auto;
}

📐 Design Notes
Some Figma measurements may include float values. Values were rounded for simplicity and consistency. The mobile version of the webpage switches at a screen width of 480px or less using a CSS media query:

css
Copier le code
@media (max-width: 480px) {
    /* Mobile-specific styles go here */
}
