# Theme Documentation

## Overview
Welcome to the documentation for the wordpress website. This document provides an overview of the theme's features, files that may require editing, design decisions, and other relevant information to help you continue developing the theme.


## Features
- **Responsive Design:** The theme is fully responsive and adapts to various screen sizes.
- **Custom Header:** The theme includes a customizable header with logo and navigation menu support.
- **Custom Footer:** The footer area is widgetized and can be customized from the WordPress dashboard.
- **Custom Shortcodes:** Includes shortcodes for buttons, columns, and other design elements.
- **Theme Customizer:** Allows real-time customization of colors, fonts, and layout options.


### Additional Directories
- **/assets/css/**: Contains additional CSS files.
- **/assets/js/**: Contains JavaScript files.
- **/assets/images/**: Contains theme images.


## Editing Instructions

### Customizing Colors
* To change the theme colors, update the color variables in the `style.css` file. Use the WordPress Customizer for real-time preview and changes.

### Customizing Header
* To change the logo/site title, navigate to the themes menu in wordpress dashboard and customize the theme named Assignment 2 and once its open, select site identity. In this section titles, logos and taglines can be altered as per user preference.

* To change the site menu, navigate to the same theme, customize and select the menus option. Then select the menu named "primary", and add items/reorder as needed.

### Customizing Footer
* To edit content, navigate to the "Assignment 2" theme customization, select the Widgets option and click on "Footer 1" to edit the left column, and select "Footer 2" to edit the right column.

### Adding New Shortcodes
Shortcodes are defined in the `functions.php` file. To add new shortcodes, create a new function and register it using the `add_shortcode()` function. Shortcodes can also be customized using the "Shortcodes Ultimate" plugin.


## Additional Notes
- **Child Theme Support:** The theme supports child themes for customizations.
