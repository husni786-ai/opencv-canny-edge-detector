

**`opencv-canny-edge-detector`**

---

# 👁️ Real-time Canny Edge Detection with OpenCV

This repository hosts a Jupyter Notebook that demonstrates a fundamental Computer Vision pipeline for **Edge Detection** using the **Canny Algorithm** from the **OpenCV (cv2)** library. The notebook processes a sample image, applies various filters, and extracts prominent edges.

## 🎯 Project Goals

The objective of this project is to implement and visualize the standard steps required to perform robust edge detection on an image:

1.  **Image Loading:** Read a local image file (e.g., `Dog.jpeg`).
2.  **Noise Reduction:** Apply a Gaussian filter to smooth the image and suppress noise.
3.  **Feature Extraction:** Execute the Canny algorithm to identify significant edges.
4.  **Visualization:** Display the intermediate and final outputs of the processing pipeline (Original, Grayscale, Blurred, and Edge-detected images).

## ⚙️ Technology Stack and Dependencies

The project relies on Python and the OpenCV library.

| Library | Role |
| :--- | :--- |
| **`opencv-python (cv2)`** | Core Computer Vision library for image loading, color conversion, blurring, and Canny detection. |
| **`google.colab.patches.cv2_imshow`** | Utility used specifically within the Google Colab environment to display OpenCV images. |

### Installation

To run this project, you need to install OpenCV. If you are using Google Colab, the environment typically includes this library.

```bash
pip install opencv-python
