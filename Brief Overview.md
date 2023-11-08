# SCAC

Streamlined ChatGPT Access Contact

This is my second ever Python project I started in September 2023

The purpose of this project is to streamline my overall learning process for Sec+, CCNA, Google Security Cert, and other future IT/CycberSec/Cloud certifications that I can obtain through home study and home labs

The project achieves this goal via X aspects
  1. Easy point of contact: The API links my text messages on my phone to ChatGPT's API interface, allowing me to ask questions and get responses back with less effort than it takes to go to the website
  2. Audio responses: In addition to getting a text message response from the AI, an mp3 text-to-speech audio file of the response is saved to a cloud drive that is accessible by this Python program on the host device it runs on, as well as accessible from my phone.
  3. Easy range of access: I can listen to the audio file and learn on the fly without needing to divert my eyes from other tasks, like walking around, jogging, and if the audio file is long enough (they have gone up to 5 minutes in my experience) I can send a text asking 
to clarify or expand upon or provide examples for a concept I need to learn more about, and I can listen to the response in the car. Of course, the texts are never written or sent out while driving. 

This summarizes the purpose and methods of this project

Future expansions: 
Prompt as Code
it will be easy to map certain prompts to certain inputs such that Python looks for certain strings of alphanumeric values (example: $CAC2C -> Compare and contrast the two concepts in this message, $PXEX-> provide X examples of this concept being used in a realist scenario)

Smart Directory Structure
it will be interesting to have the Python script take input, read the response, give the response a title, take a list of directories in a given pathway, and send these directories' names to chat gpt (or to me via sms!) along with the title of the last response, ask the AI
to choose the best location for the latest response, such that all responses can be saved and mapped in a place deemed appropriate to hold them, adding organization to the many mp3 files that will unevitably be saved over the course of usage. Currently, there are around 
400 responses since the middle of September and they don't take up as much room in storage as I anticipated. 
