# MakeAi
Make Ai With Python 
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=30&pause=1000&color=F70606&width=435&lines=%F0%9F%91%8BMakeAi+With+Python+;Samir+Talukder+Apurbo;%F0%9F%AB%B0%F0%9F%96%A4)](https://git.io/typing-svg)
### Codes
```
import speech_recognition as sr
import pyttsx3
import datetime 

listener = sr.Recognizer()
bindu = pyttsx3.init()

def talk(text):
    bindu.say(text)
    bindurunAndWait()


def take_command():
    try:
        with sr.Microphone() as source:
            print('listening...')
            voice = listener.listen(source)
            command = listener.recognize_google(voice)
            command = command.lower()
            if 'bindu' in command:
                command = command   import speech_recognition as sr
import pyttsx3
import datetime
import pywhatkit
import wikipedia
import pyjokes

listener = sr.Recognizer()
alexa = pyttsx3.init()
voices = alexa.getProperty('voices')
alexa.setProperty('voice', voices[1].id)


def talk(text):
    alexa.say(text)
    alexa.runAndWait()


def take_command():
    try:
        with sr.Microphone() as source:
            print('listening...')
            voice = listener.listen(source)
            command = listener.recognize_google(voice)
            command = command.lower()
            if 'alexa' in command:
                command = command.replace('alexa', '')
    except:
        pass
    return command


def run_alexa():
    command = take_command()
    if 'time' in command:
        time = datetime.datetime.now().strftime('%I:%M %p')
        print(time)


        talk('Current time is ' + time)replace('bindu', '')
    except:
        pass
    return command


def run_alexa():
    command = take_command()
    if 'time' in command:
        time = datetime.datetime.now().strftime('%I:%M %p')
        print(time)
        talk('Current time is ' + time)

```
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/KYpHf1cF/IMG-20240206-WA0002.jpg' border='0' alt='IMG-20240206-WA0002'/></a>

<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/90htY29C/IMG-20240206-WA0001.jpg' border='0' alt='IMG-20240206-WA0001'/></a><br /><a href='https://postimages.org/'>host pictures</a><br />
