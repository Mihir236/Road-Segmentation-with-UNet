🛣️ Road Segmentation with U-Net

This project implements road segmentation using a U-Net deep learning architecture. The goal is to accurately identify and segment road regions from aerial or satellite images to support autonomous driving, road planning, and mapping applications.

🚀 Features

Implements U-Net architecture for pixel-level segmentation

Trained on aerial/satellite imagery dataset

Includes data preprocessing, model training, and evaluation

Visualizes segmentation masks vs ground truth results

Supports custom datasets for road extraction tasks

🧠 Technologies Used

Python, TensorFlow / Keras

NumPy, OpenCV, Matplotlib

Jupyter Notebook

📈 Results

High accuracy in detecting and segmenting road surfaces

Visual comparisons of predicted and actual segmentation masks

road-segmentation-with-unet/
│
├── road-segmentation-with-unet.ipynb   # Main implementation notebook
├── data/                               # Dataset (images and masks)
├── models/                             # Saved model weights
└── README.md                           # Project documentation

⚙️ How to Run

Clone this repository

Install dependencies:

pip install -r requirements.txt


Open and run the notebook:

jupyter notebook road-segmentation-with-unet.ipynb
