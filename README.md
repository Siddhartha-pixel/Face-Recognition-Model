# Face-Recognition-Model
This project is a simple face recognition application built using Python, OpenCV, and the `face_recognition` library. It can detect and identify faces in a static image or a live webcam feed by comparing them against a set of known faces.


# Face Recognition Application

This project is a simple face recognition application built using Python, OpenCV, and the `face_recognition` library. It can detect and identify faces in a static image or a live webcam feed by comparing them against a set of known faces.

## Features

-   **Face Detection**: Finds the locations of faces in an image.
-   **Face Recognition**: Identifies known individuals.
-   **Real-time Recognition**: Works with a webcam feed.
-   **Bounding Boxes**: Draws a box and a label with the recognized name around each face.

## Prerequisites

Before running the application, make sure you have Python installed. The project uses several libraries that you can install with `pip`.

## Installation

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/YourUsername/YourRepoName.git](https://github.com/YourUsername/YourRepoName.git)
    cd YourRepoName
    ```

2.  **Install the required Python libraries**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Add Known Faces**: Place images of the people you want to recognize in the project directory. The code is currently set up to use `person1.jpg`, but you can easily add more by following the pattern in the notebook.

2.  **Run the Notebook**: Open the `face_recognition_app.ipynb` file in a Jupyter environment (like JupyterLab or VS Code with the Jupyter extension) and run all the cells.

    -   The application will first load the known face(s) and display them.
    -   It will then capture a frame from your webcam (or load `test_image.jpg` if you uncomment that line).
    -   Finally, it will display the frame with the recognized faces and their names.

## Project Structure

-   `face_recognition_app.ipynb`: The main Jupyter Notebook containing all the code.
-   `person1.jpg`: An example image of a known person.
-   `requirements.txt`: A list of all the Python dependencies.
-   `README.md`: This file.
-   `.gitignore`: A file to ignore unnecessary files and directories.
