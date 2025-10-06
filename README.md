# Lab 5: CSS foundations 

## Overview
This project builds upon the foundational HTML concepts from **Lab 4** by introducing **CSS layout and styling principles** to create a clean, modern, and responsive login page.  
It demonstrates the use of **CSS Grid**, **Flexbox**, **custom properties (variables)**, and **responsive design techniques** to organize and style content effectively.
The project simulates a professional web application login page featuring:
- A two-column layout with a branded information panel and a login form.
- Responsive design that adapts to mobile and desktop displays.
- Form styling for inputs, labels, and buttons with consistent spacing and typography.
- Hover and focus states for interactive feedback.
- Use of CSS variables for color, spacing, and border radius management.

## Project Goals

By the end of this lab, we will have:
1. A responsive two-column layout using CSS Grid (40-60 split).
2. A login form styled using Flexbox for alignment and spacing.
3. Consistent visual hierarchy through typography, color, and spacing.
4. Implementation of CSS variables to simplify styling and maintenance.
5. Proper hover, focus, and responsive states to enhance usability.


## Issues Encountered
- Default browser styles caused unexpected spacing until a CSS reset (* { box-sizing: border-box; }) was added.
- Custom elements (e.g., <form-field>) required explicit display: block; rules for labels and inputs to stack correctly.
- Achieving perfect vertical centering required combining Grid and Flexbox alignment properties.
- Some scrollbar overflow occurred due to margin with 100vh; switching to padding resolved the issue.
- Responsiveness required fine-tuning column ratios (41fr 6fr) and padding adjustments for smaller viewports

## How to Use
1. Open the project folder.
2. Navigate to the /docs directory.
3. Launch index.html in any modern browser.
4. Resize the window to observe how the layout adapts for mobile and desktop.
5. Test hover and focus states on inputs and the Sign In button.

## Github Pages site
https://joekaihaynes.github.io/lab5-css-foundations/

## Repository Structure
```
lab5-web-foundations-css/
├── docs/
│   ├── index.html         # Main HTML file (login page)
│   ├── styles.css         # CSS file (layout, colors, spacing)
│   ├── chrome.jpg         # Screenshot from Google Chrome
│   ├── firefox.jpg        # Screenshot from Mozilla Firefox
│   ├── microsoftedge.jpg  # Screenshot from Microsoft Edge
│   └── validation.jpg     # HTML/CSS validation screenshot
├── LICENSE.md             # Project license
└── README.md              # Project documentation
```

## License
This project is licensed under the MIT License – see [LICENSE.md](LICENSE.md) for details.

## Author
Joe Haynes