# task--6-SM

Text-to-Speech Converter

This project provides a simple web interface for converting text input into speech using Flask and the pyttsx3 library. The application allows users to input text and listen to the converted speech.

Files:
1.	app.py: The main application script that sets up the Flask server and handles requests to convert text into speech.
2.	templates/index.html: The main web interface providing a text area for input and a button to initiate the text-to-speech conversion.

Setup:
1.	Python Installation:
o	Ensure Python 3.x is installed on your machine. You can download it from the official website.
2.	Virtual Environment Setup:
o	Create a virtual environment to manage dependencies:
python -m venv venv
o	Activate the virtual environment:
	On Windows:
.\venv\Scripts\activate
	On macOS and Linux:
source venv/bin/activate
3.	Dependencies Installation:
o	Install the required packages listed in requirements.txt:
pip install -r requirements.txt
4.	Running the Application:
o	Start the Flask server by running:
python app.py
o	Open your web browser and go to http://127.0.0.1:5000 to access the application.

Usage:
•	Accessing the Interface:
o	Open your web browser and navigate to http://127.0.0.1:5000.
•	Text-to-Speech Conversion:
o	Enter the text you wish to convert into the provided text area on the web page.
o	Click the "Convert to Speech" button to generate the speech audio.
o	The converted speech will be available for playback using the audio player on the page.

Directory Structure:
your_project_folder/
│
├── app.py                  # Main application file
├── requirements.txt        # List of required Python packages
└── templates/
    └── index.html          # HTML file for the web interface

Additional Notes:
•	Ensure the index.html file is placed in the templates directory to allow Flask to correctly locate and render it.
•	The pyttsx3 library does not require an internet connection, making it suitable for offline use.
