# 📸 Auto-Selfie with OpenCV  

![Auto Selfie](assets/auto-selfie.png)

This Python project uses OpenCV to capture selfies automatically when it detects a smiling face in the camera frame. It provides a fun and interactive way to take pictures with just a smile!  

## ✨ Features  

- Detects faces and smiles in real-time using OpenCV.  
- Captures selfies when a smiling face is detected.  
- Saves selfies with timestamps in PNG format.  
- Simple and interactive.  

## 📋 Prerequisites  

Before you begin, ensure you have met the following requirements:  

- Python (version 3.x recommended)  
- OpenCV (`pip install opencv-python`)  
- Haar cascades for face and smile detection (`haarcascade_frontalface_default.xml` and `haarcascade_smile.xml`)  

## 🚀 Getting Started  

1. Clone the repository:  
   ```sh
   git clone https://github.com/sid-lakhani/auto-selfie.git
   cd auto-selfie
   ```  
2. Install the required Python packages:  
   ```sh
   pip install opencv-python
   ```  
3. Download the Haarcascade XML files for face and smile detection and place them in the project directory.  
4. Run the script:  
   ```sh
   python main.py
   ```  

## 📷 Usage Steps  

1. **Start the script** – Launch the program by running:  
   ```sh
   python main.py
   ```  
2. **Smile at the camera** – The program continuously detects faces and smiles in real time.  
3. **Selfie Capture** – As soon as a smile is detected, the selfie is automatically taken.  
4. **Save & View** – The image is saved in the project directory with a timestamp.  
5. **Exit the program** – To close the camera and stop the script, press the `q` key.

## 🔮 Future Scope  
 
- **Pose Estimation** – Integrate pose detection to capture selfies only when a user strikes a specific pose.  
- **Gesture-Based Capture** – Allow users to trigger selfies using hand gestures instead of just smiles.  
- **AI-Based Image Enhancement** – Apply AI-powered enhancements like automatic brightness correction and noise reduction.  
- **Multi-Person Smart Framing** – Automatically adjust the frame and focus based on the number of people in view.

## 🤝 Contributing  

Contributions are welcome! Here’s how you can contribute:  

1. **Fork the repository** on GitHub.  
2. **Create a new branch** (`git checkout -b feature-name`).  
3. **Make your changes** and commit (`git commit -m "Add new feature"`).  
4. **Push to GitHub** (`git push origin feature-name`).  
5. **Open a pull request** to merge your changes.  

## 📜 License  

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
