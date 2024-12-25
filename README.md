# SignSpeak: American Sign Language to Text Conversion

## Overview
SignSpeak is a real-time system that translates American Sign Language (ASL) gestures into textual output. It is designed to bridge the communication gap between the hearing and speech-impaired communities and the broader audience. The project leverages computer vision, machine learning, and natural language processing to provide accurate and user-friendly gesture recognition.

## Features
- **Model Integration**: Custom-trained CNN model using Keras, achieving 91% accuracy on a validation dataset of 16,000 images.
- **Real-Time Gesture Recognition**: Processes live video frames with OpenCV, incorporating adaptive thresholding and noise reduction techniques to minimize misclassifications by 30%.
- **Interactive GUI**: Built with Tkinter, the interface displays live video feed, gesture predictions, word formations, and real-time sentence suggestions.
- **Language Accuracy**: Hunspell integration ensures 95% precision for spell-checking and word suggestions, reducing spelling errors by 25%.

## Technology Stack
### Machine Learning
- TensorFlow/Keras for building and training the CNN model
- Adaptive thresholding and noise reduction for preprocessing

### Tools and Libraries
- OpenCV for real-time video capture and frame processing
- Hunspell for spell-checking and word suggestion
- Tkinter for GUI development

### Deployment
- Python environment for seamless integration of tools and libraries

## Prerequisites
- Python 3.8+
- NVIDIA GPU (for accelerated processing)
- Libraries: TensorFlow, OpenCV, Tkinter, Hunspell, NumPy

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/SignSpeak.git
   cd SignSpeak
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up the Hunspell spell-checker:
   - Install Hunspell for your operating system.
   - Configure the `hunspell` library in the project.

4. Run the application:
   ```bash
   python main.py
   ```

## Dataset
The dataset consists of:
- **Training Data**: 16,000 grayscale images of ASL gestures, preprocessed with data augmentation techniques.
- **Testing Data**: 4,000 grayscale images for validation.

Ensure the dataset is placed in the `dataSet` folder under `trainingData` and `testingData` directories.

## Usage
1. Launch the application:
   ```bash
   python main.py
   ```
2. Use the GUI to view live video feed, detect ASL gestures, and convert them to text.
3. Leverage real-time sentence suggestions and spell-checking for improved accuracy.



