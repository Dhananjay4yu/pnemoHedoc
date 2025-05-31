<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PneumoHedoc - Pneumonia Detection</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, sans-serif;
      background-color: #f9fafb;
      color: #2d3748;
      margin: 0;
      padding: 20px;
    }
    .container {
      max-width: 900px;
      margin: auto;
      background: #fff;
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    h1, h2, h3 {
      color: #1a202c;
      border-bottom: 2px solid #e2e8f0;
      padding-bottom: 5px;
    }
    pre {
      background: #f1f5f9;
      padding: 10px;
      border-radius: 6px;
      overflow-x: auto;
    }
    code {
      font-weight: bold;
      color: #d6336c;
    }
    ul {
      padding-left: 20px;
    }
    .note {
      background-color: #e9f5ff;
      padding: 10px;
      border-left: 4px solid #3182ce;
      margin: 20px 0;
      border-radius: 5px;
    }
    .important {
      background-color: #fff3cd;
      padding: 10px;
      border-left: 4px solid #ffae42;
      margin: 20px 0;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>PneumoHedoc: Pneumonia Detection Using CNN</h1>
    <p>
      <strong>PneumoHedoc</strong> is a deep learning-based image classification project designed to detect pneumonia from chest X-ray images using Convolutional Neural Networks (CNNs). It’s built using the Keras Sequential API and powered by TensorFlow for modular, scalable, and accurate diagnosis support.
    </p>

    <h2>🔍 Key Features</h2>
    <ul>
      <li><strong>CNN Architecture:</strong> Custom CNN built with Keras Sequential API for binary classification (Pneumonia vs Normal).</li>
      <li><strong>Data Preprocessing:</strong> Includes image augmentation (rotation, flipping, rescaling) and batch loading via <code>ImageDataGenerator</code>.</li>
      <li><strong>Model Training:</strong> Supports:
        <ul>
          <li>Class weights for data imbalance</li>
          <li>Validation split</li>
          <li>Configurable batch size and epochs</li>
        </ul>
      </li>
      <li><strong>Evaluation Metrics:</strong> Accuracy and loss tracked using real-time plots.</li>
      <li><strong>Modular Codebase:</strong> Separate Python modules for preprocessing, training, and inference.</li>
    </ul>

    <h2>⚙️ Installation & Setup</h2>
    <ol>
      <li>Clone the repository:
        <pre><code>git clone https://github.com/yourusername/pnemoHedoc.git
cd pnemoHedoc</code></pre>
      </li>
      <li>Create and activate a virtual environment:
        <pre><code>python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate</code></pre>
      </li>
      <li>Install the required dependencies:
        <pre><code>pip install -r requirements.txt</code></pre>
      </li>
    </ol>

    <h2>🚀 Model Training</h2>
    <p>Run the training script after configuring parameters inside <code>train_model.py</code>:</p>
    <pre><code>python model/train_model.py</code></pre>
    <p>This script:</p>
    <ul>
      <li>Defines the CNN architecture</li>
      <li>Compiles the model using Adam optimizer and binary crossentropy loss</li>
      <li>Trains the model with customizable settings (batch size, learning rate, data paths)</li>
    </ul>

    <h2>🌱 Future Enhancements</h2>
    <ul>
      <li><strong>Multi-class Classification:</strong> Extend to differentiate bacterial vs viral pneumonia.</li>
      <li><strong>Transfer Learning:</strong> Use pre-trained models like <code>ResNet</code>, <code>EfficientNet</code>, or <code>MobileNet</code>.</li>
      <li><strong>Deployment:</strong> Build a Streamlit-based web app and deploy on <code>Heroku</code>, <code>AWS</code>, or <code>Streamlit Cloud</code>.</li>
    </ul>

    <div class="note">
      <strong>Note:</strong> You can easily modify the architecture and training settings inside <code>train_model.py</code> for experimentation and optimization.
    </div>
  </div>
</body>
</html>
