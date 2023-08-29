# NeuroScan-Detecting-Brain-Tumors-with-CNN-powered-MRI-Analysis

## About the Dataset:

The dataset consists of 253 files containing Brain MRI (Magnetic Resonance Imaging) scans. MRI is a non-invasive medical imaging technique that provides detailed images of the brain's internal structures. These images are captured using strong magnetic fields and radio waves, allowing for the visualization of various tissues within the brain.

The dataset is labelled with two distinct classes:

- **No Tumor:** This class represents brain MRI scans from individuals who do not have any detectable brain tumours. These scans serve as the baseline for comparison against scans with tumours.

- **Tumor:** This class includes brain MRI scans from individuals who have been diagnosed with brain tumours. Tumors in the brain can vary in size, location, and type, which makes their accurate detection and classification a challenging task.

Each MRI scan file in the dataset likely contains a 3D array of pixel intensity values that represent different tissue types and structures within the brain. These arrays can be used as input data for various machine learning algorithms, such as Convolutional Neural Networks (CNNs), to learn patterns associated with the presence or absence of brain tumours.

## Objective:

The primary objective of this project is to develop a machine learning model, specifically a Convolutional Neural Network (CNN) using the Keras framework, to accurately detect the presence of brain tumors in MRI scans. The CNN architecture is chosen due to its effectiveness in processing image data and capturing intricate patterns. The successful implementation of this project can contribute to medical diagnosis and treatment planning for patients with brain tumours.
