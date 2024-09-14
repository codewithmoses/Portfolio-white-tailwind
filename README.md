
# Portfolio Website: Moses Oluwadamilare Oni

This is a full-stack developer portfolio website designed for Moses Oluwadamilare Oni. The portfolio showcases web development projects, graphic design skills, and Human-Computer Interaction expertise.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Website Structure](#website-structure)
- [Features](#features)
- [How to Use](#how-to-use)
- [Style Guide](#style-guide)
  - [HTML Structure](#html-structure)
  - [CSS Guidelines](#css-guidelines)
  - [Component Naming](#component-naming)
  - [Best Practices](#best-practices)
- [Contact](#contact)

## Technologies Used

This portfolio uses various technologies for both frontend and backend development, including:

### Frontend
- HTML5
- CSS3
- TailwindCSS
- Next.js
- JavaScript

### Backend
- PHP
- MariaDB
- MySQL
- MongoDB

### Software Tools
- npm
- Visual Studio Code
- Figma
- Adobe Illustrator

## Website Structure

The website has the following main components:

- **Header**: Contains navigation links and a call-to-action button for downloading the resume.
- **Hero Section**: Showcases the primary message of the portfolio—clean and minimalistic web development.
- **Technology Section**: Highlights the frontend, backend, and software tools used in the developer's work.
- **About Section**: Provides a brief introduction to Moses Oluwadamilare Oni's background and expertise.
- **Footer**: Contains social media links and the contact information for networking.

## Features

- **Responsive Design**: The website adapts to various screen sizes, ensuring a seamless experience across devices.
- **Minimalistic UI**: A focus on clean and minimalistic design to emphasize the developer's approach.
- **Interactive Navigation**: Features a responsive hamburger menu for mobile users.
- **Downloadable Resume**: A call-to-action button allows visitors to download the developer's resume in one click.

## How to Use

1. Clone or download the project repository.
2. Ensure you have an internet connection as external styles and fonts (Google Fonts, TailwindCSS, and FontAwesome) are used.
3. To modify the website:
   - Edit the HTML structure in `index.html`.
   - Modify styles using TailwindCSS.
   - Add your own images in the `img` folder.
4. Open the `index.html` file in any web browser to view the website.

## Style Guide

To maintain consistency and clarity across the website, follow these guidelines for writing HTML, CSS, and structuring components.

### HTML Structure

- **Semantics**: Use semantic HTML tags where possible (`<header>`, `<nav>`, `<section>`, `<footer>`, etc.).
- **Indentation**: Use 2 spaces for indentation in HTML files.
- **Attributes**: Use lowercase for all HTML tag names and attribute names.
  - Example: `<img src="image.jpg" alt="Portfolio image" />`
- **Class Names**: Use clear, descriptive class names, preferably following a [BEM](http://getbem.com/introduction/) (Block Element Modifier) convention.
  - Example: `.hero__title` for the title in the hero section.

### CSS Guidelines

The project is styled using **TailwindCSS**. However, in the cases where custom styles are added, follow these guidelines:

- **Class Names**: Tailwind's utility-first approach should be prioritized. For custom styles, use class names that are specific and avoid deep nesting.
- **Custom CSS**:
  - Avoid using inline styles. If needed, place all custom styles in a dedicated `.css` file (e.g., `custom.css`).
  - Example of a TailwindCSS class:
    ```html
    <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
      Button
    </button>
    ```
- **Colors**: Maintain the color palette as defined. Use the following colors for consistency:
  - Primary color: `#1A202C` (Tailwind Gray 900)
  - Accent color: `#2D3748` (Tailwind Gray 700)
  - Background: `#EDF2F7` (Tailwind Gray 100)

### Component Naming

Follow a clear and structured naming convention for sections and components:

- **Sections**: Use descriptive and clear names based on content.
  - Example: `hero`, `about`, `contact`, `footer`.
- **Modifiers**: If you have variations of components, use modifiers in your class names.
  - Example: `.btn-primary`, `.btn-secondary`.
  
**BEM Naming Convention Example**:
```html
<div class="hero">
  <h1 class="hero__title">Welcome to My Portfolio</h1>
  <p class="hero__description">Full Stack Developer</p>
</div>
```

### Best Practices

- **Mobile-first Design**: Use TailwindCSS's mobile-first approach for responsiveness.
- **Code Comments**: Add comments to sections in HTML and CSS files to make them more understandable.
  - Example:
    ```html
    <!-- Start of Hero Section -->
    <section class="hero">...</section>
    <!-- End of Hero Section -->
    ```
- **Consistency**: Ensure consistency in layout, color scheme, and font usage across all pages.
  - Use Google Fonts (such as `Poppins` for headings and `Roboto` for body text) as defined in the CSS.
  
- **Performance Optimization**: Minimize the use of large images and assets for faster load times.
  - Use `.webp` image format if possible for faster rendering.

## Contact

For any inquiries or collaboration opportunities, feel free to reach out through the following platforms:

- **Twitter**: [@moses_onit](https://twitter.com/moses_onit)
- **LinkedIn**: [Moses Oni](https://www.linkedin.com/in/moses-oni)
- **Email**: example@example.com

---

This portfolio website is a showcase of Moses Oni's development skills and design philosophy.
```

### Explanation of the Style Guide:

1. **HTML Structure**: Guidelines on how to properly write and organize HTML for better readability, emphasizing semantic HTML.
2. **CSS Guidelines**: Since TailwindCSS is used, the guide focuses on utility-first styling, but also provides rules for custom CSS if needed.
3. **Component Naming**: Suggests the use of the BEM (Block Element Modifier) methodology for class naming.
4. **Best Practices**: Tips on making the website mobile-first, adding comments, keeping consistency, and optimizing for performance.

This will help other developers understand the styling conventions and maintain the consistency and quality of the code across the project.
