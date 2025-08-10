# Fall Detection System

A machine learning project that detects human falls from video streams or image sequences using pre-trained deep learning models.  
Optimized for CPU-only environments for efficient and real-time deployment.

## 📌 Features
- Uses pre-trained models (e.g., MobileNet, Tiny YOLO, PoseNet)
- Detects human falls from video inputs
- Outputs processed video with detection results
- Lightweight and optimized for CPU-only systems
- Implemented in Google Colab

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Libraries:** OpenCV, NumPy, TensorFlow / PyTorch (depending on model), Matplotlib
- **Frameworks/Models:** MobileNet / Tiny YOLO / PoseNet
- **Tools:** Google Colab

## 📂 Project Structure
├── Untitled20_final.ipynb # Main Jupyter Notebook with implementation

├── README.md # Project documentation

├── .gitignore # Ignored files for Git

Upload your video file in the notebook environment.

Run the cells to process the video and detect falls.

The output video will be saved for download.

📈 Model Workflow
1.Video Input → 2. Frame Extraction → 3. Pose Detection / Object Detection →

4.Fall Detection Logic → 5. Output Video with Results
