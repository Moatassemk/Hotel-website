# Hotel DJERBA Feedback Form

This is the README file for the Hotel DJERBA Feedback Form web page. Below, you will find an overview of the HTML and CSS code provided.

## Overview

The Hotel DJERBA Feedback Form is a web page that allows users to share their feedback. It features a stylish and interactive design with a background of animated particles. Users can provide their name, email, and feedback, which is then submitted through the form. After submission, a success message is displayed.

## HTML Structure

The HTML structure of the code is as follows:

1. `<!DOCTYPE html>`: The document type declaration for HTML5.
2. `<html lang="en">`: The root element of the HTML document with a specified language.
3. `<head>`: The head section containing meta tags, links to external stylesheets and scripts, and the page title.
4. `<style>`: Internal CSS styles for the webpage.
5. `<body>`: The main content of the webpage.

### Particle Animation

- `<div id="particles-js">`: A container for the particle animation created using the Particles.js library.

### Feedback Form

- `<div class="container">`: A container for the feedback form and success message.
- `<h1>`: A heading inviting users to share their feedback.
- `<form id="feedbackForm">`: The feedback form.

### Form Fields

- Name, Email, and Feedback fields within the form.

### Success Message

- `<div id="successMessage" class="hidden">`: A hidden success message that is displayed after form submission.

## CSS Styles

The code includes CSS styles to define the appearance and layout of the webpage, including background, form design, and success message display.

## JavaScript

The code includes JavaScript to:

1. Initialize the particle animation using the Particles.js library.
2. Listen for the form submission event.
3. Simulate form submission by displaying a success message after a delay.

## External Dependencies

The code uses the following external dependencies:

- Font Awesome (for icons)
- Particles.js (for the particle animation)

You should ensure that these external dependencies are available for the webpage to display correctly.

## Usage

This code is a static HTML page for collecting feedback. You can customize the content and styles to suit your specific needs. Additionally, you can implement the actual form submission logic in place of the simulated submission provided in the JavaScript.

## Author

This code is provided by Moatassem kouz.

## License

This code is provided as a template and can be customized for your own use. Please make sure to respect the licenses of any external dependencies used in this code.

If you have any questions or need further assistance, you can refer to the code's comments or documentation for the external dependencies.