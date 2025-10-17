# Captcha Solver Web App

A simple, responsive web application designed to display a captcha image and allow users to input the text they see. It supports loading a default local image or an external image via a URL parameter.

## Features

*   **Responsive Design**: Built with Tailwind CSS, ensuring a great experience on any device.
*   **Dynamic Image Loading**: Displays a default `sample.png` image or loads an image from a URL provided in the query string (`?url=https://.../image.png`).
*   **User Input**: Provides a clear input field for users to type the captcha text.
*   **Basic Validation**: For the default `sample.png` image, it includes client-side validation against the known captcha text ("ADUR3"). For external images, it indicates submission without validation.

## Usage

1.  **Open `index.html` in your web browser.**
2.  **Default Mode**: The application will display the `sample.png` image, and you can try to solve the captcha by entering "ADUR3".
3.  **External Image Mode**: To display an external captcha image, append a `?url=` parameter to your URL.
    *   Example: `index.html?url=https://example.com/some-captcha.png`
    *   Replace `https://example.com/some-captcha.png` with the actual URL of your captcha image.

## Local Development

To run this application locally:

1.  Save the `index.html`, `README.md`, and `LICENSE` files into a folder.
2.  Ensure `sample.png` is in the same folder as `index.html`.
3.  Open `index.html` directly in your web browser.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.
