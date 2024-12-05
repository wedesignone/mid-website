# Mid-space Website

Welcome to the **Mid-space Website**! This project focuses on aligning diverse community needs with inclusive public spaces through AI-generated visualizations and comprehensive datasets. Mid-space serves as a bridge between innovative AI tools and urban design, fostering environments that cater to varied community preferences.

## Live Website

Access the live website here: [mid-space.one](https://mid-space.one)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Customizing Content](#customizing-content)
  - [Adding New Pages](#adding-new-pages)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## Features

- **AI-Generated Visualizations:** Innovative tools that create visual representations of inclusive public spaces based on community preferences.
- **Comprehensive Dataset:** A robust dataset that bridges AI visualizations with diverse community needs for informed urban design decisions.
- **Research Paper:** Detailed documentation and findings on the project’s methodologies and outcomes.
- **Interactive Tools:** Engaging tools for users to explore and interact with data and visualizations.
- **Responsive Design:** Optimized for desktops, tablets, and mobile devices to ensure accessibility.
- **Resource Downloads:** Easy access to download datasets, research papers, and project code.

## Installation

To run the website locally:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/wedesignone/mid-space-website.git
    ```

2. **Navigate to the Project Directory**
    ```bash
    cd mid-space-website
    ```

3. **Open the Website**
    - Open `index.html` in your preferred web browser.

## Usage

### Customizing Content

1. **Update Text Content:**
   - Replace placeholder texts (`<!-- Placeholder -->`) with your own content in HTML files.

2. **Replace Images:**
   - Add your own images to the `assets/images/` directory.
   - Update the `src` attributes in HTML to point to your images.
   
   **Update the Favicon:**
   - Replace the existing favicon with your own by uploading your favicon file to the `assets/images/` directory.
   - Update the `<link>` tag in the `<head>` section of your HTML files to point to your favicon.
     ```html
     <!-- Favicon -->
     <link rel="icon" href="assets/images/your-favicon.ico" type="image/x-icon">
     ```
   - Ensure your favicon file is named appropriately (e.g., `favicon.ico`) or update the `href` path accordingly.

3. **Modify Styles:**
   - Edit `assets/css/styles.css` to customize the appearance as per your preferences.

4. **Adjust Scripts:**
   - Enhance or modify `assets/js/scripts.js` to add interactivity.

### Adding New Pages

To add a new page:

1. **Duplicate an Existing HTML File:**
   - For example, duplicate `paper.html` and rename it to `new-page.html`.
   
2. **Update the Content:**
   - Modify the content within the new HTML file as needed.
   
3. **Update Navigation:**
   - Add a new `<li>` in the navigation menu within the `<nav>` section to link to your new page.
     ```html
     <li class="new-page-link"><a href="new-page.html">New Page</a></li>
     ```
   
4. **Customize as Needed:**
   - Ensure that all sections are appropriately filled with relevant content.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For more information, please contact [rashidmushkani@gmail.com](mailto:rashidmushkani@gmail.com) | [www.rsdmu.com](https://www.rsdmu.com)

## Acknowledgements

- [Roboto Font](https://fonts.google.com/specimen/Roboto) by Google Fonts
- [Font Awesome](https://fontawesome.com/) for Icons
- [AOS](https://michalsnik.github.io/aos/) for Scroll Animations
