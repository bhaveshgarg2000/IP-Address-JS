# Dynamic Greeting Blog

Welcome to the Dynamic Greeting Blog project! This project creates a static and responsive HTML page similar to a blog post, with a dynamic greeting based on the time of day and the country determined by a query parameter in the URL.

## Table of Contents

- [Objective](#objective)
- [Requirements](#requirements)
- [Evaluation Criteria](#evaluation-criteria)
- [Submission](#submission)
- [Files](#files)
- [Usage](#usage)

## Objective

Create a static and responsive HTML page with a heading, content, and an image. Write a JavaScript file to change the heading text dynamically based on the time of day and the country determined by a query parameter in the URL.

## Requirements

1. **HTML Page:**
   - A heading with an `id` attribute for selection.
   - Some content.
   - An image.

2. **JavaScript File:**
   - Dynamically change the heading text based on the current time and country.
   - Execute after the page has loaded.

3. **Country Determination:**
   - Determine the country based on a query parameter in the URL with the key `ip`.
   - If `ip` is an odd number, the country is India.
   - If `ip` is an even number, the country is England.
   - If `ip` ends with 0, the country is America.

## Evaluation Criteria

- Code clarity (comments and readability).
- Code organization (functions and decoupling of logics).
- Correct implementation of time and country logic.
- Proper use of HTML and JavaScript.
- Responsiveness of the HTML page.

## Submission

- Code using an online code collaboration tool of your choice (CodePen, CodeSandbox, etc.).
https://codepen.io/Bhavesh-Garg/pen/rNPKYRJ
- Provide the HTML, JavaScript, and CSS files.
- Ensure the JavaScript file is properly linked in the HTML file.

## Files

- `index.html`: Basic HTML structure.
- `script.js`: JavaScript file for dynamic greeting logic.
- `style.css`: CSS file for basic styling.

## Usage

1. Clone the repository to your local machine.

```bash
git clone https://github.com/bhaveshgarg2000/IP-Address-JS.git
