Wildeye – Smart Surveillance System for Forest and Wildlife Protection

Wildeye is a surveillance-based project developed to improve safety in forest areas. The main goal is to detect and respond to unusual activities such as human intrusion, animal movement, and gunshot sounds in real time.

In many forest regions, continuous manual monitoring is difficult. This system reduces that dependency by using computer vision and audio analysis to automatically observe and identify potential threats.

What the system does
detects humans and animals using real-time video input
identifies gunshot-like sounds using audio processing
provides continuous monitoring
helps in early detection of threats
reduces the need for constant human supervision
Technologies used
Python for backend processing
OpenCV for handling video input
YOLO (v5/v8) for object detection
basic audio processing for gunshot detection
Flutter for frontend interface
Project structure

mini_project_cpy

backend → core logic, detection models, and processing
frontend → user interface built using Flutter
requirements.txt → required Python libraries
How to run the project
Clone the repository
git clone https://github.com/Nithya2810/Wildeye.git
Navigate to the folder
cd Wildeye
Create and activate virtual environment
python -m venv win_env
win_env\Scripts\activate
Install dependencies
pip install -r mini_project_cpy/requirements.txt
Run the backend script
python mini_project_cpy/backend/wildeye.py
Important note

The trained model files (.pt) are not included in this repository due to size limitations.

Download the required models and place them in:
mini_project_cpy/backend/models/

Possible improvements
real-time alert system (SMS/email)
cloud-based monitoring
database for storing logs
improving detection accuracy with better models
Author

Nithya Sri G
