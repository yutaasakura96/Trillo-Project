# 🏨 Trillo - Your All-in-One Booking App (UI Design Only)

**Trillo** is a hotel booking web application designed as a UI/UX showcase. This project focuses on the **visual design** and layout, using **Flexbox** and **SCSS** to create a responsive, modern interface. Please note, **the menus, buttons, and search bar are not functional** in this demo version—they are purely for demonstration purposes.

![Trillo Logo](img/logo.png)
![Screenshot 2024-09-04 at 15 43 28](https://github.com/user-attachments/assets/6871363a-605b-488a-89d0-6d4a370c8ca5)

🌍 Live Demo

Check out the live version of **Trillo** here: <a href="https://trilloproject-yasakura.netlify.app/" target="_blank">Trillo Live Demo</a>

## 🎯 Project Overview

The **Trillo** project is part of an **Advanced CSS and SASS** course, where the primary focus is building a **flexbox-based responsive UI**. The app is designed with clean, modern aesthetics, and it utilizes **SCSS** for maintainable and modular styles. While the interface is fully designed, **functionality is not implemented**—it is strictly a front-end demo.

## 🌟 Features

### 📱 Responsive UI Design
- Fully responsive layout built using **Flexbox**, ensuring it adapts to all screen sizes.
- **SCSS** is used for scalable and modular styles, making it easy to maintain and update.
- **CSS Variables** are employed for consistent color schemes and design elements across the project.

### 🖼️ Visual-Only Elements
- **Search Bar**: The search bar expands when focused, but it is non-functional and purely a design element.
- **Sidebar Navigation**: Includes links for **hotels**, **flights**, **car rentals**, and **tours**—these links do not redirect or trigger any actions.
- **Buttons**: Buttons like "Book now" and "Show all reviews" are for UI purposes only and do not execute any backend logic.

### 🏨 Hotel Overview
- Displays a **hotel name**, star ratings, location, and amenities list.
- **Gallery**: A simple, non-interactive image gallery that showcases hotel images.

### 👥 User Reviews and Recommendations
- **User Reviews** section presents mock reviews with user names, ratings, and profile pictures. However, this is static content with no actual review functionality.
- **Recommendations**: A section where friends' recommendations are visually displayed, but there is no backend data or logic.

## 💻 Tech Stack

- **HTML5**: For structured and semantic content.
- **SCSS**: For scalable and modular styling with variables, mixins, and responsive breakpoints.
- **Flexbox**: Used exclusively for layout design and responsiveness.
- **CSS Variables**: Ensuring consistent styling across components.

## 🛠️ Key Sections

### Header
- **Logo**: The Trillo logo is displayed prominently in the header.
- **Search Bar**: Expands when clicked or focused, but does not have search functionality.
- **User Navigation**: Includes mock notifications for bookmarks and messages, with a static profile picture.

### Sidebar
- **Sidebar Navigation**: Features links for hotels, flights, car rentals, and tours. However, these are not functional and serve as placeholders for potential future development.
- **Legal Notice**: Contains the legal and copyright information for the project.

### Hotel View
- **Hotel Overview**: Displays the hotel name, star rating, and a location button. None of these are interactive beyond the static display.
- **Gallery**: Shows hotel images in a gallery format.
- **Details & Reviews**: Contains a static list of amenities and mock reviews from users.

### Reviews
- **User Reviews**: Displays sample reviews with profile pictures, but reviews are static and non-functional.
- **Recommendations**: A simple visual display of user recommendations, with no dynamic data.

### Call to Action
- **Book Now Button**: The "Book now" button is interactive visually but does not perform any booking actions.

## 🎨 Design Details

### Colors
The project uses **CSS Variables** to define and reuse colors throughout the application:
```css
:root {
  --color-primary: #eb2f64;
  --color-primary-light: #ff3366;
  --color-primary-dark: #ba265d;
  --color-grey-light-1: #faf9f9;
  --color-grey-dark-2: #777;
}
```

### Shadows and Borders
Box shadows and borders add depth and separation to the design:
```css
:root {
  --shadow-dark: 0 2rem 6rem rgba(0, 0, 0, 0.3);
  --line: 1px solid var(--color-grey-light-2);
}
```

### Media Queries
Custom breakpoints ensure the UI adjusts across different screen sizes:
```scss
$bp-largest: 75em;
$bp-large: 68.75em;
$bp-medium: 56.25em;
$bp-small: 37.5em;
```

## 🚀 Getting Started

### Prerequisites

To run this project locally, you will need:

- A modern browser that supports **HTML5**, **CSS Flexbox**, and **CSS Variables**.
- A code editor like **VSCode** for viewing or modifying the code.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/trillo-project.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd trillo-project
   ```

3. **Open `index.html` in your browser:**
   You can open the `index.html` file directly to view the static website.

### SCSS Compilation (Optional)
If you want to modify the styles, install **Sass** and compile the SCSS files:
```bash
npm install -g sass
sass --watch scss/main.scss css/style.css
```

## 📄 License

This project is licensed under the **MIT License**.

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch.
3. Submit a pull request for review.

---

Developed by **Yuta Asakura** as part of the **Advanced CSS and SASS** course by **Jonas Schmedtmann**.

---

### ⚠️ Important: Non-Functional Elements

All menus, buttons, and the search bar in this project are for **visual purposes only**. They do not have any interactive functionality, and the project is focused on **UI/UX design** using Flexbox and SCSS.

---
