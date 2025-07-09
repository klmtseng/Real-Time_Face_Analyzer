Real-Time Face Analyzer
A web-based tool that uses your webcam to perform real-time face analysis. This application detects multiple faces and provides estimations for age, gender, and experimental skin quality metrics like texture, tone evenness, and brightness.
You can replace the placeholder above with a real screenshot of your app!
Features
Multi-Face Detection: Analyzes all faces detected in the camera's view simultaneously.
Smoothed Age & Gender Estimation: Provides a stabilized age estimate by averaging results and rejecting outliers.
Detailed Skin Analysis (Experimental):
Texture: Measures the smoothness of the skin.
Tone Evenness: Analyzes the consistency of skin coloration.
Brightness: Measures the lighting on the facial regions.
Tech Stack
HTML5
Tailwind CSS for styling.
JavaScript for application logic.
face-api.js for the core machine learning models (face detection, landmarks, age, and gender).
How to Use
Clone or download this repository.
Open the index.html file in a modern web browser that supports webcam access (like Chrome or Firefox).
Grant the browser permission to use your camera when prompted.
The application will load the models and begin the analysis.
Disclaimer
This tool provides estimations for entertainment and educational purposes only. It is not a medical diagnostic tool. All skin analysis is experimental and highly dependent on factors like camera quality and lighting conditions.
