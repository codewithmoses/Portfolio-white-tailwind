

# 💻 Moss Oni Web Developer Portfolio - README

## Overview

Welcome to the **Moss Oni** portfolio! This is a **single-page HTML portfolio** designed using **Tailwind CSS** and **Cofic** for minimal and professional aesthetics. It showcases Moss Oni’s web development skills, focusing on clean UI, innovative projects, and technologies used in frontend and backend development.

The key sections include:
- Hero introduction with a profile image
- Technologies (Frontend, Backend, Software tools)
- Featured Projects
- Contact Information and social links

---

## 💻 How to Set Up the Project

1. **Download the Repository**:
   Clone or download the repository to your local machine:
   ```bash
   git clone https://github.com/codewithmoses/Portfolio-white-tailwind.git
   ```

2. **File Structure**:
   - **index.html**: The single-page HTML file showcasing the developer’s portfolio.
   - **/assets**: Contains images, project visuals, and other assets.
   - **/css**: Stores any custom styles, though Tailwind is linked via CDN.

3. **Installation**:
   No installation is needed, as **Tailwind CSS** and **Cofic** are included via CDN. Simply open `index.html` in a browser to view the portfolio.

4. **Tailwind CSS and Cofic Setup**:
   - **Tailwind CSS**:
     ```html
     <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
     ```
   - **Cofic Script**:
     ```html
     <script src="https://cdn.cofic.io/latest/cofic.min.js"></script>
     ```

---

## 🖥️ Key Website Sections

### **Hero Section**:
This section presents a sleek introduction of the developer, focusing on minimalism:
```html
<section class="bg-white text-black h-screen flex flex-col justify-center items-center">
  <h1 class="text-5xl md:text-6xl font-bold">Crafting Clean & Minimal Websites</h1>
  <p class="text-lg md:text-xl mt-4">Frontend to Backend, I create seamless web experiences.</p>
</section>
```

### **Technologies Section**:
An easy-to-read section displaying frontend, backend, and software tools:
```html
<section class="flex flex-wrap justify-center gap-4 my-10">
  <div class="p-4 border border-gray-300 rounded-lg">
    <h3 class="text-lg font-semibold">Frontend Technologies</h3>
    <ul class="list-disc pl-5">
      <li>HTML, CSS, JavaScript</li>
      <li>Tailwind CSS</li>
    </ul>
  </div>
</section>
```

### **Featured Projects**:
Projects are displayed in a grid format with brief descriptions:
```html
<section class="grid grid-cols-1 md:grid-cols-3 gap-6 p-10">
  <div class="bg-white shadow-lg rounded-lg p-6">
    <h3 class="text-2xl font-bold mb-2">EventSphere</h3>
    <p>A dynamic event management system designed to simplify scheduling and attendance management.</p>
  </div>
  <div class="bg-white shadow-lg rounded-lg p-6">
    <h3 class="text-2xl font-bold mb-2">Music Player</h3>
    <p>A sleek, intuitive music player app with seamless playback.</p>
  </div>
</section>
```

---

## 🎨 Tailwind CSS Styling Guide

### **Fonts & Colors**:
- **Primary Font**: **Sans-serif** fonts, such as `Roboto`, are used for a professional look:
   ```css
   font-family: 'Roboto', sans-serif;
   ```
- **Colors**: A minimalist palette is used, primarily shades of white, black, and gray:
   ```css
   text-gray-900, bg-white, hover:bg-gray-700
   ```

### **Button Styling**:
Buttons utilize Tailwind's hover effects for smooth interaction:
```html
<button class="bg-gray-900 text-white hover:bg-gray-700 px-4 py-2 rounded transition duration-300 ease-in-out">
```

---

## 🚀 Deployment Instructions

- **GitHub Pages**: Push the repository and enable Pages from the settings.
- **Netlify/Vercel**: Use drag and drop to easily deploy the site.

---

## 🔗 Contact

For collaboration, feel free to contact:
- **Email**: moss@mossoni.com
- **LinkedIn**: [Connect on LinkedIn](https://linkedin.com/in/moss-oni)

---

These separate README

 files should now perfectly match the needs of each project and provide clear instructions for anyone working with or deploying the portfolios.
