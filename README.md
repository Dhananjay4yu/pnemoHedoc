<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PneumoHedoc: Pneumonia Detection Using CNN</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f6f8;
      color: #333;
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
      color: #2c3e50;
    }
    pre {
      background: #ecf0f1;
      padding: 10px;
      border-radius: 6px;
      overflow-x: auto;
    }
    code {
      color: #e74c3c;
      font-weight: bold;
    }
    ul {
      padding-left: 20px;
    }
    a {
      color: #2980b9;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .section {
      margin-bottom: 40px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>PneumoHedoc: Pneumonia Detection Using CNN</h1>
    <p><strong>PneumoHedoc</strong> is a deep learning-based image classification project aimed at detecting pneumonia from chest X-ray images using Convolutional Neural Networks (CNNs). Built with the Keras Sequential API and powered by TensorFlow, this solution focuses on accurate, scalable, and modular pneumonia diagnosis support.</p>
    
    <div class="section">
      <h2>🔍 Key Features</h2>
      <ul>
        <li><strong>CNN Architecture:</strong> Custom CNN built using the Keras Sequential API for binary classification.</li>
        <li><strong>Data Preprocessing:</strong> Includes image augmentation (rotation, flipping, rescaling) and efficient loading via <code>ImageDataGenerator</code>.</li>
        <li><strong>Model Training:</strong> Supports class weighting, validation splits, and configurable batch sizes and epochs.</li>
        <li><strong>Evaluation Metrics:</strong> P
