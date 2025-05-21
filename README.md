# Face Detection

This project captures face images using a webcam, detects faces using Haar cascades, and saves the images in grayscale for training a face recognition model.

## 🚀 Features
- **Automatic Face Detection** using OpenCV.
- **Incremental User ID Generation** using a tracking file.
- **200 Face Image Capture** per user.
- **Real-time Display** of the captured face.

## 🛠️ Prerequisites
- Python 3.x
- OpenCV (`cv2`)
- NumPy

## 📥 Installation
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/thecritiz/Face_detection.git
    cd Face_detection
    ```
2. **Install Dependencies:**
    ```bash
    pip install opencv-python numpy
    ```

## 🧑‍💻 Usage
1. **Run the Script:**
    ```bash
    python dataset_generator.py
    ```
2. Follow the on-screen instructions to capture **200 face images**.
3. Press **Enter** to exit before completion if necessary.

## 📁 File Structure
- `dataset_generator.py` - Main script to generate the dataset.
- `last_user_id.txt` - Tracks the last user ID.
- `data/` - Directory to store captured images.

## 📝 Notes
- Ensure your **webcam** is functional and properly connected.

- Captured images will be stored in the format:
    ```
    data/user.<id>.<image_number>.jpg
    ```

## 🛡️ License
This project is licensed under the **MIT License**. Feel free to contribute or modify as needed.

## 🤝 Contribution
1. **Fork the Repository.**
2. **Create a Feature Branch:**
    ```bash
    git checkout -b feature/YourFeature
    ```
3. **Commit Your Changes:**
    ```bash
    git commit -m 'Add your feature'
    ```
4. **Push to the Branch:**
    ```bash
    git push origin feature/YourFeature
    ```
5. **Open a Pull Request.**

