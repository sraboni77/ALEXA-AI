
# ALEXA-AI
RESEARCH PAPER 
https://docs.google.com/document/d/1wlliLgXJPZQrAddSoRayYOE4ZTe4TA_-/edit?usp=drivesdk&ouid=100458552978499837577&rtpof=true&sd=true

# 🔊 AI Voice Assistant (Alexa Clone)

A Python-based voice assistant that responds to voice commands such as playing YouTube songs, telling time, searching Wikipedia, cracking jokes, and answering basic questions.



 Author  
Sraboni Akter  
Student ID: 213071018  
GitHub: [sraboni77](https://github.com/sraboni77)  
University: Shanto-Mariam University of Creative Technology



 Features

 Play YouTube videos by voice command  
 Tell the current time  
 Fetch summary information from Wikipedia  
 Tell jokes using `pyjokes`  
 Respond to fun personal questions  
 Listens for "Alexa" in commands before responding  



 Technologies Used

 Python 3.x  
speech_recognition` for voice input  
pyttsx3` for text-to-speech  
pywhatkit` to play YouTube videos  
wikipedia` API for fetching information  
pyjokes` for jokes  
pyaudio` for microphone access  


Required Python Packages

Before running the project, install the following packages:

bash
pip install SpeechRecognition
pip install pyttsx3
pip install pywhatkit
pip install wikipedia
pip install pyjokes
pip install pyaudio


Note: If pyaudio fails to install, run:
bash
pip install pipwin
pipwin install pyaudio




 How to Run This Project

1. Clone the repository 
bash
git clone https://github.com/sraboni77/alexa-ai.git
cd alexa-ai


2. Install required packages 
bash
pip install -r requirements.txt


3. Run the main file
bash
python main.py


4. Speak a command starting with "Alexa" 
   Examples:  
   Alexa play Shape of You  
   Alexa what’s the time  
   Alexa who the heck is Einstein  
   Alexa tell me a joke



Sample Voice Commands

| Voice Command                 | Functionality                |
|------------------------------|------------------------------|
| Alexa play Believer          | Plays song on YouTube        |
| Alexa what time is it        | Tells the current time       |
| Alexa who the heck is Newton | Gives Wikipedia info         |
| Alexa tell me a joke         | Tells a funny joke           |
| Alexa are you single         | Gives a fun response         |



 Project Structure


alexa-ai/
├── main.py             # Core voice assistant logic
├── README.md           # Project documentation
└── requirements.txt    # Package list for installation




  Limitations

Requires a working microphone
Internet connection is needed for YouTube and Wikipedia features
 Only activates when it hears "Alexa"



 Purpose of the Project

This project is developed as a voice-controlled intelligent assistant using Python. It is intended for learning purposes and demonstrates how artificial intelligence can be integrated with speech technology to interact naturally with users. Designed as part of university academic work to explore AI applications in real life.



 License

This project is for educational purposes only. No commercial use allowed.