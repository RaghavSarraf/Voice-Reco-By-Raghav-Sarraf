Voice Reco By Raghav Sarraf


Converting from Speech to Text with JavaScript
The purpose of this app is to experiment with the Web Speech API which enables you to incorporate voice data into web apps. The Web Speech API has two parts: SpeechSynthesis (Text-to-Speech), and SpeechRecognition (Asynchronous Speech Recognition.)

This app uses the Web Speech API to build a voice powered note app to do 3 things:

Takes notes by using voice-to-text or keyboard input.
Save Voice Reco By Raghav Sarrafs to localStorage.
Display all of the saved notes and give the option to either Listen to the Notes or delete them.
Voice Reco By Raghav Sarraf App

Note: On Chrome, using Speech Recognition on a web page involves a server-based recognition engine. Your audio is sent to a web service for recognition processing, so it won't work offline.

Most APIs that require user permission don't work on non-secure hosts. Make sure you are serving your Web Speech apps over HTTPS.

Table of Contents
Description
What I Learned From The Exercise
Website Technologies Used
How to Use This App
File and Directory Structure
Resources
Revision History

Description
The Web Speech API provides two distinct areas of functionality — speech recognition, and speech synthesis (also know as text to speech, or tts)

The Voice Reco By Raghav Sarraf App will be separated into two seperate interfaces. The first will be the "Speech Recognition" that will involve receiving speech through a device's microphone, which is then checked by a speech recognition service against a list of grammar (basically, the vocabulary you want to have recognised in a particular app.) When a word or phrase is successfully recognised, it is returned as a result (or list of results) as a text string, and further actions can be initiated as a result.

The second is "Speech Synthesis" (aka text-to-speech, or tts) that involves receiving synthesising text contained within an app to speech, and playing it out of a device's speaker or audio output connection.

What I Learned From The Exercise
To work with the Web Speech API; speech recognition, and speech synthesis.

Website Technologies Used
Description of website technologies used to develop this app.

HTML
CSS
JavaScript
Bootstrap
Web Speech API

How to Use This App
Add A New Voice or Text Note
​Click on the Start Recognition Button and give the app permission to use your microphone, and start speaking your note (if no microphone or you don't want to use the microphone you can type into the text box.)

​When done speaking click on the "Pause Recognition" button, and then click the "Save Note" button. (if you you typed your note in to the text box you do not need to click on the "Pause Recognition" button, just click the "Save Note" button.)


Listen To Notes
Click on the "Listen to Note" link next to the date of the note that you want to listen to.

Delete Voice Reco By Raghav Sarrafs
Click on the "Delete" link next to the date of the note that you want to delete.

Demo - Click Here - Best Used with Chrome

Note: On Chrome, using Speech Recognition on a web page involves a server-based recognition engine. Your audio is sent to a web service for recognition processing, so it won't work offline.

Most APIs that require user permission don't work on non-secure hosts. Make sure you are serving your Web Speech apps over HTTPS.

File and Directory Structure
.
├── assets
│   │
│   ├── css
│   │   │
│   │   └── style.css
│   │
│   ├── ico
│   │   │
│   │   └── favicon.ico
│   │
│   ├── img
│   │   │
│   │   ├── code-mic-150.png
│   │   │
│   │   └── vna-1.gif
│   │
│   └── js
│       │
│       └── script.js
│ 
├── .gitignore
│
├── index.html
│
└── README.md     
       
Resources
Article from tutorialzine Converting from Speech to Text with JavaScript using HTML, CSS, jQuery, JavaScript, and Shoelace.css a lightweight, forward-thinking CSS library built with future CSS syntax.

Reference how to work with the Web Speech API - MDN Web Docs Web Speech API
