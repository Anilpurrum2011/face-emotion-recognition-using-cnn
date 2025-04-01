# Face Emotion Recognition using CNN

## Overview
The **Face Emotion Recognition System** is a deep learning-based application that detects and classifies human emotions from facial expressions using **Convolutional Neural Networks (CNN)**. The system processes real-time or static images to identify emotions such as happy, sad, angry, surprised, and more.

## Features
- Real-time emotion detection using a webcam
- Emotion classification from static images
- Deep learning model trained on facial emotion datasets
- User-friendly interface for interaction
- Efficient and optimized CNN model
 
## Tech Stack
- **Backend:** Python, Flask
- **Frontend:** HTML, CSS, JavaScript
- **Machine Learning:** TensorFlow, Keras, OpenCV
- **Database:** N/A (model-based prediction)
- **Deployment:** Flask Server

## Installation
### Prerequisites
Ensure you have the following installed:
- Python (>= 3.8)
- pip
- Virtual Environment (optional but recommended)
- OpenCV
- TensorFlow/Keras

### Steps to Set Up
1. **Clone the Repository**
   ```sh
   git clone https://github.com/Anilpurrum2011/face-emotion-recognition-using-cnn.git
   cd face-emotion-recognition-using-cnn
   ```

2. **Create and Activate Virtual Environment (Optional but Recommended)**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the Application**
   ```sh
   python app.py
   ```
   The application should now be running at `http://127.0.0.1:5000/`

## Usage
1. Open the web application at `http://127.0.0.1:5000/`
2. Upload an image or use the webcam
3. The system detects facial expressions and classifies emotions


## Folder Structure
```
face-emotion-recognition-using-cnn/
│── main.py                                        # Main application file
│── model_78.weights.h5                            # Pre-trained deep learning model
│── Face_Emotion_Recognition_Anish_Johnson.ipynb   # python file
│── haarcascade_frontalface_default.xml            # Haarcascade xml file
│── model_78.h5                                    # pre-trained model
│── README.md                                      # Documentation
```

## Future Enhancements
- Improve accuracy with deeper CNN architectures
- Deploy on cloud platforms (AWS, GCP, Heroku)
- Add support for more emotion categories
- Integrate with social media APIs for real-time emotion tracking

## Contributors
- **Anil Purrum** - [GitHub Profile](https://github.com/Anilpurrum2011)

## License
This project is licensed under the MIT License.

## Contact
For queries, contact **Anil Purrum** via [GitHub Issues](https://github.com/Anilpurrum2011/face-emotion-recognition-using-cnn/issues).
