# Rai-Construction-Solution-

LIVE LINK : https://devanshu896.github.io/Rai-Construction-Solution-/

![App Screenshot](https://github.com/Devanshu896/Rai-Construction-Solution-/blob/main/Rai%20Construction%20Solution%20SS.png)

## RAI Construction Solutions - Official Website

This project is the official website for "RAI Construction Solutions," a company offering complete construction consultancy services. The site is a single-page application (SPA) with multiple sections, designed to be modern, professional, and fully responsive. It showcases the company's services, projects, client testimonials, and contact information with a focus on a smooth user experience.

***

### Key Features

* **Responsive Design**: The website is built to provide a seamless user experience across all devices, including desktops, tablets, and mobile phones, with a fluid layout and a dedicated mobile navigation menu.
* **Sticky Header**: A fixed navigation bar stays at the top of the page as the user scrolls, changing its background color for better readability on different sections.
* **Smooth Scrolling**: Navigation links, a "scroll down" arrow on the hero section, and a "back to top" button all use smooth scrolling to navigate between sections.
* **Dynamic Content Filtering**: The "Projects" section includes a filter functionality, allowing users to view projects by category (e.g., Residential, Commercial, Renovation) without reloading the page.
* **Interactive Elements**: Hover effects, button animations, and subtle transformations are used on various elements like service cards, project cards, and social media icons to enhance user engagement.
* **"Back to Top" Button**: A button appears in the bottom-right corner when the user scrolls down, providing a convenient way to return to the top of the page.
* **Contact Form & Map Integration**: A simple contact form allows users to send inquiries, and an embedded Google Maps iframe shows the company's location.

***

### Technologies Used

### Frontend
* **HTML5**: The foundational markup language used to structure the entire website.
* **CSS3**: All styling, layout, and visual effects are achieved with custom CSS.
    * **CSS Variables (`:root`)**: Not explicitly used, but the styling is based on a clean, maintainable structure.
    * **Flexbox and CSS Grid**: Used extensively for creating responsive layouts for sections like the header, service grid, about content, and project grid.
    * **Custom Animations**: The site uses `@keyframes` for hero section elements (`fadeIn`) and a scroll-down arrow (`bounce`), as well as CSS transitions for hover and scroll-based effects.
* **JavaScript**: Powers the dynamic and interactive features of the website.
    * **DOM Manipulation**: Used for toggling the mobile menu, adding/removing classes on scroll, and dynamically filtering projects.
    * **Event Listeners**: Captures user interactions like button clicks and scroll events.
    * **`window.scrollTo`**: Implements the smooth scrolling functionality for navigation and the "back to top" button.
* **Font Awesome**: A popular icon toolkit used to display vector icons for various elements such as social media links, service features, and navigation buttons.
* **Google Fonts**: The website uses two fonts: `Montserrat` for a geometric sans-serif look with high legibility, and `Poppins`, another geometric sans-serif typeface.

### Content and Services
* **Services**: The website highlights several key services:
    * **BIM 3D Modeling**: The process of creating and managing digital representations of a building's physical and functional characteristics.
    * **Construction Documents**: A set of drawings and specifications that guide the construction process from start to finish.
    * **Scan to BIM**: The process of using a 3D laser scanner to capture a site's data and create an accurate BIM model from it.
* **Images**: All images for sections like the hero, services, and projects are linked from an external source (`rai-construction-solutions.vercel.app/assets/...` and `unsplash.com`).
* **Contact Information**: Includes a physical address in Jodhpur, Rajasthan, India, as well as a phone number and email address.
