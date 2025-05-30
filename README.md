# PersonalPortfolio
Al Zabir Portfolio Website
A modern, responsive portfolio website showcasing Al Zabir's skills, projects, and contact information.

📋 Features

Responsive Design: Fully responsive layout that works on all devices (mobile, tablet, desktop)
Modern UI/UX: Clean and professional design with smooth animations
Navigation: Fixed navigation bar with mobile hamburger menu
Sections Include:

Hero section with call-to-action
About section with personal information
Skills section with animated progress bars
Projects showcase with filterable categories
Contact form with validation
Footer with social media links


Interactive Elements: Smooth scrolling, hover effects, and form validation
Performance Optimized: Fast loading times and optimized assets

🛠️ Technologies Used

HTML5
CSS3 (External stylesheet)
JavaScript (Vanilla JS)
FontAwesome for icons
Google Fonts

🚀 Setup and Installation

Clone the repository
git clone https://github.com/Zabir03/PersonalPortfolio.git
cd portfolio-website

Project Structure
portfolio-website/
├── index.html
├── css/
│   ├── style.css
│   └── responsive.css
├── js/
│   └── script.js
├── images/
│   ├── profile.jpg
│   ├── projects/
│   │   ├── project1.jpg
│   │   ├── project2.jpg
│   │   └── project3.jpg
│   └── icons/
└── README.md

Open in Browser

Simply open the index.html file in your preferred browser
Alternatively, use a local development server like Live Server for VS Code



📱 Responsive Breakpoints

Mobile: up to 480px
Tablet: 481px to 768px
Desktop: 769px and above

✨ Customization
Colors
The website uses a color scheme that can be easily customized in the css/style.css file:
css:root {
  --primary-color: #3498db;
  --secondary-color: #2d3e50;
  --text-color: #333;
  --light-bg: #f5f5f5;
  --white: #ffffff;
  /* Add more color variables as needed */
}
Content

Update the personal information in the HTML file
Replace profile image in the images folder
Add your own projects with descriptions and images
Update contact information and social media links

Fonts
The website uses Google Fonts, which can be changed in the CSS file:
css@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600&family=Raleway:wght@700&display=swap');

body {
  font-family: 'Open Sans', sans-serif;
}

h1, h2, h3, h4 {
  font-family: 'Raleway', sans-serif;
}
📝 External CSS Implementation
This portfolio website uses external CSS files for better organization and maintainability:

style.css: Contains the main styling rules for the website

Base styles and typography
Layout and grid systems
Component styling (buttons, cards, forms)
Section-specific styles
Animations and transitions


responsive.css: Contains media queries for responsive design

Mobile-first approach
Tablet breakpoints
Desktop breakpoints
Print styles



To implement the external CSS structure:

Create a css folder in your project root
Create the CSS files:
touch css/style.css css/responsive.css

Link them in the HTML head section:
html<head>
  <!-- Other meta tags -->
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="css/responsive.css">
</head>


🔧 Future Improvements

 Add dark/light mode toggle
 Implement filtering functionality for projects
 Add blog section
 Improve accessibility features
 Add language selector for internationalization

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
👨‍💻 Author
Al Zabir

Website: alzabir.com
GitHub: [text](https://github.com/Zabir03)
LinkedIn: Al Zabir


⭐️ If you find this project helpful, please consider giving it a star on GitHub! ⭐️