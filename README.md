# Bloom-Scrolling-Website

Bloom Scrolling Website

🌸 Overview

The Bloom Scrolling Website is a visually engaging, smooth-scrolling web application built using React.js, JavaScript, and Module CSS. This project demonstrates seamless scrolling animations, dynamic content transitions, and an immersive user experience. The website is designed to showcase elegant bloom effects while scrolling, creating a visually appealing interface.

🚀 Live Demo: https://bloomscrollingpradeepb.netlify.app/

📌 Features

✅ Smooth Scrolling Animation – Uses optimized scrolling effects to enhance the browsing experience.✅ Blooming Effects on Scroll – Beautiful animation effects that give elements a blooming appearance when they come into view.✅ React Functional Components – Built using React functional components for modularity and reusability.✅ CSS Modules for Styling – Encapsulated styling with CSS Modules to prevent global scope conflicts.✅ Fully Responsive Design – Optimized for different screen sizes and devices.✅ Performance Optimizations – Efficient rendering techniques to ensure a lag-free experience.✅ Modern UI/UX – Aesthetic design with smooth transitions and engaging user interactions.

🎯 Technologies Used

This project leverages modern front-end technologies:

React.js – Core framework for building the UI components.

JavaScript (ES6+) – Used for interactivity and dynamic behavior.

CSS Modules – Scoped CSS for better maintainability and styling control.


React Intersection Observer – To detect element visibility and trigger animations.

Netlify – For deployment and hosting.

📜 Usage Guide

Navigate Through the Website: Scroll vertically to see the smooth scrolling effects in action.

Observe Blooming Effects: As you scroll, elements will animate into view with blooming effects.

Responsive Layout: Resize the browser or use a mobile device to see how the layout adapts.

Custom Styling: Modify the CSS module files in the styles/ directory to change the appearance.

🎨 Customization

You can tweak the scrolling effects and animations:

Modify the bloomEffect.module.css file to adjust animation styles.

Adjust the animation timing in BloomEffect.js.

Add new sections by creating new Section.js instances in App.js.

🚀 Deployment

This project is deployed on Netlify. To deploy your own version:

Push the project to a GitHub repository.

Go to Netlify and connect your repository.

Set the build command as npm run build.

Deploy and get a live URL instantly!

🛠 Known Issues & Fixes

Issue: Laggy Scrolling on Some Browsers

🔹 Solution: Ensure will-change: transform is applied to animated elements in CSS.

Issue: Animation Not Triggering

🔹 Solution: Check if the IntersectionObserver is properly detecting visibility.


📜 License

This project is open-source and available under the MIT License.



