<h1 align="center">🫁 PneumoHedoc: Pneumonia Detection Using CNN</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue" alt="Python Version">
  <img src="https://img.shields.io/badge/Framework-Keras%20%7C%20TensorFlow-orange" alt="Framework">
</p>

<p align="center">
  A deep learning-powered system to detect pneumonia from chest X-ray images using CNNs. Built with the Keras Sequential API for accurate, scalable, and modular diagnosis support.
</p>

<hr>

<h2>🔍 Key Features</h2>
<ul>
  <li><b>CNN Architecture:</b> Custom Convolutional Neural Network built with Keras Sequential API for binary classification.</li>
  <li><b>Data Preprocessing:</b> Image augmentation (rotation, flipping, rescaling) using <code>ImageDataGenerator</code>.</li>
  <li><b>Model Training:</b> Includes:
    <ul>
      <li>Class weights for data imbalance</li>
      <li>Validation split</li>
      <li>Configurable batch size and epochs</li>
    </ul>
  </li>
  <li><b>Evaluation Metrics:</b> Accuracy and loss plots for performance tracking.</li>
  <li><b>Modular Codebase:</b> Clean and readable Python modules for training, preprocessing, and inference.</li>
</ul>

<hr>

<h2>⚙️ Installation & Setup</h2>

<pre><code>git clone https://github.com/yourusername/pnemoHedoc.git
cd pnemoHedoc

# Create a virtual environment
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
</code></pre>

<hr>

<h2>🚀 Model Training</h2>

<pre><code>python model/train_model.py</code></pre>

<p>The training script handles:</p>
<ul>
  <li>Defining the CNN architecture</li>
  <li>Compiling with <code>Adam</code> optimizer and <code>binary_crossentropy</code> loss</li>
  <li>Training with custom batch size, learning rate, and data paths</li>
</ul>

<p><i>All hyperparameters can be modified inside <code>train_model.py</code></i></p>

<hr>

<h2>🔮 Future Enhancements</h2>
<ul>
  <li><b>Multi-class Classification:</b> Extend to detect bacterial vs. viral pneumonia.</li>
  <li><b>Transfer Learning:</b> Use ResNet, EfficientNet, or MobileNet for improved accuracy.</li>
  <li><b>Deployment:</b> Deploy via Streamlit on Heroku, AWS, or Streamlit Cloud.</li>
</ul>

<hr>

<h2>📂 Folder Structure</h2>

<pre><code>pnemoHedoc/
├── data/
│   ├── train/
│   ├── val/
├── model/
│   └── train_model.py
├── utils/
│   └── preprocess.py
├── requirements.txt
└── README.md
</code></pre>

<hr>

<p align="center">💙 Built with passion for saving lives through technology 💙</p>
