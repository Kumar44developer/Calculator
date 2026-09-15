<div align="center">

# Calculator

### A clean, animated calculator for everyday arithmetic

A lightweight web calculator built with vanilla HTML, CSS, and JavaScript. It offers a polished, responsive interface for fast addition, subtraction, multiplication, and division, with zero dependencies and instant load times.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [How It Works](#how-it-works)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Design](#design)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

---

## Overview

Calculator is a front-end only application that runs entirely in the browser. The interface presents a numeric keypad, the four core arithmetic operators, an equals key, and a clear key. Input is echoed to a display area in real time, and pressing equals evaluates the full expression at once.

The project is intentionally simple and dependency free, making it fast to load, easy to read, and straightforward to extend or embed in a larger site.

## Features

- Addition, subtraction, multiplication, and division
- Decimal point support for non-integer values
- Live display that updates as each key is pressed
- One-tap clear to reset the display
- Smooth entrance animation and hover feedback on keys
- Fully responsive layout centered on any screen
- No frameworks, build steps, or external libraries

## Tech Stack

| Technology | Role |
| --- | --- |
| HTML5 | Structure and calculator layout |
| CSS3 | Styling, gradients, animations, and responsive design |
| JavaScript | Input handling and expression evaluation |

## How It Works

The keypad is rendered as a list of items. On load, the script attaches a click handler to each key. Number, operator, and decimal keys append their value to the display, with the multiplication symbol mapped to the standard operator. The equals key evaluates the current expression and shows the result, and the clear key resets the display to an empty state.

## Project Structure

```
project26/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Getting Started

No installation, build tools, or servers are required.

Clone the repository:

```bash
git clone https://github.com/Kumar44developer/Calculator.git
```

Open `index.html` in any modern browser. For live reloading during development, the VS Code Live Server extension works well.

## Usage

1. Tap the number keys to enter values.
2. Choose an operator to build an expression.
3. Press the equals key to evaluate and display the result.
4. Press clear to reset and start again.

## Design

The interface uses a dark gradient body with a bordered calculator panel that scales into view on load. Keys are circular with hover highlights, operators are visually distinct, and the equals key is emphasized in green. The display sits at the top with right-aligned, high-contrast text for readability.

## Roadmap

- Keyboard input support
- Backspace and delete for correcting entries
- Calculation history log
- Percentage and sign-toggle keys
- Theme options and a light mode

## Contributing

Contributions are welcome. Fork the repository, create a feature branch, commit your changes, and open a pull request with a clear description.

## License

This project is released under the MIT License.

## Author

Created by [Kumar44developer](https://github.com/Kumar44developer).
