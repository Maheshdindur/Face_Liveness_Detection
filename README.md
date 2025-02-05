# **Face Liveness Detection** 🎭  

## **📌 Overview**  
This project implements a **real-time face liveness detection system** that captures input from a camera and determines whether the face is real or spoofed. It helps prevent spoofing attempts using printed photos, videos, or masks in authentication systems.  

## **🚀 Features**  
- 📷 **Real-time face liveness detection** using a webcam  
- 🔍 **Distinguishes real faces from spoof attacks** (photos/videos/masks)  
- ⚡ **Lightweight and efficient for real-time use**  

## **🛠️ Technologies Used**  
- **Python** 🐍  
- **OpenCV** 👁️ (for image processing)  
- **TensorFlow/Keras** 🤖 (for model training)  
- **Scikit-learn** 📊 (for feature extraction & classification)  

## 📂 **Project Structure**  

📁 **Face-Liveness-Detection**  
├── 📂 **models**              # Trained ML model  
├── 📄 **README.md**           # Project documentation  
├── 📜 **requirements.txt**    # Required dependencies  
├── 💻 **Face_Antispoofing.ipynb**   # Main script to run detection  
└── 🎥 **liveness_net.py**      # Real-time detection script  


## **📌 How It Works**
- **The system captures live frames from the webcam.**
- **It processes the frame and extracts features.**
- **A trained machine learning model classifies the face as real or spoof.**
- **The result is displayed directly in the camera interface.**
## **📸 Demo**
You can watch the demo video below:

<video width="320" height="240" controls>
  <source src="https://github.comMaheshdindur/Face_Liveness_Detection/blob/main/assets/VID_20250205125201.mp4?raw=true" type="video/mp4">
  Your browser does not support the video tag.
</video>


