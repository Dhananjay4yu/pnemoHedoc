PneumoHedoc: Pneumonia Detection Using CNN
Project Overview
PneumoHedoc is a deep learning-based image classification project designed to detect pneumonia from chest X-ray images. This project implements a Convolutional Neural Network (CNN) using Keras with TensorFlow backend, trains it on a dataset of X-ray images.

Features
CNN model built with Keras Sequential API
Data preprocessing with image augmentation and batching
Model training with support for class weights, validation split, and batch iteration
Model evaluation using accuracy and loss metrics
Clean and modular Python code

Installation
Clone the repository:
git clone https://github.com/yourusername/pnemoHedoc.git
cd pnemoHedoc

Set up a Python virtual environment (recommended):
python -m venv myenv
source myenv/bin/activate        # On Windows: myenv\Scripts\activate

Install dependencies:
pip install -r requirements.txt

Training the Model
Modify and run the training script:
python model/train_model.py
This script defines the CNN architecture, compiles the model, and trains it on your dataset. Adjust parameters such as epochs, batch size, and data paths in the script.

Dataset
Use a public pneumonia chest X-ray dataset (e.g., Kaggle Pneumonia Dataset) or your own labeled dataset of images. Organize your data in subfolders for training and validation.

Troubleshooting
Large files error pushing to GitHub: Use .gitignore to exclude virtual environments and large binary files (e.g., model weights).
Activation attribute error: Ensure you use compatible versions of TensorFlow and Keras.
Streamlit app not loading: Confirm Streamlit is installed and run streamlit run app.py from the project root.

Future Work
Add multi-class classification (e.g., bacterial vs viral pneumonia)
Improve accuracy with transfer learning (e.g., using pre-trained ResNet or EfficientNet)
Deploy the app on cloud platforms like Heroku or AWS






