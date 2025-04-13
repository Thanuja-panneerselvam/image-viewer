# Image Viewer

A simple image viewer application built using Python's Tkinter library and the Pillow library for image processing. This application allows users to view images from a selected folder, navigate through them, and resize the window while maintaining the aspect ratio of the images.

## Features

- Load images from a selected directory.
- Navigate through images using "Previous" and "Next" buttons.
- Exit the application using the "Exit" button.
- Automatically resize images to fit the window while maintaining their aspect ratio.

## Requirements

- Python 3.x
- Tkinter (usually included with Python)
- Pillow library

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-viewer.git
   cd image-viewer
   ```

2. Install the required libraries:
   ```bash
   pip install Pillow
   ```

## Usage

1. Run the application:
   ```bash
   python image_viewer.py
   ```

2. A dialog will prompt you to select a folder containing images (supported formats: PNG, JPG, JPEG, GIF, BMP).

3. Use the "Previous" and "Next" buttons to navigate through the images.

4. Resize the window to see the images adjust to the new size.

5. Click "Exit" to close the application.

## Code Overview

- **ImageViewer Class**: The main class that handles the GUI and image loading.
- **load_images()**: Prompts the user to select a folder and loads images into the application.
- **show_image(index)**: Displays the image at the specified index.
- **show_next_image()**: Displays the next image in the list.
- **show_previous_image()**: Displays the previous image in the list.
- **on_resize(event)**: Resizes the displayed image when the window is resized.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
