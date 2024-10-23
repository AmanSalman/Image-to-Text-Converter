# Image to Text Converter

This React Native application allows users to upload an image and extract text from it using the Google Vision API. The app provides a user-friendly interface for selecting images from the device's library, and displays the extracted text in a visually appealing format. Users can easily pick another image after clearing the previous results.

## Features

- Image Selection: Choose images from the device's photo library.
- Text Extraction: Uses Google Vision API to extract text from the selected image.
- Clear Results: Option to clear extracted text and upload a new image.
- Responsive Design: Works seamlessly on both Android and iOS devices.
  
## Tech Stack

- **React Native**
- **Expo**
- **Axios**
- **Google Vision API**

## API Key
To use the Google Vision API, you need an API key. Replace the placeholder in the code with your own API key to enable text extraction functionality.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AmanSalman/Image-to-Text-Converter.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Image-to-Text-Converter
   ```
3. Install the required dependencies:
   ```bash
   npm install
   ```
4. Create a config.js file in the root directory and add the API key:
   ```bash
   export const API_KEY <your api key>
   ```
5. To run the app locally, use the following command:
   ```bash
   npx expo start
   ```
   This command will start the Expo development server and provide you with a QR code to scan with the Expo Go app on your mobile device or open the app in an Android/iOS emulator.
  
