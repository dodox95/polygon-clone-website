Project README.md
Overview

This project is a web application that showcases a responsive design using the Flowbite framework and Tailwind CSS. The primary theme revolves around Ethereum, as indicated by the title in the index.html file.
Files
1. index.html

    This is the main HTML file that structures the web page.
    It uses the Flowbite framework for styling and functionality.
    The page has a navigation bar with a dropdown mega menu.
    External styles are linked from style.css and the Flowbite CDN.
    The Flowbite JavaScript library is also included for dynamic functionalities.

2. style.css

    Contains custom styles for the project.
    Defines styles for .container, .btn, .btn-2, and .btn-3 classes.
    Each button class has its own positioning and hover effect.

3. tailwind.config.js

    Configuration file for Tailwind CSS.
    Specifies the content sources for Tailwind to purge unused styles.
    Extends the default theme with custom colors, screens, keyframes, and animations.
    No plugins are currently being used.

4. package.json

    Defines the project's metadata and dependencies.
    The project is named lesson05.
    Contains scripts for running Tailwind CSS and Prettier.
    The only development dependency is prettier-plugin-tailwindcss.

Setup & Development

    Installation: Before starting, make sure to install the required dependencies by running:

    bash

npm install

Running Tailwind CSS: To watch and compile your Tailwind CSS, use:

bash

npm run tailwind

Formatting with Prettier: To format your HTML files, use:

bash

    npm run prettier

Dependencies

    Flowbite: A modern CSS framework based on Flexbox and Grid.
    Tailwind CSS: A utility-first CSS framework for rapid UI development.
    Prettier: An opinionated code formatter.

License

This project is licensed under the ISC license.
