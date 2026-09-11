# Futras – Fitness & Nutrition

A modern, responsive **Fitness & Nutrition website** built with **HTML5, CSS3, and Vanilla JavaScript**. Futras presents fitness courses, nutrition programs, instructor information, blog articles, mobile-app promotion, and newsletter subscription in a clean and engaging landing-page layout.

---

## 🌐 Live Demo

Experience the Futras – Fitness & Nutrition website live:

**🔗 Live Demo:** [Futras – Fitness & Nutrition](https://futras-fitness-and-nutrition.netlify.app/)

---

## 🌐 Overview

**Futras** is designed as a fitness and nutrition learning platform where users can:

- Explore fitness and nutrition courses
- Browse specialized programs for men, women, and beginners
- Learn about experienced instructors
- View course pricing, duration, and lecture information
- Read nutrition-related blog articles
- Download the mobile application
- Subscribe to a newsletter
- Navigate easily across mobile, tablet, and desktop devices

The website uses a responsive, section-based layout with smooth visual interactions and scroll-based animations.

---

## ✨ Features

### 🏠 Hero Section

- Fitness and nutrition-focused introduction
- Full-width background image
- Primary **Start Course** call-to-action
- Social media links
- Responsive typography and spacing

### 🎯 Service Section

Provides three major course categories:

- Women's Course
- Basic Course
- Men's Course

Each service card includes:

- Course icon
- Description
- Hover effects
- Navigation button

### 👨‍🏫 About Section

- Instructor introduction
- 25+ years of experience highlight
- 100+ courses information
- Instructor image
- **Meet Instructor** call-to-action
- Decorative animated shapes

### 📚 Course Section

Displays available fitness and nutrition courses with:

- Course image
- Price
- Instructor name
- Course title
- Course duration
- Number of lectures

The course layout automatically adapts to different screen sizes.

### 📝 Blog Section

Displays the latest nutrition articles with:

- Publication date
- Author
- Likes and shares
- Article title
- Short description
- Interactive hover effects

### 📱 App Section

Promotes the Futras mobile application with:

- App introduction
- Google Play Store button
- Apple App Store button
- Responsive app promotion card

### 🦶 Footer

The footer contains:

- Newsletter subscription form
- Course links
- Help and support links
- Opening hours
- Location information
- Copyright information
- Terms of Service
- Privacy Policy
- Sitemap
- Security links

---

## 🎨 Design & Styling

The website uses a custom CSS architecture with reusable classes and CSS custom properties.

### Main Design Features

- Responsive grid layouts
- CSS transitions and hover effects
- Custom typography using **Montserrat** and **Playfair Display**
- CSS variables for colors, typography, spacing, and transitions
- Animated decorative elements
- Mobile-first responsive design
- Section reveal animations
- Interactive buttons and cards

The design uses a fitness-oriented color palette including **blue-green, orange, white, and neutral tones**.

---

## 📱 Responsive Design

The stylesheet contains multiple responsive breakpoints:

| Breakpoint | Purpose                                     |
| ---------- | ------------------------------------------- |
| `< 575px`  | Mobile layout                               |
| `575px+`   | Larger mobile / small tablet                |
| `768px+`   | Tablet layout                               |
| `992px+`   | Desktop navigation and multi-column layouts |
| `1200px+`  | Large desktop optimization                  |

### Larger Screen Improvements

At larger screen sizes:

- Navigation changes from a mobile menu to desktop navigation
- Course, service, and blog grids expand to multiple columns
- About section becomes a two-column layout
- Footer becomes a multi-column layout
- Typography and spacing scale up
- Desktop hover interactions become more prominent

---

## ⚙️ JavaScript Functionality

The website uses **Vanilla JavaScript** without any JavaScript framework.

### Mobile Navigation

The navigation menu can be opened and closed using the menu buttons and overlay. Navigation links automatically close the mobile menu after selection.

### Sticky Header

After scrolling approximately `100px`, the header receives an `active` class, allowing CSS to change its appearance.

### Back-to-Top Button

The back-to-top button becomes visible after scrolling down and links back to the page's `#top` element.

### Scroll Reveal

Sections containing the `data-section` attribute receive the `active` class when they reach approximately the middle of the viewport. CSS then controls their reveal animation.

### Data Attributes

JavaScript uses custom HTML attributes such as:

```html
data-navbar data-nav-toggler data-nav-link data-header data-back-top-btn
data-section
```

This keeps JavaScript behavior separate from styling classes and makes the code easier to maintain.

---

## 📂 Project Structure

```html
Futras/ │ ├── index.html ├── favicon.svg │ ├── assets/ │ ├── css/ │ │ └──
style.css │ │ │ ├── js/ │ │ └── script.js │ │ │ └── images/ │ ├──
hero-banner.jpg │ ├── about-banner.jpg │ ├── about-shape-1.png │ ├──
about-shape-2.png │ ├── courses-1.jpg │ ├── courses-2.jpg │ ├── courses-3.jpg │
├── courses-4.jpg │ ├── courses-5.jpg │ ├── courses-6.jpg │ ├── service-1.svg │
├── service-2.svg │ ├── service-3.svg │ ├── play-store.jpg │ └── app-store.jpg │
└── README.md
```

---

## 🛠️ Technologies Used

- **HTML5** – Semantic website structure
- **CSS3** – Styling, responsive layouts, animations, and transitions
- **JavaScript (ES6)** – Navigation, scrolling, and interactive behavior
- **Ionicons** – Interface and social icons
- **Google Fonts** – Montserrat and Playfair Display
- **CSS Grid & Flexbox** – Responsive layouts

---

## ♿ Accessibility-Friendly Design

The website follows accessibility-friendly practices to provide a better experience for all users.

- Uses semantic HTML5 elements such as `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`
- Provides descriptive `alt` text for meaningful images
- Uses `aria-label` and `aria-hidden` attributes where appropriate
- Maintains clear heading hierarchy throughout the page
- Provides accessible navigation controls for the mobile menu
- Supports keyboard-friendly interactive elements
- Uses sufficient color contrast for important content and controls
- Includes descriptive text for buttons and navigation links
- Uses responsive layouts for different screen sizes and devices
- Respects meaningful content structure for assistive technologies

---

## 🚀 Getting Started

No framework or build process is required.

1. Clone the Repository

```js
git clone https://github.com/your-username/futras-fitness.git
```

2. Open the Project

```js
cd futras-fitness
```

3. Run the Website
   Open index.html directly in your browser, or use a local development server such as VS Code Live Server.

---

## 📌 Future Improvements

The current project is primarily a frontend website. Possible future improvements include:

- Connect course cards to real course pages
- Add user authentication and registration
- Implement a course enrollment system
- Connect newsletter subscription to a backend service
- Add functional contact forms
- Add a real blog/article management system
- Integrate payment functionality
- Connect Play Store and App Store buttons to actual applications
- Improve accessibility and SEO
- Replace scroll-event reveal logic with `IntersectionObserver`

---

## 🙏 Acknowledgement

This project was developed as a frontend practice and portfolio project using **HTML5, CSS3, and Vanilla JavaScript**.

Special thanks to the open-source resources, documentation, icons, fonts, and learning materials that helped in designing and developing the Futras – Fitness & Nutrition website.

### Resources

- **Ionicons** – For interface and social media icons
- **Google Fonts** – For Montserrat and Playfair Display typography
- **MDN Web Docs** – For HTML, CSS, and JavaScript references
- **Open-source web development resources** – For design and development inspiration

Thank you to everyone who contributes to the web development community and makes learning resources freely available.

---

❤️ Futras – Fitness & Nutrition

Built using HTML5, CSS3, and Vanilla JavaScript, with a focus on responsive design, clean UI, accessibility-friendly structure, and interactive user experience.
