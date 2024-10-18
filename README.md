# A-Website-Coming-Soon-Page
A Bakery Website Coming Soon Page
# Izzah'Bakers Coming Soon Page

This project is a simple "Coming Soon" page for Izzah'Bakers, built with HTML, CSS, and JavaScript. It features a countdown timer, a launch notification, and an animated rocket icon.

## Table of Contents


- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Technologies](#technologies)
- [License](#license)



## Features

- **Responsive Design**: The page is fully responsive, with a clean layout and beautiful background image.
- **Countdown Timer**: A dynamic countdown timer to the launch date.
- **Animated Rocket**: A rocket icon that animates upward.
- **Custom Button**: A stylish "Learn More" button with an image.
- **Google Fonts Integration**: Integrated with Google Fonts for a unique typography style.
- **Remix Icons Integration**: Using Remix Icons for the rocket animation.
- **CSS Animation**: Simple and effective keyframe animations.

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone (https://github.com/Izzah-23/A-Website-Coming-Soon-Page)
    ```

2. Open the project directory:

    ```bash
    cd A Website Coming Soon Page
    ```

3. Open the `index.html` file in your browser to view the project.

## Usage

This "Coming Soon" page is a placeholder for websites that are under construction or in maintenance mode. The countdown timer will count down to a specific launch date (currently set to **October 30, 2024**).

To change the launch date:

1. Open the `index.html` file.
2. Locate the following line in the script section:

    ```javascript
    var countDownDate = new Date("Oct 30, 2024 00:00:00").getTime();
    ```

3. Modify the date to your preferred launch date.

## Customization

### Change Background Image

To replace the background image with your own:

1. Open the `style.css` file.
2. Replace the current background image URL with your own:

    ```css
    .container {
        background-image: url('YOUR_IMAGE_URL_HERE');
    }
    ```

### Modify Font

The project uses **Google Fonts** (Dancing Script). You can change the font by editing the link in the `<head>` section of the `index.html` file.

### Icon Size and Animation

The rocket icon size and animation are controlled in the CSS:

- Change the size of the icon by adjusting the `font-size` property in `.ri-rocket-2-fill`.
- Modify the animation speed or behavior in the `@keyframes` section.

### Countdown Timer

You can further customize the countdown timer by modifying the JavaScript in the `<script>` section. For example, you can add more custom behavior when the timer ends.

## Technologies

- **HTML5**: Structuring the web page.
- **CSS3**: Styling and layout.
- **JavaScript**: Countdown timer functionality.
- **Remix Icons**: Rocket icon for animation.
- **Google Fonts**: Custom fonts.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as you like!

---

**Author**: Izzah Manzoor
