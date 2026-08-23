# Ashura

A responsive personal portfolio website built to showcase projects, skills, experience, and professional information.

## Overview

Ashura is a personal portfolio website designed with a clean and responsive layout. It provides a simple way to present personal projects, background, and other professional information through a structured web interface.

## Features

* Responsive design for desktop, tablet, and mobile devices
* Personal portfolio and project showcase
* Dedicated portfolio/project detail pages
* Reusable HTML, CSS, and JavaScript structure
* SCSS source files for styling
* Local vendor dependencies and assets
* Image and media asset support

## Project Structure

```text
ashura/
├── css/                    # Compiled CSS styles
├── forms/                  # Form-related files
├── img/                    # Images and visual assets
├── js/                     # JavaScript files
├── scss/                   # SCSS source files
├── vendor/                 # Third-party libraries
├── index.html              # Main landing page
├── inner-page.html         # Inner page template
├── portfolio-details.html  # Portfolio project details
├── LICENSE                 # Project license
└── README.md               # Project documentation
```

## Getting Started

No build system or server configuration is required for the basic version.

### 1. Clone the repository

```bash
git clone https://github.com/boukheang/ashura.git
cd ashura
```

### 2. Open the website

Open `index.html` in your browser.

For a better development experience, you can also serve the project using a local HTTP server.

For example:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Customization

The website can be customized by modifying:

* `index.html` for page content and structure
* `css/` for compiled styling
* `scss/` for source styling
* `js/` for interactive functionality
* `img/` for images and other visual assets
* `portfolio-details.html` for individual project information

## Technologies

* HTML5
* CSS3
* JavaScript
* SCSS
