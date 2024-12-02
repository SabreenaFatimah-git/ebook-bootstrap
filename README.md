# WebWise Pro - The Book

## 1. Description
WebWise Pro - The Book is a responsive web application built using **Bootstrap** for layout and styling. It showcases a mobile-first design and includes interactive features like tooltips and customizable UI components. The project is aimed at providing an example of using Bootstrap to create clean, functional, and responsive websites.

## 2. Features
- **Responsive Layout**: Utilizes **Bootstrap**'s grid system for a mobile-first, responsive design.
- **Interactive Tooltips**: Tooltips are initialized on elements with the `.toolt` class to provide contextual information on hover.
- **Custom Styles**: A custom `main.min.css` file has been included for design customizations.
- **Bootstrap Icons**: Scalable vector icons from **Bootstrap Icons** are used for UI elements like buttons and navigation.
- **Cross-Browser Compatibility**: Ensures compatibility with all modern browsers for consistent user experience.

## 3. Technologies Used
- **HTML5**: The structural markup language used for the website.
- **CSS3**: For custom styling, including layout and appearance adjustments.
- **Bootstrap 5**: Frontend framework for responsive design and ready-made components.
- **Bootstrap Icons**: A library for vector icons that scale without losing quality.
- **JavaScript**: Used for initializing Bootstrap tooltips and interactivity.

## 4. Installation

To view the project locally, follow these steps:

1. Clone the repository to your local machine:

   git clone https://github.com/SabreenaFatimah-git/webwisePro-bootstrap.git

## 5. Open the E-book.html file in your browser to view the project.

   There are no additional setup steps required.

## 6. Folder Structure:
/ebook-bootsrap
│
├── /assets
│   ├── /css
│   │   └── main.min.css  (Custom Styles)
│   ├── /images
│   └── /js
│
├── /E-book.html
└── README.md

/assets/css: Contains the custom main.min.css file for styling the project.
/assets/js: This folder contains JavaScript files for additional interactivity.
/images: Folder for any images used in the project.
index.html: The main HTML file for the project.
README.md: This file providing project details and documentation.

## 7. JavaScript and Tooltips
The project includes Bootstrap's JavaScript bundle for interactivity and includes Popper.js (required for components like dropdowns and tooltips):

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
        crossorigin="anonymous"></script>

Tooltips Initialization:
The project includes a JavaScript snippet that initializes tooltips for any element with the toolt class:

<script>
    const tooltips = document.querySelectorAll('.toolt');
    tooltips.forEach(t => {
        new bootstrap.Tooltip(t);
    });
</script>
This allows elements with the toolt class to show a tooltip when hovered over.
