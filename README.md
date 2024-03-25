# OvaTiamo

OvaTiamo is a rapid redesign of avotiamo.co.ke, transitioning from a WordPress-based platform to a more lightweight and efficient static site built with HTML, CSS, and JavaScript. This project aims to improve performance, user experience, and maintainability.

## Table of Contents

- [OvaTiamo](#ovatiamo)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Languages](#languages)
  - [Designs](#designs)
- [File Structure](#file-structure)

## Overview

This project represents a significant shift from the original WordPress platform to a static site. The decision to move away from WordPress was driven by the desire for a more streamlined, high-performance website that can be easily maintained and updated.

## Languages

- **HTML**: Used for structuring the content of the website.
- **CSS**: Utilized for styling the website, ensuring a visually appealing and responsive design.
- **JavaScript**: Employed to add interactivity and dynamic content, including the transition effect between pages.
- **Apache Directives**: Configured in the `.htaccess` file for server-side settings, such as URL rewriting and error handling.

## Designs

The design for OvaTiamo was meticulously crafted using Figma. The designs can be accessed and reviewed [here](https://www.figma.com/file/ul3BUnebQtphmZfUt83p68/Ovatiamo-Site?type=design&node-id=0%3A1&mode=design&t=B7XuIcHA5DOnKzdV-1).


# File Structure
```
ovatiamo
│   .htaccess
│   404.html
│   index.html
│   README.md
│
├───css
│       404.css
│       index.css
│       page-transition.css
│       style.css
│
├───images
│       favicon.ico
│       hero-img.png
│       logo.png
│
└───js
        pageTransition.js
```

- .htaccess: This file is used for server configuration on Apache servers. It can be used to enable/disable additional functionality and features that the Apache Web Server software offers.
- 404.html: A custom error page that is displayed when a user tries to access a page that does not exist on the website. It helps in maintaining a consistent look and feel across the site.
- index.html: The default or home page of the website. When users visit the root URL of the website, this is the page that is displayed.
- README.md: A markdown file that typically contains information about the project, such as how to set it up, how to contribute, and any other relevant information for users or developers.
- css: This directory contains all the CSS files that style the website. The CSS files using a modular approach to CSS, where different stylesheets are used for different parts of the site or for different purposes (e.g., index.css for the homepage, 404.css for the error page, and style.css as a general stylesheet).
- images: This directory holds all the image files used on the website, such as logos, hero images, and favicons. The inclusion of a favicon indicates that the site is designed to be bookmarked or added to the home screen on mobile devices.js: This directory contains JavaScript files that add interactivity and functionality to the website. The presence of pageTransition.js suggests that the site includes page transition animations or effects.
