**Overview**
    SignSpeak is an AI-powered system for translating American Sign Language (ASL) gestures into text in real time, leveraging advanced computer vision and natural language processing techniques.

**Key Features**
    Custom CNN Model: Trained with Keras, achieving 91% accuracy on a validation set of 16,000 images.
    Real-Time Gesture Recognition: Processes video frames using OpenCV with adaptive thresholding, reducing misclassification rates by 30%.
    Interactive GUI: Tkinter-based interface for live feed display, word formation, and sentence suggestions.
    Linguistic Accuracy: Integrated Hunspell for spell-checking and suggestions, achieving 95% precision and a 25% reduction in errors.
**Tech Stack**
    Programming Language: Python
    Frameworks & Libraries: Keras, OpenCV, Tkinter, Hunspell
    Tools: TensorFlow, NumPy
**How It Works**
    Captures live video frames and detects gestures in the ROI.
    Preprocesses gestures using adaptive thresholding and noise reduction.
    Predicts characters via the CNN model and forms words dynamically.
    Refines text with spell-checking and suggestions using Hunspell.
