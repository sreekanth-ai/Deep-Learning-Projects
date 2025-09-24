Overview

This project uses a Convolutional Neural Network (CNN) trained on the FER-2013 dataset to detect human emotions from facial expressions in real-time using a webcam.

The model can classify faces into 7 emotions:

- 😡 Angry
- 🤢 Disgust
- 😨 Fear
- 😀 Happy
- 😢 Sad
- 😲 Surprise
- 😐 Neutral

⚙️ Features

- Train CNN model on FER2013 dataset
- Save & load trained model (.keras format)
- Real-time face detection with OpenCV
- Live emotion prediction using webcam

📂 Project Structure

emotion-detection/
- │── emotion_dection using CNN.ipynb       # Script to train CNN model
- │── emotion_model.keras    # Saved trained model
- │── emotion detion using open cv.ipynb    # Real-time webcam detection
- │── fer2013.csv            # Dataset (link or instructions to download)
- │── README.md              # Project documentation

Dataset

- This project uses the FER2013 dataset
- Contains 35,887 labeled face images (48×48 pixels)
- 7 emotion categories

🙌 Future Improvements

- Improve accuracy with deeper CNN / Transfer Learning (VGG16, ResNet)
- Use DNN-based face detection instead of Haar Cascades
- Deploy as a WebApp (Flask/Streamlit)

🤝 Contributing

Pull requests are welcome! If you’d like to improve the model or add new features, feel free to fork and contribute.
