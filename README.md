# 🧠 Text Detection using EasyOCR and OpenCV

This is a simple Python project that detects text in images using [EasyOCR](https://github.com/JaidedAI/EasyOCR) and [OpenCV](https://opencv.org/). It reads an image, detects any visible text, and highlights the detected words with bounding boxes.

---

## 📸 Example Output

The script:
- Reads an image
- Detects English text
- Draws green boxes around the text
- Labels each word with the detected text in blue
- Displays the final image using Matplotlib

---

## 🔧 Requirements

Before running the script, install the following Python libraries:

```bash
pip install easyocr opencv-python matplotlib

