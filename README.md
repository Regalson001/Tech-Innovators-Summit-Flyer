# 🚀 Tech Innovators Summit 2026 — Event Flyer

A modern, responsive event flyer web application built with **semantic HTML5 and CSS3**. This project was developed as part of practical front-end web development training, with a focus on responsive design, viewport-relative sizing, dynamic CSS calculations, and clean, maintainable code.

The flyer demonstrates how fundamental web technologies can be used to create an engaging event presentation that adapts to different screen sizes while maintaining a clear visual hierarchy.

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Implementation Highlights](#-implementation-highlights)
- [Responsive Design](#-responsive-design)
- [Accessibility and Best Practices](#-accessibility-and-best-practices)
- [Learning Objectives](#-learning-objectives)
- [Future Improvements](#-future-improvements)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

## 🎯 Overview

The **Tech Innovators Summit 2026 — Event Flyer** is a front-end project designed to present event information through a structured, visually appealing, and responsive web layout.

The project emphasizes core web development principles, including semantic markup, relative CSS units, dynamic sizing, and consistent visual styling. It provides practical experience in building web interfaces that are readable, maintainable, and adaptable to different viewport dimensions.

### Project Goals

- Build a well-structured web page using semantic HTML5.
- Apply modern CSS techniques to create an attractive event flyer.
- Use viewport-relative units to support flexible layouts.
- Implement the CSS `calc()` function for dynamic dimension calculations.
- Develop good habits in code organization, accessibility, and responsive design.

## ✨ Features

- **Semantic HTML5:** Uses meaningful structural elements such as `<header>`, `<main>`, `<section>`, heading elements, and `<hr>` where appropriate.
- **Responsive Sizing:** Uses viewport-relative units such as `vw` to help elements scale with the browser viewport.
- **Dynamic CSS Calculations:** Applies the `calc()` function to combine CSS values and calculate dimensions dynamically.
- **Flexible Layouts:** Uses percentage-based widths and relative measurements to support adaptable page elements.
- **Modern Visual Styling:** Incorporates a coordinated color palette, spacing, alignment, and box shadows to establish a clear visual hierarchy.
- **Organized Codebase:** Separates page structure from presentation using dedicated HTML and CSS files.
- **Accessibility Awareness:** Encourages logical heading order, readable content, and semantic document structure.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Defines the page structure and event content. |
| CSS3 | Controls layout, typography, colors, spacing, and visual effects. |
| Responsive CSS | Helps the flyer adapt to different viewport sizes. |
| CSS `calc()` | Calculates dimensions by combining CSS values. |
| Viewport Units | Supports sizing relative to the browser viewport. |
| Git and GitHub | Supports version control and project hosting. |

## 📁 Project Structure

```text
Tech-Innovators-Summit-Flyer/
│
├── index.html      # Main HTML document and flyer content
├── styles.css      # Responsive styling and layout rules
└── README.md       # Project documentation
```

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites

You will need:

- A modern web browser, such as Chrome, Firefox, Edge, or Safari.
- A code editor, such as Visual Studio Code, if you want to inspect or modify the source files.
- Git, if you plan to clone the repository from GitHub.

### 1. Clone the Repository

Replace the placeholder below with your actual GitHub repository URL:

```bash
git clone <your-repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd Tech-Innovators-Summit-Flyer
```

### 3. Open the Project

Open `index.html` directly in your browser to view the flyer.

Alternatively, open the project folder in Visual Studio Code and use the Live Server extension for convenient local previewing during development.

### 4. Customize the Flyer

Edit `index.html` to update the event content and `styles.css` to adjust the layout, colors, typography, and responsive behavior.

## 💡 Implementation Highlights

### Semantic HTML5

The page uses semantic elements to organize content into meaningful sections. This improves document readability and helps browsers and assistive technologies interpret the structure.

### Viewport-Relative Units

CSS viewport units, such as `vw`, allow selected dimensions to scale relative to the viewport width.

```css
.example-element {
  width: 80vw;
}
```

This example sets the element's width to 80% of the viewport width. Actual project values may differ depending on the design.

### Dynamic Dimension Calculations

The CSS `calc()` function can combine different CSS units to calculate dimensions dynamically.

```css
.example-container {
  min-height: calc(100vh - 100px);
}
```

Here, `100vh` represents the viewport height, while `100px` is subtracted to account for a fixed amount of vertical space.

**Implementation note:** The example illustrates the technique described in this project. Keep the actual values aligned with the layout and spacing rules in `styles.css`.

### Relative Widths and Dividers

Percentage-based widths help elements scale in relation to their containing block.

```css
.example-divider {
  width: 80%;
  margin-inline: auto;
}
```

This example creates a centered divider that occupies 80% of its containing block's width.

## 📱 Responsive Design

Responsive design helps ensure that a web page remains usable across desktop computers, laptops, tablets, and mobile devices.

This project explores responsive techniques such as:

- Using relative and viewport-based units where appropriate.
- Applying flexible widths instead of relying entirely on fixed dimensions.
- Maintaining consistent spacing and alignment.
- Using CSS media queries when layout adjustments are needed at specific breakpoints.
- Testing content at narrow and wide viewport sizes to identify overflow and readability issues.

For production-quality responsiveness, test the flyer at multiple screen widths and use media queries or `clamp()` where fixed viewport-relative sizing alone does not provide sufficient control.

## ♿ Accessibility and Best Practices

The project provides an opportunity to practice accessible and maintainable front-end development.

Recommended practices include:

- Use headings in a logical hierarchy.
- Choose semantic HTML elements according to their intended meaning.
- Maintain sufficient contrast between text and background colors.
- Ensure that event details remain readable on smaller screens.
- Avoid using color as the only way to communicate important information.
- Use meaningful text for links and descriptive alternative text for informative images.
- Keep HTML structure and CSS presentation organized and easy to maintain.

## 🎓 Learning Objectives

Through this project, the following front-end development concepts can be practiced:

- Writing semantic HTML5 markup.
- Styling web interfaces with CSS3.
- Understanding viewport-relative units such as `vw` and `vh`.
- Using `calc()` to create dynamic CSS dimensions.
- Applying percentage-based sizing for flexible layouts.
- Establishing visual hierarchy through spacing, alignment, typography, and color.
- Understanding the importance of responsive design and accessibility.
- Organizing a small front-end project for readability and maintainability.

## 🔮 Future Improvements

Potential enhancements for future versions include:

- **Improved Mobile Layouts:** Add carefully selected media queries for smaller screens.
- **Responsive Typography:** Use `clamp()` to balance minimum, preferred, and maximum font sizes.
- **Event Details:** Include the event date, venue, agenda, speakers, and registration information as required.
- **Interactive Registration:** Add a registration form or a clearly labeled call-to-action link.
- **Visual Enhancements:** Introduce event branding, optimized images, and refined typography.
- **Cross-Browser Testing:** Verify consistent presentation across modern browsers.
- **Deployment:** Publish the finished flyer using GitHub Pages or another static hosting service.

These are suggested improvements and do not imply that the features are already implemented.

## 🤝 Contributing

Suggestions and improvements are welcome.

To contribute:

1. Fork the repository.
2. Create a feature branch.

   ```bash
   git checkout -b feature/your-improvement
   ```

3. Make your changes and test the page.
4. Commit your changes.

   ```bash
   git commit -m "Improve responsive flyer layout"
   ```

5. Push your branch to your fork.

   ```bash
   git push origin feature/your-improvement
   ```

6. Open a pull request describing your changes.

## 📄 License

No license has been specified for this project yet. If you intend to make the source code available for reuse, consider choosing an appropriate open-source license and adding a `LICENSE` file to the repository.

Until a license is added, do not assume that others have permission to reuse, modify, or redistribute the code.

## 👨‍💻 Author

**Stephen Oyugi**

- GitHub: [@Regalson001](https://github.com/Regalson001)

---

<p align="center">
  Built with HTML5 and CSS3 as part of a front-end web development learning journey.
</p>

<p align="center">
  <strong>Learning by building. Improving with every project.</strong>
</p>
