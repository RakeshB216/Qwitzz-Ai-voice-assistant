# Qwitzz Voice Assistant

A voice-activated assistant with a Flask backend and React frontend, providing features like weather updates, Wikipedia search, fitness tips, emergency contacts, and object detection.

## Features
- Weather updates via web scraping
- Wikipedia search
- Fitness and wellness tips
- Phone calls and WhatsApp messaging via Twilio
- Emergency contact protocol
- Object detection using OpenVINO
- Water intake reminders

## Project Structure
![image](https://github.com/user-attachments/assets/b0b3157b-69e4-4c5f-8106-1fdee239888d)

## Setup Instructions

### Backend
1. Navigate to `backend/`.
2. Create a virtual environment and activate it.
3. Install dependencies: `pip install -r requirements.txt`.
4. Create a `.env` file with Twilio credentials:

![image](https://github.com/user-attachments/assets/61cf963f-b662-4f34-959a-547f96f35c6e)

5. Run the backend: `python app.py`.

### Frontend
1. Navigate to `frontend/`.
2. Install dependencies: `npm install`.
3. Run the frontend: `npm start`.

## Model Files
- The `backend/model/` directory contains large OpenVINO model files, which are not included in this repository due to size.
- Download the `ssdlite_mobilenet_v2` model from [Open Model Zoo](https://storage.openvinotoolkit.org/) and place it in `backend/model/`.
