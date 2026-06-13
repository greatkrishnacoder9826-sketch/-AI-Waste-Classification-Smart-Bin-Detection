# ♻️ AI Waste Classification & Smart Bin Detection

An AI-powered waste classification system that uses a webcam and a trained TensorFlow/Keras model to identify different types of waste and display the correct disposal bin in real time.

## 📌 Overview

This project captures live video from a webcam, classifies the detected waste item using a machine learning model, and suggests the appropriate waste bin for disposal. The system provides a visual interface with waste images, bin images, and directional guidance.

The goal is to promote proper waste segregation and improve recycling efficiency through computer vision and machine learning.

---

## ✨ Features

- 🎥 Real-time webcam-based waste detection
- 🤖 TensorFlow/Keras image classification model
- ♻️ Automatic waste category recognition
- 🗑️ Smart bin recommendation system
- 🖼️ Visual overlay interface using OpenCV and CVZone
- ➡️ Arrow guidance for correct disposal bin
- ⚡ Fast and lightweight implementation

---

## 🛠️ Technologies Used

- Python
- OpenCV
- CVZone
- TensorFlow / Keras
- NumPy

---

## 📂 Project Structure

```text
AI-Waste-Classification/
│
├── keras_model.h5          # Trained classification model
├── labels.txt              # Class labels
├── main.py                 # Main application
│
├── Resources/
│   ├── background.png
│   ├── arrow.png
│   │
│   ├── Waste/
│   │   ├── waste_images...
│   │
│   └── Bins/
│       ├── bin_images...
│
└── README.md
🚀 Installation
1. Clone the Repository
git clone https://github.com/yourusername/AI-Waste-Classification.git
cd AI-Waste-Classification
2. Install Dependencies
pip install opencv-python
pip install cvzone
pip install tensorflow
pip install numpy

Or:

pip install -r requirements.txt
▶️ Usage

Run the main application:

python main.py

The webcam will start automatically and the system will:

Capture live video.
Detect and classify waste items.
Predict the waste category.
Display the correct disposal bin.
Show visual guidance on the screen.

Press Q to exit the application.

🧠 Waste Categories

The trained model can classify multiple waste categories and map them to their respective disposal bins.

Example categories:

Paper
Plastic
Metal
Glass
Organic Waste

(Actual categories depend on the labels used during model training.)

⚙️ How It Works
Webcam captures live frames.
Frame is sent to the trained Keras model.
Model predicts the waste class.
The predicted class is mapped to a bin category.
OpenCV and CVZone generate the visual interface.
User receives guidance for proper waste disposal.
🎯 Applications
Smart Recycling Systems
Educational Projects
Environmental Awareness Programs
Smart Cities
Waste Management Automation
🔮 Future Improvements
Object detection instead of image classification
Multiple object recognition
Mobile application integration
Cloud-based analytics dashboard
Voice guidance support
Improved model accuracy
🤝 Contributing

Contributions are welcome.

Fork the repository
Create a feature branch
git checkout -b feature-name
Commit your changes
git commit -m "Add new feature"
Push to GitHub
git push origin feature-name
Open a Pull Request
📜 License

This project is licensed under the MIT License.

👨‍💻 Author

Krishna Great

Passionate about Artificial Intelligence, Computer Vision, and Smart Automation Systems.

⭐ If you found this project useful, don't forget to star the repository!
