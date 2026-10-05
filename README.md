# Creating a Website - HTML5 Event Development & Web Design

Welcome to the **Group Website Project** for HTML5 event development and modern web design! This repository contains the source code, design patterns, and assets for building collaborative, accessible, and responsive websites.

This project serves as a foundational resource for the [Family Media Network](https://github.com/orris0/orris0) initiative and supports HTML5 event development practices.

---

## 🌐 Community & Collaboration

### **Join Our Facebook Community**
Connect with developers and designers working on HTML5 event development and web design:

- **[HTML5 Event Development & Web Design](https://www.facebook.com/groups/html5eventdev)** — Primary group for sharing techniques, discussing event handling, and collaborative web design projects
- **[Family Media Network Community](https://www.facebook.com/groups/familymedianetwork)** — Broader community for social justice advocacy projects

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

### Prerequisites

Make sure you have Node.js and npm installed:
- [Node.js](https://nodejs.org/) (v16.x or later recommended)
- `npm` (comes bundled with Node.js)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/orris0/creating-a-website.git
   cd creating-a-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

   The site will be available at `http://localhost:3000` (or your configured port)

---

## 🎨 Features & Learning Objectives

### **HTML5 Event Development**
- Event listener patterns and best practices
- DOM manipulation using semantic HTML5
- Event delegation for scalable interactions
- Custom event handling and bubbling control

### **Modern Web Design**
- **Responsive Design:** Mobile-first approach using CSS Grid and Flexbox
- **Semantic HTML5:** Proper markup for accessibility and SEO
- **Cross-browser Compatibility:** Testing across modern browsers
- **Performance Optimization:** Fast load times and smooth interactions
- **Accessibility (WCAG 2.1):** Ensuring usability for all users

### **Interactive Components**
- Form validation and submission handling
- Dynamic content loading
- Animated transitions and effects
- User interaction feedback systems

---

## 📂 Project Structure

```text
creating-a-website/
├── index.html                 # Main landing page (HTML5 semantic markup)
├── css/
│   ├── style.css             # Primary stylesheet
│   ├── responsive.css        # Mobile and breakpoint styles
│   └── normalize.css         # Cross-browser consistency
├── js/
│   ├── main.js               # Event handlers and interactive logic
│   ├── utils.js              # Helper functions and utilities
│   └── event-handlers.js     # Custom event management
├── assets/
│   ├── images/               # Optimized imagery
│   ├── fonts/                # Web font files
│   └── icons/                # SVG and icon assets
├── package.json              # Node.js dependencies and scripts
└── README.md                 # This file
```

---

## 📚 Learning Resources

### Foundational Books & References
This project is based on industry-standard web development resources:

1. **Creating a Website: The Missing Manual** — Navigation principles and accessibility paradigms
2. **Practical HTML5 Projects** — Semantic page zoning and structured markup
3. **CSS Secrets** — Modern styling techniques and layout patterns
4. **jQuery: Novice to Ninja** — Interactive scripting and DOM manipulation

### Key Concepts

#### Event Handling
```javascript
// Event listener pattern
document.getElementById('myButton').addEventListener('click', function(event) {
  event.preventDefault();
  // Your event logic here
});

// Event delegation for dynamic elements
document.addEventListener('click', function(event) {
  if (event.target.matches('.dynamic-element')) {
    // Handle dynamic element clicks
  }
});
```

#### Semantic HTML5
```html
<header>
  <nav aria-label="Main navigation">
    <!-- Navigation content -->
  </nav>
</header>
<main>
  <article>
    <section>
      <!-- Organized content -->
    </section>
  </article>
</main>
<footer>
  <!-- Footer content -->
</footer>
```

#### Responsive CSS
```css
/* Mobile-first approach */
.container {
  width: 100%;
  padding: 1rem;
}

/* Tablet and larger */
@media (min-width: 768px) {
  .container {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
  }
}
```

---

## 🔗 Integration with Family Media Network

This repository provides the **foundational HTML5 and web design patterns** used in the [Family Media Network](https://github.com/orris0/orris0) project.

### How It's Used
- **Template structure** for semantic HTML5 pages
- **CSS patterns** for responsive, accessible layouts
- **Event handling examples** for interactive components
- **Design best practices** for social justice advocacy sites

### Related Repositories
- [orris0/orris0](https://github.com/orris0/orris0) — Family Media Network (main project)
- [academicpages.github.io](https://github.com/orris0/academicpages.github.io) — Portfolio framework
- [css-secrets](https://github.com/orris0/css-secrets) — Advanced CSS techniques
- [jquery-novice-to-ninja](https://github.com/orris0/jquery-novice-to-ninja) — Interactive scripting

---

## 🛠️ Development Workflow

### Local Testing
```bash
# Install dependencies
npm install

# Start development server
npm start

# View at http://localhost:3000
```

### Code Quality
- Follow semantic HTML5 standards
- Ensure WCAG 2.1 accessibility compliance
- Test on multiple browsers and devices
- Optimize images and assets

### Best Practices
- Use semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<article>`, `<footer>`)
- Implement proper event delegation
- Write maintainable, commented code
- Validate markup using [W3C Validator](https://validator.w3.org/)

---

## 📝 Code Examples

### HTML5 Event Handling
```html
<button id="submitBtn" aria-label="Submit form">Submit</button>

<script>
  const submitBtn = document.getElementById('submitBtn');
  submitBtn.addEventListener('click', (event) => {
    event.preventDefault();
    console.log('Button clicked!');
  });
</script>
```

### Responsive Grid Layout
```css
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
}

.grid-item {
  padding: 1rem;
  border: 1px solid #ddd;
}
```

---

## 🤝 Contributing

We welcome contributions! To contribute:

1. **Fork this repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** with clear, descriptive commits
4. **Test thoroughly** across browsers and devices
5. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Submit a Pull Request** with a detailed description

### Before Contributing
- Review our design patterns in existing files
- Follow HTML5 semantic standards
- Ensure accessibility compliance
- Test on mobile devices

### Join Our Community
Discuss your ideas and get feedback in our Facebook groups:
- [HTML5 Event Development & Web Design](https://www.facebook.com/groups/html5eventdev)
- [Family Media Network](https://www.facebook.com/groups/familymedianetwork)

---

## 📋 Checklist for Web Design Projects

- [ ] Semantic HTML5 markup used throughout
- [ ] CSS follows mobile-first approach
- [ ] Tested on at least 3 different browsers
- [ ] Responsive design tested on mobile, tablet, desktop
- [ ] WCAG 2.1 accessibility standards met
- [ ] Images optimized for web
- [ ] JavaScript is unobtrusive and performant
- [ ] Forms include proper validation
- [ ] Keyboard navigation fully functional
- [ ] Screen reader compatible

---

## 🐛 Reporting Issues

Found a bug or have a suggestion? Please open an [Issue](https://github.com/orris0/creating-a-website/issues) with:
- Clear title describing the problem
- Steps to reproduce the issue
- Expected vs. actual behavior
- Browser and device information
- Screenshots when helpful

---

## 📄 License

This project is part of the Family Media Network advocacy initiative. See LICENSE file for details.

---

## 📞 Support & Contact

- **GitHub Issues:** Report bugs and feature requests
- **Facebook Groups:** Connect with our community
- **Main Project:** [Family Media Network](https://github.com/orris0/orris0)

---

**Happy Coding! 🎨💻**

*Last Updated: October 2026*
*Built with ❤️ for HTML5 event development and accessible web design*
