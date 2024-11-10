pip install pyttsx3
pip install SpeechRecognition
pip install wikipedia
pip install pyaudio
git clone https://github.com/yourusername/jarvis-assistant.git
cd jarvis-assistant
def sendEmail(to, content):
    server = smtplib.SMTP('smtp.gmail.com', 587)
    server.ehlo()
    server.starttls()
    server.login('your-email@gmail.com', 'your-app-password')  # Use your Gmail App Password
    server.sendmail('your-email@gmail.com', to, content)
    server.close()
music_dir = 'D:\\Your\\Music\\Folder\\Path'
python jarvis_assistant.py
