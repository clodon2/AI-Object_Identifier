# AI Object Analyzer

Web app derived from https://github.com/bdekraker/webcamgpt-vision that looks for objects in an image and identifies them.

Made with Node.js

## Features

- Webcam integration for live image capture.
- Processing of images with OpenAI's GPT-4o Vision API.
- Display of AI-generated object descriptions.
- Simple and intuitive user interface.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have a modern web browser.
- You have Node.js and npm installed.
- You have obtained an API key from OpenAI for GPT-4 Vision API usage.

## Installation

To install WebcamGPT-Vision, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/clodon2/AI-Object_Identifier
   ```
2. Navigate to the `js-version` directory.
3. Run `npm install` to install the dependencies.
4. Create a `.env` file in the root of `js-version` directory and add your OpenAI API key:
   ```
   OPENAI_API_KEY=YOUR_DEFAULT_API_KEY
   ```
5. Start the server with `node server.js`.
6. Access the application through your web browser at `http://localhost:3000` (or the port you configured).


## Usage

1. Ensure that you have a working webcam connected and allowed for use by the browser.
2. Open the `index.html` page in your web browser.
3. Click the "Capture" button to take a snapshot from your webcam.
4. The application will process the image and display the description below the webcam feed.


This project is licensed under the [MIT License](LICENSE.md) - see the `LICENSE.md` file for details.

## Acknowledgements

- Thanks to OpenAI for providing the GPT-4o Vision API.
- [Benjamin De Kraker](https://twitter.com/BenjaminDEKR


## Disclaimer

This application is not affiliated with OpenAI, and the GPT-4 Vision API usage is subject to OpenAI's terms and conditions. Ensure that you follow OpenAI's usage guidelines and have appropriate permissions to use the API.
