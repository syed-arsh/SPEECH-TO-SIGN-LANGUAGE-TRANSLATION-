# SPEECH-TO-SIGN-LANGUAGE-TRANSLATION-
Education for the deaf is hindered by the scarcity of sign language interpreters. Our innovation revolutionizes learning by offering real-time sign language translation, empowering deaf students to access education effortlessly and thrive in inclusive environments.


An application which takes in live speech or audio recording as input, converts it into text and displays the relevant Indian Sign Language images or GIFs.

- Front-end using EasyGui.
- Speech as input through microphone using PyAudio.
- Speech recognition using Google Speech API and Sphix(for offline use).
- Text Preprocessing using NLP.
- Dictionary based Machine Translation.
- To run the application.
- Open the Downloads folder and then open the terminal.
- From the terminal, run the main python file using the command python main.py.
- The application interface appears on the screen.
- Hit the record button to start taking speech as input.
- Any speech recorded is then processed and respective outputs are shown accordingly.
- To exit the application using speech, say goodbye.
- Sign language is a visual language that is used by deaf people as their mother tongue. Unlike acoustically conveyed sound patterns, sign language uses body language and manual communication to fluidly convey the thoughts of a person. Due to considerable time required in learning the Sign Language, it becomes difficult to communicate with these specially abled people, and thus creates a communication gap.

Objective
This Audio to Sign Language converter aims at :

Providing information access and services to deaf people in Indian sign language.
Developing a scalable project which can be extended to capture whole vocabulary of ISL through manual and non-manual signs
It can be developed as a desktop or mobile application to enable specially abled people to communicate easily and effectively with others

Sign language is a visual language that is used by deaf people as their mother tongue. Unlike acoustically conveyed sound patterns, sign language uses body language and manual communication to fluidly convey the thoughts of a person. Due to considerable time required in learning the Sign Language, people find it difficult to communicate with these specially abled people, creating a communication gap. Thus, we propose an application which takes in live speech or audio recording as input, converts it into text and displays the relevant Indian Sign Language images or GIFs.

Algorithm

Audio to Sign Language Translator

- Start
- Getting the Speech
- Listen for 1 second and calibrate the energy threshold for ambient noise levels.
- Listen the Speech using Microphone. Now the energy threshold is already set to a good value, and we can reliably catch speech right away.
- Recognise the Speech.
- Convert Speech to Text.
- Make the Text to lowercase for further manipulation.
- Detected Text
- If “goodbye” then exit. 2.Else if Detected Text in predefined Dictionary Words. Display respective GIFs of the Phrase.
- Else Count the Letters of the Word/Phrase.
- Display the Visual of the phrase with some delay of Actions.
- Continue all the steps from Step 3, and continue till the Speech Ends.
- If Error in Step 2, That is if no Speech Detected then display error message “Could not listen”.
- Due to considerable time required in learning the Sign Language, people find it difficult to communicate with these specially abled people, creating a communication gap. Thus the Audio to Sign Language converter is important and significant because it helps in providing information access and services to deaf people in Indian sign language and develops a scalable project which can be extended to capture whole vocabulary of ISL through manual and non-manual signs. It also can be developed as a desktop or mobile application to enable specially abled people to communicate easily and effectively with others.
