# The Nature Website

A static website built for nature enthusiasts to explore and book adventurous tours. The site features a modern, responsive design with smooth animations and a clean layout.

![License](https://img.shields.io/badge/license-Not%20specified-lightgrey)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

## 📖 Description

**The Nature Website** is a front-end project that showcases exciting nature tours, customer testimonials, and a booking form. It is designed to inspire people to connect with nature and provides a seamless browsing experience for potential travelers. The repository currently contains the source code for the landing page, including all styling and assets.

## ✨ Features

- **Hero Section** – A visually striking banner with a call-to-action button.
- **Tour Listings** – Detailed cards for popular tours (e.g., The Sea Explorer, The Forest Hiker) with pricing, duration, group size, and difficulty level.
- **Testimonials** – Real-life stories from customers who have experienced the tours.
- **Booking Form** – A simple form to capture user details for tour reservations.
- **Responsive Navigation** – A fully functional hamburger menu for mobile devices.
- **Animations** – Subtle CSS animations that enhance user interaction.
- **PWA Ready** – Includes a web manifest and icons for progressive web app support.

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure of the web page |
| **CSS3** | Styling, custom properties (variables), Flexbox/Grid, animations |
| **VS Code** | Development environment (includes `.vscode/settings.json`) |
| **GitHub Pages** | Potential hosting platform (static site) |

> **Note:** No JavaScript framework or library is used; the site is purely HTML/CSS with CSS-driven interactivity (e.g., the navigation toggle via checkbox hack).

## 📂 Project Structure

```
The-Nature-Website/
├── .vscode/
│   └── settings.json          # VS Code workspace settings
├── public/
│   ├── android-chrome-192x192.png
│   ├── android-chrome-512x512.png
│   ├── apple-touch-icon.png
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── favicon.ico
│   ├── site.webmanifest       # PWA manifest
│   └── resources/
│       ├── css/
│       │   ├── animation.css
│       │   ├── grid.css
│       │   ├── main.css       # Primary stylesheet (imports others)
│       │   └── row-col.css
│       ├── icons/             # SVG icons used in the UI
│       └── images/            # Hero images, logo, tour photos, etc.
├── index.html                 # Main landing page
└── README.md                  # This file
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) A local development server such as [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VS Code

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ChethanPutran/The-Nature-Website.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd The-Nature-Website
   ```

3. **Open `index.html` in your browser**
   - Simply double-click the `index.html` file, or
   - Use a local server for a more production-like experience.

### Running with Live Server (VS Code)

If you have the Live Server extension installed:

1. Open the project folder in VS Code.
2. Right-click on `index.html` and select **"Open with Live Server"**.
3. The site will open at `http://127.0.0.1:5500`.

## 🎨 Usage

- **Navigation** – Click the hamburger icon (top-right) to open the menu on mobile.
- **Booking** – Scroll to the "Start booking now!" section and fill out the form.
- **Tours** – Browse the three tour cards to see pricing and details.
- **Testimonials** – Read real customer experiences at the bottom of the page.

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the website:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

Please ensure your code follows the existing style and includes appropriate comments.

## 📄 License

This project does **not** currently include a license file. If you intend to use this code for commercial purposes, please contact the author for permission.
