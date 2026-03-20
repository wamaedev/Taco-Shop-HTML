# The Little Taco Shop

A multi-page, static website for a fictional taco shop, "The Little Taco Shop." This project demonstrates fundamental HTML5 structure and content, including semantic elements, forms, tables, and multimedia, forming a complete and cohesive brand presence.

## 📖 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [File Structure](#file-structure)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Page Details](#page-details)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## 🔍 Project Overview

This project consists of three interconnected HTML pages that together create a complete online presence for "The Little Taco Shop." It's designed as a practical demonstration of core web development concepts, showcasing how to structure a small business website with informational content, a menu, contact options, and business hours.

## ✨ Features

- **Multi-Page Structure**: A cohesive website with a home page, contact page, and hours page.
- **Semantic HTML**: Uses `<header>`, `<main>`, `<footer>`, `<article>`, `<section>`, `<nav>`, and `<aside>` for accessible and meaningful structure.
- **Navigation**: A consistent navigation bar across all pages allows users to easily move between sections.
- **Menu Display**: Features a complex HTML table to present taco menu items with quantities and pricing.
- **Contact Form**: Includes a functional form with validation, using `httpbin.org` for testing submissions.
- **Multimedia**: Integrates images with appropriate `alt` text, titles, and captions using `<figure>` and `<figcaption>`.
- **Interactive Elements**: Uses `<details>` and `<summary>` for an expandable trivia section.
- **Accessibility Features**: Employs `abbr` tags, `scope` attributes for tables, `aria`-implicit labels, and `lang` declarations.
- **Responsive Meta Tag**: Includes the viewport meta tag for better display on mobile devices.

---

## 📁 File Structure

```
little-taco-shop/
│
├── index.html # Home page with about section and menu
├── contact.html # Contact page with a form and location
├── hours.html # Store hours page
├── css/
│ └── style.css # External stylesheet for the website
│
└── img/ # Directory for all image assets
├── taco.png # Favicon for the website
├── Tacos&Drinks.jpeg # Hero image on the home page
├── Tacoscloseup.jpeg # Image on the contact page
└── tacostray.jpeg # Image on the hours page
```

---


## 🛠 Technologies Used

- **HTML5**: The core structure for all pages, utilizing semantic elements.
- **CSS3**: External styling (referenced but not provided).
- **HTTPbin**: A testing service used to simulate form submissions.

## 🚀 Setup and Installation

1.  **Clone or download** the project files.
2.  **Create the required folder structure** as shown above in your project directory.
3.  **Add your images** to the `/img` folder. Ensure the filenames match those referenced in the HTML files (e.g., `Tacos&Drinks.jpeg`).
4.  **Create or customize** the `style.css` file inside the `/css` folder to add your own styling.
5.  **Open** any of the `.html` files in your web browser to view the website.

## 📄 Page Details

### `index.html` (Home Page)
- **Hero Section**: Features a welcoming title and a main image.
- **About LTS**: Provides the shop's founding story and an interactive trivia section about tacos in the USA.
- **Menu**: A detailed table displaying the menu with prices for crunchy and soft tacos in different quantities.

### `contact.html` (Contact Page)
- **Contact Form**: A user-friendly form to send a message. It includes fields for name, email, and a message text area. The form submits data to `httpbin.org` for testing.
- **Location**: Displays the shop's physical address and a clickable phone number link (`tel:`).

### `hours.html` (Hours Page)
- **Operating Hours**: Clearly lists the weekly opening hours using a definition list (`<dl>`).
- **Consistent Branding**: Maintains the same header and footer as the other pages for a unified experience.

## 💻 Usage

1.  **Browse the Site**: Use the navigation bar at the top of each page to switch between the home, menu (via home page), store hours, and contact pages.
2.  **View the Menu**: On the home page, scroll to the "Our Menu" section to see the pricing table.
3.  **Test the Contact Form**:
    - Fill out the form on the `contact.html` page.
    - Clicking the **Send** button will submit the data to `httpbin.org/get`, where you can see your input in the response.
    - Use the **Reset** button to clear all fields.
4.  **Contact the Shop**: Use the address or click the phone number provided on the contact page.
5.  **Return to Top**: Use the "Back To the Top" link at the bottom of the home and hours pages.

## 👤 Credits

**Author**: Presbury Wamae

## 📄 License

This project is open-source and intended for educational and portfolio purposes.

---

*Last updated: 2024*