# Psychic Reader Text Editor, for Google Assistant

Psychic Reader is an app for Actions on Google that can be invoked on any Google Assistant device (phones, Google Home, Allo, etc.) by saying "Talk to Psychic Reader". This is the text editor frontend (the backend and rest of the frontend is [here](https://github.com/karan1149/psychic-google-assistant)).

The user of the app can tell their friends to ask Psychic Reader any question, and the app will always respond with the correct answer. Secretly, the user will be using a separate connected device to provide answers for Psychic Reader. The connected device will appear to be using an innocent text editor, not typing anything suspicious. 

For example, a friend could ask, "How old am I?", and the user of the text editor types in a secret command (".20 years old." in this case), and the Psychic Reader will respond with "20 years old".

As this is happening, the editor appears to be typing out something else:
![Image of text editor](https://getpsychicreader.com/images/editor-demo.gif)

## What does the text editor do?

The text editor is used to send commands to Psychic Reader so the app knows what to say when it is asked a question. The text editor is basically a textbox that captures all keystrokes (surprisingly difficult to get working on all platforms) and sends the relevent ones to the Psychic Reader. More details on usage of the text editor can be found in the advanced tips in the [tutorial](https://getpsychicreader.com/tutorial.html).

## Get Started

Details on how to begin using Psychic Reader can be found in the [tutorial](https://getpsychicreader.com/tutorial.html).
