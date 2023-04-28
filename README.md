# face-emotion-recognition-app template

This is a simple web template for showing live instructional videos and student videos. The project is built using HTML, CSS, and JavaScript.

## Features

+ Display instructional videos and live student videos side by side
+ Use face-api.js to detect and display student emotions in real-time
+ Easy to customize and integrate with other projects

## Installation

1. Clone the repository.
2. Open the folder in VSCode.
3. To avoid CORS policy errors related to the face-api.js library, we need to run our code on a local server instead of opening the HTML file directly in the browser. One easy way to do this is to use a live server extension in VSCode.
4. Once you have a live server extension installed, you can right-click on the HTML file in the VSCode explorer and select "Open with Live Server" to start the server and open the file in your default browser.

## Usage

1. Add your instructional video to the live-instructional-video.mp4 file
2. Add your live student video to the student-video.mp4 file
3. Run the index.html file in a web browser by live server of VSCode to see the live videos side by side
4. The student's emotions will be displayed on the page in real-time

## Dependencies

The project uses the following dependencies:

+ face-api.js for emotion detection
