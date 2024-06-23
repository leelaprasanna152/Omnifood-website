# 🍽️ Omnifood: Your Gateway to Healthy Eating!

Welcome to the Omnifood Website Project! This project showcases the best practices in modern web design by using a variety of CSS properties, HTML tags, and AOS.js animations. Whether you're a developer looking for inspiration or a food enthusiast, this project has something for everyone.

![Omnifood Banner](path-to-banner-image.jpg) 

## 🚀 Project Overview

Omnifood is a fictional food delivery service dedicated to providing nutritious meals right to your doorstep. Our website is designed to be both visually appealing and highly functional, ensuring a seamless user experience across all devices.

## 🌟 Features

- **Responsive Design:** Built with CSS Flexbox and Grid to ensure a flawless look on any device.
- **Smooth Animations:** Leveraging AOS.js for captivating scroll animations.
- **Optimized Typography:** Enhanced text rendering for superior readability.
- **Interactive Elements:** Engaging user interactions with pseudo-elements and animations.
- **Customizable Backgrounds:** Dynamic background images that adjust perfectly to the viewport.

## 🛠️ Technologies Used

- **HTML5:** For semantic structure.
- **CSS3:** For styling and layout.
- **JavaScript:** For interactivity.
- **AOS.js:** For animation on scroll.
- **SVG:** For scalable vector graphics.

## 📷 Screenshots

### Home Page

![1](https://github.com/leelaprasanna152/Omnifood-website/assets/142930059/86d89298-a344-4bdf-8ad8-8583aa2ccf43)

### Features Section

![2](https://github.com/leelaprasanna152/Omnifood-website/assets/142930059/d2551f35-8d2f-49fe-b10a-c2fe138eec9f)
![3](https://github.com/leelaprasanna152/Omnifood-website/assets/142930059/6d887dce-1b84-46ce-bcf2-41204b571685)

### Testimonials Section

![5](https://github.com/leelaprasanna152/Omnifood-website/assets/142930059/e79e1afa-5697-4bad-861d-a0ef0936bbdb)

## 🎥 Video Demonstration

Check out this video demonstration to see the Omnifood website in action:


https://github.com/leelaprasanna152/Omnifood-website/assets/142930059/7b62ae38-c9a4-4b6c-b516-9ae28f29ebc4

## 📥 Setup Instructions

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/omnifood.git
    cd omnifood
    ```

2. **Open the project in your favorite code editor.**

3. **Include AOS.js and its CSS:**

    Add the following line to the `<head>` section of your `index.html`:

    ```html
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
    ```

    Add the following lines before the closing `</body>` tag:

    ```html
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
        AOS.init();
    </script>
    ```

4. **Open `index.html` in your browser to view the website.**

## 🎨 Key Properties and Elements

### 1. Text Rendering Optimization

- **Property:** `text-rendering`
- **Usage:** Optimizes text for legibility, speed, or geometric precision.

    ```css
    body {
        text-rendering: optimizeLegibility;
    }
    ```

### 2. Full Viewport Height

- **Property:** `height: 100vh;`
- **Usage:** Sets the element's height to the full viewport height.

    ```css
    .full-screen {
        height: 100vh;
    }
    ```

### 3. Background Attachment

- **Property:** `background-attachment`
- **Usage:** Determines if a background image scrolls with the page or stays fixed.

    ```css
    .background-fixed {
        background-attachment: fixed;
    }
    ```

### 4. Background Size

- **Property:** `background-size`
- **Usage:** Specifies the size of background images.

    ```css
    .background-cover {
        background-size: cover;
    }
    ```

### 5. Generated Content with Pseudo-elements

- **Property:** `content`
- **Usage:** Used with `::before` and `::after` to insert content.

    ```css
    li::before {
        content: "•";
        padding-right: 8px;
        color: blue;
    }
    ```

### 6. Visibility Control

- **Property:** `visibility`
- **Usage:** Toggles element visibility without affecting layout.

    ```css
    .hidden-element {
        visibility: hidden;
    }
    ```

### 7. Clearfix for Floats

- **Property:** `clear`
- **Usage:** Controls the flow next to floated elements.

    ```css
    .clearfix::after {
        content: "";
        clear: both;
        display: table;
    }
    ```

### 8. Vertical Alignment

- **Property:** `vertical-align`
- **Usage:** Sets the vertical alignment of an element.

    ```css
    .vertical-middle {
        vertical-align: middle;
    }
    ```

### 9. AOS.js Animations

- **Library:** AOS.js
- **Usage:** Adds scroll animations with ease.

    ```html
    <div data-aos="fade-up">Fade Up Animation</div>
    ```

    Supported animations include fade, flip, and zoom effects.

## 🎉 Get Started

Dive into the Omnifood project to see how these properties and animations come together to create a stunning website. Experiment with different values and settings to make the project truly your own.

## 🤝 Contributing

We welcome contributions! If you have ideas to improve the project, please fork the repository and submit a pull request. Let's build something amazing together.


