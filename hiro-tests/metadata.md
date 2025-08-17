To run these tests, make sure you have the necessary packages installed, including `opencv-python` and `numpy`. You can install them using pip: `pip install opencv-python numpy`. These tests cover the core functionality of the face recognition system, including face detection, recognition, and saving faces. Make sure to replace the `haarcascade_frontalface_default.xml` file path with the actual path to the file on your system. The tests will fail if the face detection or recognition fails, or if the face cannot be saved.

## Required Packages
- unittest
- cv2
- numpy
## Test Cases for Facial Recognition Code
The following test cases are designed to test the core functionality of the facial recognition code.
### Test 1: Load Classifier
*   Test that the classifier is loaded correctly using `cv2.CascadeClassifier`.
### Test 2: Load Image
*   Test that an image is loaded correctly using `cv2.imread`.
### Test 3: Upload Image
*   Test that an image can be uploaded using `st.file_uploader`.


## Required Packages
- unittest
- numpy
- Pillow
- opencv-python
- streamlit
