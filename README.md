# Face-Recognition-Model
This project is a simple face recognition application built using Python, OpenCV, and the `face_recognition` library. It can detect and identify faces in a static image or a live webcam feed by comparing them against a set of known faces.


# Face Detection with OpenCV

This project demonstrates a simple face detection application using Python and the OpenCV library. It utilizes a pre-trained Haar Cascade classifier (`haarcascade_frontalface_default.xml`) to identify human faces in an image.

## Features

-   Loads an image from a specified file path.
-   Resizes the image for consistent processing.
-   Converts the image to grayscale, as required by the Haar Cascade classifier.
-   Detects faces and returns their coordinates.
-   (Note: The provided code snippet currently only detects the faces. To display bounding boxes, you would need to add a few more lines of code.)

## Prerequisites

To run this project, you need to have Python and the necessary libraries installed.

## Installation

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/Siddhartha-pixel/Face-Recognition-Model](https://github.com/Siddhartha-pixel/Face-Recognition-Model)
    cd YourRepoName
    ```

2.  **Install the required Python libraries**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

This project is a Jupyter Notebook. To run the code, you will need a Jupyter environment (like JupyterLab or VS Code with the Jupyter extension).

1.  **Open the Notebook**: Launch your Jupyter environment and open `facerecognition.ipynb`.
2.  **Provide the Data**: Make sure the required image (`people1.jpg`) and the classifier file (`haarcascade_frontalface_default.xml`) are in the correct path as specified in the notebook, or update the paths in the code to match your file locations.
3.  **Run the Cells**: Execute the cells in the notebook sequentially to see the code in action. The notebook will:
    -   Load and display the original image.
    -   Resize the image.
    -   Convert it to grayscale.
    -   Load the face detector.
    -   Attempt to detect faces, which will output the coordinates of any detected faces.

## Project Structure

-   `facerecognition.ipynb`: The main Jupyter Notebook containing the face detection code.
-   `people1.jpg`: The input image file used for face detection.
-   `haarcascade_frontalface_default.xml`: The pre-trained Haar Cascade classifier file from OpenCV.
-   `requirements.txt`: A list of all the Python dependencies.
-   `README.md`: This file.
-   `.gitignore`: A file to ignore unnecessary files and directories.
