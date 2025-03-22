Face_detection

This project captures face images using a webcam, detects faces using Haar cascades, and saves the images in grayscale for training a face recognition model.

Features

Automatic face detection using OpenCV.

Incremental user ID generation using a tracking file.

Captures and saves 200 face images per user.

Displays the captured face in real-time.

Prerequisites

Python 3.x

OpenCV (cv2)

NumPy

Installation

Clone this repository:

git clone https://github.com/thecritiz/Face_detection.git
cd Face_detection

Install dependencies:

pip install opencv-python numpy

Usage

Run the script:

python dataset_generator.py

Follow on-screen instructions to capture 200 face images.

Press Enter to exit before completion if necessary.

File Structure

dataset_generator.py: Main script to generate the dataset.

last_user_id.txt: Tracks the last user ID.

data/: Directory to store captured images.

Notes

Ensure your webcam is functional and properly connected.

Captured images will be stored in data/user.<id>.<image_number>.jpg.

License

This project is licensed under the MIT License. Feel free to contribute or modify as needed.

Contribution

Fork the repository.

Create your feature branch: git checkout -b feature/YourFeature

Commit your changes: git commit -m 'Add your feature'

Push to the branch: git push origin feature/YourFeature

Open a Pull Request.

