# Digital Clock

A small, lightweight, and responsive digital clock built with plain HTML, CSS, and JavaScript. It displays your local time in the browser and updates every second — no frameworks or build tools required.

![Digital Clock Screenshot](./Screenshot%202024-06-21%20001919.png)

Table of contents

- [Demo / Usage](#demo--usage)
- [Features](#features)
- [How it works (brief)](#how-it-works-brief)
- [Customize](#customize)
- [Accessibility](#accessibility)
- [Contributing](#contributing)
- [License](#license)


## Demo / Usage

To run the clock locally:

1. Clone the repository:

   git clone https://github.com/BinaryVortex/Digital-Clock-4.git

2. Open `index.html` in your web browser (double-click the file or drag it into a browser window).

The clock will start immediately and update every second.

Tip: You can also open the `index.html` file with a simple static file server (for example `npx http-server` or `python -m http.server`) if you prefer.


## Features

- Real-time updating clock (hours, minutes, seconds)
- Clean, minimal design with responsive layout
- No dependencies — vanilla HTML, CSS, and JavaScript
- Easy to customize colors, fonts, and time format


## How it works (brief)

- index.html provides the markup and container elements for the clock.
- style.css contains the visual design and responsive layout rules.
- script.js reads the user's local time, formats it, and updates the DOM every second using setInterval / requestAnimationFrame.


## Customize

You can change the look and behavior quickly:

- Styles: edit `style.css` to modify colors, font-family, sizing, spacing, and layout.
- Behavior: edit `script.js` to adjust the time format (12-hour vs 24-hour), toggle AM/PM, or change the update cadence.

Example: to switch to a 12-hour format with AM/PM, modify the formatting code in `script.js` where hours are calculated and append AM/PM accordingly.


## Accessibility

- The clock is simple and readable with a high-contrast design by default. Consider increasing font-size, contrast, or adding `aria-live="polite"` to the time container for better assistive technology support.


## Contributing

Contributions are welcome! If you have ideas for additional features (date display, alarms, time-zone switching), styling improvements, or accessibility fixes, please open an issue or submit a pull request.

When opening a PR, please include:

- A short description of the change
- Screenshots if the change affects visuals
- Any manual test steps to verify the change


## License

This project is licensed under the MIT License. If a LICENSE file is not present in the repository, consider adding one with the standard MIT text.


---

Created by BinaryVortex
