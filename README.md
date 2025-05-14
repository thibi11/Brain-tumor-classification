
# 🧠 Brain Tumor Classification Using CNN & Gradio

This project uses a Convolutional Neural Network (CNN) to classify brain MRI images as either showing a tumor or not. A simple and interactive Gradio interface is built for user input and model prediction.  
It is implemented in **Google Colab** for easy accessibility.

---

## 📌 Features

- Classifies brain MRI images into **Tumor** or **No Tumor**
- Built using **TensorFlow/Keras**
- Web interface with **Gradio**
- Dataset loading, preprocessing, model training, and prediction in one Colab notebook

---

## 📁 Dataset

- MRI images classified into folders: `yes/` (tumor), `no/` (no tumor)
- Image preprocessing includes resizing, normalization, and grayscale conversion

---

## 🚀 How to Use (in Google Colab)

1. **Open the Colab Notebook**  
   Upload and open the `.ipynb` file in Google Colab.

2. **Install Dependencies**  
   All required Python libraries like TensorFlow, Gradio, NumPy, etc., are installed in the notebook.

3. **Train the Model**  
   The notebook trains a CNN model using the provided dataset.

4. **Launch Gradio UI**  
   Once trained, the model is connected to a Gradio interface where users can upload an MRI image and get a prediction.

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- Gradio
- Google Colab

---

## 📈 Model Summary

- Input: 150x150 grayscale MRI image
- Layers: Conv2D, MaxPooling2D, Flatten, Dense
- Output: Binary classification (Tumor / No Tumor)

---

## ✅ Example Output

The Gradio interface displays the uploaded MRI and returns a label like:  
```
🧠 Prediction: Tumor
```

---

## 📚 Conclusion

This project demonstrates how deep learning can be used for medical image classification.  
With Gradio and Colab, it becomes accessible and interactive for both learning and demonstration purposes.
