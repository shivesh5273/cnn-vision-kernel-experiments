# CNN Vision Kernel Experiments

This project explores core concepts of computer vision using Convolutional Neural Networks (CNNs). The work involves implementing edge detection, tuning CNN architectures, and testing real handwritten digits using Keras and TensorFlow.

---

## 🔍 Key Challenges

### 🐱 1. Edge Detection
- Implemented the Laplacian operator to detect edges in a downloaded cat image.
- Used discrete Laplacian filters on grayscale images.

### 🧠 2. CNN Architecture Modifications (MNIST)
- Modified kernel sizes of 2nd and 3rd Conv layers to (4,4).
- Detailed trainable parameter breakdown provided with model summary.

### 📊 3. Kernel Experimentation (3x3 to 6x6)
- Evaluated how kernel size impacts accuracy and model performance.
- Recorded accuracy for various filters and selected best-performing configuration.

### ✍️ 4. Custom Handwriting Test
- Created 18 images of handwritten digits (0–8).
- Tested CNN model performance on this tiny dataset.
- Compared accuracy with prior evaluations.

### 📁 5. Executed Lab Notebooks
- Ran full code from `Lab04a-introduction-to-convnets.ipynb` and `Lab04b_ReadImages.ipynb`.

---

## 📁 Files Included

- `cnn-experiments.ipynb` — full implementation of problems 1–4
- `cnn-experiments.html` — HTML version for viewing outputs
- `cnn-vision-kernel-experiments-overview.docx` — problem statements
- `cnn-labs-lab04a-lab04b.zip` — lab notebooks fully executed

---

## 🛠 Tools Used

- Python 3.x  
- TensorFlow / Keras  
- OpenCV / PIL (for image processing)  
- Jupyter Notebook  
- Custom image data collection

---

> Practicing architecture tuning, visualization, and experimentation with CNNs helped reinforce model intuition and edge behavior.
