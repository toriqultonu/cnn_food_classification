<h1 align="center" id="title">CNN Base Food Image Classification with Pytorch</h1>

<p align="center"><img src="https://raw.githubusercontent.com/toriqultonu/cnn_food_classification/main/__pycache__/cnn_food_classification.png" alt="project-image"></p>

<p id="description">This project implements a Convolutional Neural Network (CNN) using the PyTorch framework for food image classification. The model is trained to classify images into three categories: pizza steak and sushi. It's designed to showcase the capabilities of deep learning in recognizing and categorizing different types of food.</p>

<p align="center"><img src="https://img.shields.io/badge/python-3.10-black?labelColor=blue" alt="shields"><img src="https://img.shields.io/badge/Pytorch-1.13%2B-black" alt="shields"></p>

<h2>Project Screenshots:</h2>

<img src="https://raw.githubusercontent.com/toriqultonu/cnn_food_classification/main/__pycache__/steak.PNG" alt="project-screenshot" width="100" height="300/">

<img src="https://raw.githubusercontent.com/toriqultonu/cnn_food_classification/main/__pycache__/curve.png" alt="project-screenshot" width="300" height="100/">

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   CNN Architecture: Utilizes a deep convolutional neural network architecture for effective feature extraction from food images.
*   Multi-Class Classification: Trained to classify images into three distinct food categories: pizza steak and sushi.
*   PyTorch Implementation: Written in PyTorch allowing for easy modification extension and integration into other PyTorch-based projects.
*   Dataset: The model is trained on a curated dataset containing diverse images of pizzas steaks and sushi.

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the Repository:</p>

```
git clone https://github.com/toriqultonu/cnn_food_classification.git
```

<p>2. Install Dependencies:</p>

```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```

<p>3. Train the Model:</p>

```
python train.py
```

<p>4. Use the trained model for inference on new food images by running:</p>

```
python main.py --image_path path/to/your/image.jpg
```

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Pytorch
*   python-3.10

<h2>🛡️ License:</h2>

This project is licensed under the MIT License

<h2>🍰 Contribution Guidelines:</h2>

Follow the PEP 8 style guide for Python code. Maintain a consistent coding style with the existing codebase. Comment your code when necessary to ensure clarity and understanding.
