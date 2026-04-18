
Dataset
This project utilizes the Mango Leaf Disease Dataset from Kaggle:
https://www.kaggle.com/datasets/aryashah2k/mango-leaf-disease-dataset

Note on Analysis Video
Due to the high-resolution screen recording (200MB) exceeding direct upload limits, the full project walkthrough and analysis video is available on LinkedIn.
https://www.linkedin.com/posts/sachin-tewari-29ab32381_deeplearning-ai-computervision-ugcPost-7450899314794717184-85dz?utm_source=share&utm_medium=member_android&rcm=ACoAAF5RVhYB-FP4DACo_GNFdA8SsF5Wmzp2FFE

pip install tensorflow numpy pandas scikit-learn pillow matplotlib

Key Libraries Used:
TensorFlow/Keras: For building and training the CNN model architecture.
Scikit-learn: For Label Encoding and data splitting (training/validation sets).
Pillow (PIL): For image loading, resizing (150x150), and preprocessing.
NumPy & Pandas: For array manipulation and data handling.
Matplotlib: For plotting training history (Accuracy and Loss curves).

Technical Specifications
Deep Learning: Custom CNN Architecture (32, 64, 128 filters).
Processing: Image normalization (1/255) and resizing (150x150).
Performance: ~92% Training Accuracy | ~90% Validation Accuracy.

Usage
Open the mango_disease_le.ipynb in Google Colab.
Mount Google Drive and load the Kaggle dataset.
Run the inference cell to upload a leaf image.
The system will output the disease name and its remedy in both English and Hindi.
