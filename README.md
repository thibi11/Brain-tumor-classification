# Brain Tumor Classification - Naan Mudhalvan Project

This project is developed as part of the **Naan Mudhalvan** skill development program under the subject **Deep Learning**. It focuses on classifying brain tumors from MRI images using a Convolutional Neural Network (CNN) and providing predictions through an interactive Gradio interface.

## Introduction

Brain tumor detection and classification from MRI scans is a critical task in medical imaging. In this project, a deep learning model is trained to categorize brain MRI images into four classes:

- Glioma  
- Meningioma  
- Pituitary Tumor  
- No Tumor  

The model is integrated with Gradio, allowing users to upload MRI images and receive predictions instantly through a simple web interface.

## Project Structure

- `brain_tumor_classification.ipynb` – Jupyter Notebook with code for data loading, model training, and Gradio integration.
- `README.md` – Project documentation.
- Dataset path is assumed to be in Google Drive at:  
  `/content/drive/MyDrive/Brain Tumor Segmentation/Training/`

## Technologies Used

- Python  
- Google Colab  
- TensorFlow & Keras (Deep Learning)  
- OpenCV (Image Preprocessing)  
- Scikit-learn (Preprocessing & Splitting)  
- Gradio (Web Interface)  
- NumPy (Data Handling)

## How to Run

1. Open the notebook in **Google Colab**:  
   👉 [Click here to open in Colab](https://colab.research.google.com/github/Kokisha2004/Brain-Tumor-Classification/blob/main/brain_tumor_classification.ipynb)  
2. Mount your **Google Drive** if your dataset is stored there.  
3. Run all cells to load the data, train the model, and launch the Gradio interface.  
4. Use the interface to upload MRI images and classify tumor type.

## Future Enhancements

- Improve prediction accuracy with deeper or pretrained CNN architectures.  
- Add data augmentation for better generalization.  
- Deploy the Gradio app online for global accessibility.

## License

This project is developed for educational purposes under the **Naan Mudhalvan** initiative.
