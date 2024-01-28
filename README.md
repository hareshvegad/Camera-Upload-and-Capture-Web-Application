# Camera Upload and Capture Web Application

This web application provides a simple interface for users to upload images or capture photos using their device's camera. The application is built using HTML, Bootstrap, and JavaScript. Users can enter a recipient's username in the input field and click the "Upload" button to open the camera modal. In the camera modal, they can capture a photo, preview it, and save it. The saved photo and file name are displayed below the input field.

## Features

1. Upload Input Field:
        The application provides an input field for users to enter a recipient's username.

2. Upload Button:
        There is an "Upload" button that triggers the opening of a camera modal when clicked.

3. Camera Modal:
        The camera modal allows users to access their device's camera.
        It includes a live video feed from the camera using the navigator.mediaDevices.getUserMedia API.
        Users can capture a photo from the live feed by clicking the "Capture Photo" button.

4. Save Photo Button:
        After capturing a photo, users can click the "Save Photo" button to download and save the captured image as 'captured_photo.png'.
        The saved photo and file name are displayed below the input field.

5. Close Button:
        The modal can be closed using the "Close" button, and it stops the video stream.

## Usage

    1. Open the HTML file in a web browser.
    Enter the recipient's username in the input field.
    2. Click the "Upload" button to open the camera modal.
    3. Allow access to the device's camera when prompted.
    4. Capture a photo using the "Capture Photo" button.
    5. Save the captured photo using the "Save Photo" button.
    6. The saved photo and file name will be displayed below the input field.

## Dependencies

    Bootstrap (v5.0.2):
        Used for styling and layout of the web application.
        Linked from a CDN for easy integration.

    jQuery (v3.6.4):
        Required by Bootstrap for JavaScript functionality.
        Linked from a CDN for easy integration.

    Popper.js (v2.9.2):
        Required by Bootstrap for tooltip and popover positioning.
        Linked from a CDN for easy integration.

## How to Contribute

Feel free to contribute to the development of this application by submitting issues or pull requests. Please follow the standard coding conventions and provide clear documentation for any changes made.

## License

This project is licensed under the MIT License.
