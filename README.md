# Construkta S.R.O. Website

This is the official website for **Construkta S.R.O.**, a construction company based in Slovakia. The website is designed to showcase the company's services, history, and values in a modern, professional manner.

## Features

*   **Modern Design**: A sleek dark grey and orange theme reflecting the construction industry.
*   **Bilingual Support**: Fully translated into **Slovak (SK)** and **Hungarian (HU)**. Language preference is saved globally using `localStorage`.
*   **Responsive Layout**: Optimized for desktops, tablets, and mobile devices.
*   **Interactive Elements**: Mobile navigation menu, hover effects, and smooth transitions.

## Technologies Used

*   **HTML5**: Semantic markup for structure.
*   **CSS3**: Custom styling with Flexbox and Grid (no external frameworks).
*   **JavaScript**: Vanilla JS for language switching logic and mobile menu interaction.
*   **Font Awesome**: For icons.
*   **Google Fonts**: 'Inter' font family.

## How to Run

### Option 1: Direct File Access (Quickest)
Simply double-click the `index.html` file to open it in your default web browser.

**Note**: Some browsers may restrict `localStorage` functionality when opening files directly from the file system (`file://` protocol). If language switching doesn't persist across pages, try Option 2.

### Option 2: Local Development Server (Recommended)
To ensure all features (especially language persistence) work correctly, it is best to serve the site via a local web server.

**Using Python (if installed):**
1.  Open your terminal/command prompt in the project directory.
2.  Run: `python3 -m http.server`
3.  Open your browser and go to `http://localhost:8000`.

**Using VS Code Live Server:**
1.  Install the "Live Server" extension in VS Code.
2.  Right-click `index.html` and select "Open with Live Server".

## Project Structure

*   `index.html`: Homepage.
*   `about.html`: Company history and values.
*   `services.html`: List of services.
*   `contact.html`: Contact form and details.
*   `css/style.css`: Main stylesheet.
*   `js/main.js`: Core logic (language switcher, mobile menu).
*   `js/lang.js`: Translation dictionary.
*   `images/`: Logo and other assets.
