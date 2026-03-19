# Lung-and-Colon-Cancer-Histopathological-Image-Dataset
Lung and Colon Cancer Histopathological Image Dataset, image classification using cnn
The dataset contains 25,000 images across five categories.
Categories:
    Lung: Adenocarcinoma (lung_aca), Benign (lung_n), and Squamous Cell Carcinoma (lung_scc).

    Colon: Adenocarcinoma (colon_aca) and Benign (colon_n).
    ----------------------------

    Frameworks: TensorFlow / Keras (Sequential CNN)

    Libraries: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn

Methodology

    Data Prep: Images are resized to 64x64 and normalized to a [0, 1] range.

    Processing: Labels are converted via one-hot encoding.

    Splitting: 80% Training, 20% Testing.

    Model: A Convolutional Neural Network (CNN) featuring Conv2D, MaxPooling2D, Dropout, and Dense layers, compiled with the Adam optimizer.

