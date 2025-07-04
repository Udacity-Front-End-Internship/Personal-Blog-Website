
![image](https://github.com/user-attachments/assets/c450047c-153f-4fc7-9161-ebd78bca64a0)


# Pen & Paper Blog

A modern, responsive personal blog website project built as part of the Udacity Front End Web Developer Nanodegree. This website showcases HTML and CSS skills, custom layouts, and a clean, accessible design. It includes a homepage with featured posts, individual blog post pages, and a modular CSS structure using Flexbox and Grid.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Development Strategy](#development-strategy)
---

## Project Overview

This project demonstrates the creation of a personal blog website from scratch, focusing on proper HTML/CSS structure, layout, and responsive design principles. It is part of Udacity's *Front End Web Developer* program, Course 3: "CSS, Website Layout, Website Components".

- **Course:** Udacity Front End Web Developer Nanodegree
- **Project:** Personal Blog Website
- **Skills Practiced:** HTML, CSS, Flexbox, Grid, Responsive Design

## Features

- Responsive layout using Flexbox and CSS Grid
- Modular CSS file structure
- Homepage with a hero section and recent blog posts
- Individual blog post page with author info and related resources
- Navigation bar, search bar, and footer
- Clean, accessible HTML markup
- Example images and icons for posts and social links

## Getting Started

To get a local copy up and running:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Udacity-Front-End-Internship/Personal-Blog-Website.git
   cd Personal-Blog-Website
   ```

2. **Open `index.html` in your browser:**
   - No build tools or dependencies required.
   - All styling is handled via CSS files in `assets/css/`.

## Project Structure

```
Personal-Blog-Website/
├── index.html              # Main homepage
├── blog-post.html          # Example individual blog post page
├── assets/
│   ├── images/             # All images and icons (logo, post images, author, etc.)
│   └── css/
│       ├── main.css        # Main CSS file (imports modular CSS files)
│       ├── core.css
│       ├── home.css
│       ├── blog-post.css
│       ├── page-layout/
│           ├── header.css
│           ├── footer.css
│           └── responsive.css
```

- **HTML Files:**  
  - `index.html` — Homepage with hero section and recent posts  
  - `blog-post.html` — Individual, detailed blog post

- **CSS Files:**  
  - Modularized by component and page layout for easy editing

- **Images:**  
  - Logos, author photos, blog post images, and icons in `assets/images/`

## Development Strategy

- **Semantic HTML:** All pages use meaningful HTML elements for accessibility and SEO.
- **Modular CSS:** Styles are organized by component and page for maintainability.
- **Responsive Design:**  
  - Mobile-first approach  
  - Flexbox and Grid used for layout  
  - `responsive.css` for device-specific tweaks
- **Style Guide:** Consistent fonts, colors, and spacing across pages.
