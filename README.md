# Plant Disease Detection

## Overview
This project utilizes deep learning to classify plant leaves as **healthy** or **diseased** using RGB images. The model helps in early disease detection, enabling farmers and agronomists to take timely action to prevent crop losses.

## Features
- Image classification using deep learning
- Two models implemented:
  - **Convolutional Neural Network (CNN)**
  - **Fully Connected Neural Network (Dense Model)**
- Dataset containing diseased and healthy leaf images
- Achieved high accuracy with CNN

## Dataset
The dataset consists of two folders:
- **Healthy**: Images of green and healthy leaves
- **Diseased**: Images of leaves affected by plant diseases such as:
  - Apple Scab
  - Black Rot
  - Cedar Apple Rust

## Model Architectures
### 1. **Convolutional Neural Network (CNN)**
- Two convolutional layers (32 filters, 3×3 kernel, ReLU activation)
- Max pooling layers (2×2)
- Flattening layer
- Fully connected layers (64 neurons, softmax output)

### 2. **Fully Connected Neural Network (Dense Model)**
- Flattening layer
- Two dense layers (64 neurons, ReLU activation)
- Output layer (2 neurons, softmax activation)

## Training Results
| Model  | Training Accuracy | Validation Accuracy |
|--------|------------------|--------------------|
| CNN    | 97.62%           | 97.62%             |
| Dense  | 93.55%           | 92.31%             |

The CNN model performed better in detecting plant diseases and is recommended for use.

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/Plant-Disease-Detection.git
   cd Plant-Disease-Detection
2.Install dependencies:
   ```sh
    pip install -r requirements.txt
3.Run the Jupyter Notebook:
   ```sh
   jupyter notebook PlantDiseaseDetection.ipynb



## Dependencies
- Python 3.x
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib

## Future Improvements
- Add more plant disease categories
- Improve model generalization
- Deploy as a web or mobile app

## License
This project is open-source under the MIT License.
