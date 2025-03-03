# React Image Gallery

This project is a simple image gallery built using React. It fetches images from the Picsum Photos API and displays them in a responsive grid layout. You can click on any image to view it in fullscreen mode.

## Features
- Displays images in a responsive grid layout.
- Click on any image to toggle its fullscreen view.
- Custom styles for image thumbnails and fullscreen mode.
- Built with React and Emotion for styled components.

## Technologies Used
- React
- ReactDOM
- Emotion (for styled components)
- CSS for global styles

## Getting Started
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/react-image-gallery.git
    ```

2. Navigate into the project directory:
    ```bash
    cd react-image-gallery
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

4. Start the development server:
    ```bash
    npm start
    ```
    This will run the app at [http://localhost:3000](http://localhost:3000) in your browser.

## How It Works
The App.js file is the main entry point of the application, rendering the TestAPI component.
The TestAPI component fetches a list of images from the Picsum Photos API and displays them in a grid layout.
When an image is clicked, its state toggles between a thumbnail view and a fullscreen view.
The styles.css file defines global styles for the body and header elements.

## Usage
When the app loads, it fetches 30 images from the Picsum API.
Images are displayed as thumbnails, and when clicked, they expand to fullscreen mode.
You can toggle the fullscreen view by clicking on the image again.

## Acknowledgements
Picsum Photos for providing free random images for the gallery.
React for the framework used in this project.
Emotion for styled components.
