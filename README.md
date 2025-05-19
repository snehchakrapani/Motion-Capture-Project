# Motion Capture Project

## Project Description

This project implements a **Motion Capture system** that tracks human body movements and translates them into animated characters in real time. It is designed to help in animation, gaming, virtual reality, and rehabilitation applications by capturing precise human motion data.

## How It Works

1. The system uses **webcam or sensor input** to capture the user's movements.
2. It processes the captured data to identify **key body points** and their motions using computer vision techniques.
3. The processed motion data is then used to animate a **3D model or avatar** in real time.
4. This project includes:
   - A Python module for capturing and processing motion data.
   - Integration with Unity to display the animated character based on the captured motions.

## Tools and Technologies Used

- **Python**: For motion data capture and processing.
- **OpenCV**: Library used for computer vision tasks.
- **Unity 3D**: A popular game engine used for rendering and animating the 3D avatar based on captured data.
- **Git & GitHub**: For version control and project collaboration.

## About Unity in This Project

Unity is used to create the 3D environment and animate the character. After processing motion data in Python, the data is sent to Unity (via files, network, or plugins), where the 3D model reacts and animates accordingly. Unity’s powerful tools help bring the motion capture data to life visually.

## How to Run the Project

1. **Clone the repository** to your local machine.
2. Install required Python libraries, such as OpenCV.
3. Run the Python script to start capturing motion.
4. Open the Unity project in the Unity Editor.
5. Connect the motion data output to the Unity model to see real-time animation.

## Optional: Adding Output Video

You can record the motion capture output as a video file using Python OpenCV’s video writer or Unity’s recording features. The output video files can be saved and added to this repository for demonstration.

---

## Contact

For questions or suggestions, contact sneh chakrapani at snehchakrapani2002@gmail.com.

