

# LinkedIn AI Reply Chrome Extension

## Overview

This is a Chrome extension built for generating AI-based replies to LinkedIn messages. The extension shows an AI icon when the LinkedIn message input field is focused. Upon clicking the icon, a modal is displayed where the user can enter commands and generate a static response. The generated response can be inserted back into the message input field.

## Features

- Displays an AI icon when the LinkedIn message input field is focused.
- A modal appears when clicking the AI icon, allowing the user to input commands.
- Clicking 'Generate' provides a static response: `Thank you for the opportunity! If you have any more questions or if there's anything else I can help you with, feel free to ask.`
- The response can be inserted into the LinkedIn message input field by clicking 'Insert'.

## Technology Stack

- **React** with **TypeScript**
- **Tailwind CSS** for styling
- **WXT Framework** for building the Chrome extension

## Installation

1. Clone or download the project.
2. Run `npm install` to install all dependencies.
3. Build the project using `npm run build`.
4. Load the Chrome extension:
   - Go to `chrome://extensions/` in your Chrome browser.
   - Enable "Developer Mode".
   - Click on "Load unpacked" and select the project folder.

## Project Structure

- `manifest.json`: Chrome extension manifest file.
- `background.js`: Handles background operations for the extension.
- `contentScript.js`: Contains the logic for detecting when the LinkedIn message input field is focused.
- `src/index.js`: React component for the modal interface and message generation logic.
- `public/index.html`: The main HTML page for the popup.
- `tailwind.config.js`: Tailwind CSS configuration file.

## Usage

1. Focus on the LinkedIn message input field to see the AI icon.
2. Click on the AI icon to open the modal.
3. Enter a command and click "Generate" to see the static reply.
4. Click "Insert" to insert the generated text into the LinkedIn message input.

## Constraints

- No actual API calls for AI response generation are made. The response is static.
- Only works on LinkedIn's message input fields.

## License

This project is for demo purposes and is licensed under MIT.

---

You can copy this content and include it in the `README.md` file of your project.
