Virtual Assistant Chatbot 🤖

This is a Python-based Voice-Activated Virtual Assistant that listens to user commands, responds with speech, and performs basic tasks such as telling the time, opening Google, finding locations on maps, and even sending emails.

🚀 Features

🎙️ Speech Recognition: Understands voice commands using Google Speech Recognition

🔊 Text-to-Speech (TTS): Responds back using Google Text-to-Speech (gTTS)

⏰ Time Queries: Tells the current time

🌐 Web Automation: Opens Google and locates places on Google Maps

📧 Email Support: Sends emails via Gmail SMTP

🛑 Stop Command: Ends the assistant when you say “stop”

🛠️ Tech Stack

Language: Python 3

Modules Used:

speech_recognition – Convert voice to text

gTTS – Text-to-Speech using Google TTS

playsound – Play audio responses

datetime – Fetch system time

os – File handling

webbrowser – Open web pages

smtplib – Send emails through Gmail SMTP

uuid – Generate unique audio filenames
📂 Project Structure
Virtual-Assistant-Chatbot/
│── assistant.py        # Main assistant script
│── requirements.txt    # Required dependencies
│── README.md           # Project documentation

⚡ Installation

Clone the repository:

git clone https://github.com/your-username/virtual-assistant-chatbot.git
cd virtual-assistant-chatbot


Install the required dependencies:

pip install -r requirements.txt


(Make sure you have Python 3.7+ installed)

▶️ Usage

Run the chatbot with:

python assistant.py


Say commands like:

“How are you” → Responds with a greeting

“What’s the time” → Tells the current time

“Open Google” → Opens Google in your browser

“Locate New York” → Opens Google Maps at the location

“Send email” → Starts email sending process

“Stop” → Ends the program

📧 Email Setup

This project uses Gmail SMTP for sending emails.

You must enable App Passwords in your Gmail account (since Google no longer allows "less secure apps").

Replace the credentials inside the script with your own:

mail.login('your-email@gmail.com', 'your-app-password')
📌 requirements.txt

Here’s a sample requirements.txt you can include:

speechrecognition
gtts
playsound
pyaudio


(You might need to install pyaudio separately depending on your OS.)

🤝 Contributing

Contributions are welcome!
Feel free to fork this repo, open an issue, or submit a pull request with improvements.

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.
