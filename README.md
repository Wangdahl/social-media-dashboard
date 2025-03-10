# Frontend Mentor - Social Media Dashboard with Theme Switcher

This is my solution for the [Social Media Dashboard with Theme Switcher challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-media-dashboard-with-theme-switcher-6oY8ozp_H). The challenge is to build a responsive dashboard that supports both light and dark modes with a manual theme toggle that defaults to the system preference.

## Table of Contents
- [The Challenge]
- [My Process]
  - [Built With]
  - [What I Learned]
  - [Manual Theme Toggle]
- [Author]
- [Acknowledgments]


### The Challenge

Users should be able to:
- View an optimal layout for the site on different screen sizes.
- See hover states for all interactive elements.
- Toggle the color theme (light/dark) based on their preference. On first load, the dashboard reflects the user's system preference using the `prefers-color-scheme` media query, and a manual override is available that saves the selection in localStorage.

## My Process

I built this project using a mobile-first approach and ensured responsiveness with CSS Grid and Flexbox. The project includes a manual theme toggle that defaults to the system preference on first load and stores the user’s selection in localStorage for subsequent visits.

### Built With

- **HTML5** – Semantic markup
- **CSS3** – Custom properties, Flexbox, and CSS Grid
- **SCSS** – Modular and maintainable styles
- **JavaScript** – For theme toggling and localStorage management

### What I Learned

- **Responsive Design:**  
    Building a responsive layout using a mix of Flexbox and CSS Grid helped me ensure that the dashboard looks great on various devices.

- **CSS Custom Properties:**  
    Using CSS variables made it straightforward to implement theming across the entire project.

- **Theme Toggling:**  
    I implemented a manual theme toggle that leverages the browser's `prefers-color-scheme` to set the initial theme, and then allows users to override that preference. 


### Manual Theme Toggle
    The theme toggle is implemented using radio inputs for dark and light modes. If no preference is stored, the site detects the system's preference via window.matchMedia('(prefers-color-scheme: dark)') and applies the appropriate theme. This ensures a seamless experience for first-time visitors and saves their selection for future visits.

### Author
    - Melker Wångdahl

### Acknowledgments
    Thanks to Frontend Mentor and Free Code Camp for the inspiration for the project.