 ✋ Sign Language Detection System

A real-time Sign Language Detection and Recognition System built using Python, OpenCV, MediaPipe, and Deep Learning. This project captures hand gestures through a webcam, extracts hand landmarks, and predicts sign language gestures using a trained neural network model.

This project is suitable for:

 Academic / college projects
 Computer Vision beginners
 Assistive technology demonstrations



 📌 Features

 Real-time hand detection using MediaPipe Hands
 Dataset collection using webcam
 Gesture classification using a trained deep learning model
 Modular and easy-to-understand code structure
 Works on standard webcams



 🛠️ Tech Stack

 Programming Language: Python 3
 Libraries & Frameworks:

   OpenCV
   MediaPipe
   NumPy
   TensorFlow / Keras
 IDE: VS Code / Any Python IDE



 📂 Project Structure


SignLanguage-Detection/
│
├── app.py                 Main application file (real-time detection)
├── function.py            Helper functions (MediaPipe, drawing, preprocessing)
├── collectdata.py         Script to collect gesture data using webcam
├── data.py                Dataset handling and label processing
├── trainmodel.py          Model training script
├── model.json             Saved model architecture
├── model.h5               Trained model weights
├── image/                 Images / assets
├── Logs/                  Training logs (ignored in git)
├── MP_Data/               Collected landmark data (ignored in git)
├── requirements.txt       Project dependencies
└── README.md              Project documentation




 ⚙️ Installation & Setup

 1️⃣ Clone the Repository

bash
git clone https://github.com/dishak23/SignLanguage-Detection.git
cd SignLanguage-Detection


 2️⃣ Create Virtual Environment (Recommended)

bash
python -m venv venv


Activate:

 Windows:

bash
venv\Scripts\activate


 Linux / macOS:

bash
source venv/bin/activate


 3️⃣ Install Dependencies

bash
pip install -r requirements.txt




 ▶️ How to Run

 🔹 Collect Training Data

bash
python collectdata.py


 🔹 Train the Model

bash
python trainmodel.py


 🔹 Run Real-Time Detection

bash
python app.py


Make sure your webcam is connected.



 🧠 How It Works

1. Webcam captures hand gestures
2. MediaPipe extracts 21 hand landmarks
3. Landmarks are preprocessed and passed to the trained model
4. Model predicts the corresponding sign
5. Result is displayed in real-time



 📸 Sample Output

> Real-time webcam feed with detected hand landmarks and predicted sign label.



 🚀 Future Enhancements

 Add support for more gestures
 Convert to full sentence recognition
 Deploy as a web or mobile application
 Improve accuracy using CNN / LSTM models



 👩‍💻 Author

Disha Karmakar
GitHub: [https://github.com/dishak23](https://github.com/dishak23)



 📄 License

This project is for educational purposes. Feel free to use and modify it for learning and academic use.
