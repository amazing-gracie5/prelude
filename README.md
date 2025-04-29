# Prelude
This Python web application allows music composers to view, edit, and combine their ideas in one workspace. This app was developed as part of the Senior Independent Study project "Idea Management for Composers" by Grace Simonson at the College of Wooster (advised by Dr. Dan Palmer and Professor Greg Slawson). 

## "Idea Management for Composers": Abstract
A challenge many composers face during the process of writing music is managing their early ideas. Not only does inspiration strike in a variety of places, but ideas themselves come in a myriad of forms: a melody, a texture, an image, words, rhythms, sounds, etc. However, current composition applications focus on notating music to create performance-ready sheet music and lack the ability to record early, inexact ideas. Utilizing knowledge of design principles, interviews with active composers, and research on the composition process and composition tools, I designed and implemented a software tool that allows composers to store, edit, and combine their early music ideas in one workspace. When testing the tool, composers enjoyed the ability to see all their ideas at once and the ability to switch quickly between different idea formats (which may be represented as notated music, drawings, images, audio recordings, or text in the workspace) and found that these features aided the creative process. 

## Dependencies
Prelude depends on the following Python libraries:
- NiceGUI (version 2.4.0)
- abc
- music21 (version 9.1.0)
- pathlib
- os
- datetime
- subprocess
- filetype
- re

Other dependencies (command line programs that must be installed on the host machine):
- LilyPond (version 2.24.4)
- FluidSynth (version 2.4.2)

Not included in this GitHub repository is a Soundfont file (it was too big to upload). The Soundfont file I use on my machine may be downloaded here: https://member.keymusician.com/Member/FluidR3_GM/index.html 

## How to Build/Run
- Download a Soundfont file (the one I use may be downloaded here: https://member.keymusician.com/Member/FluidR3_GM/index.html) and place it in the same directory as main.py 
- Ensure the name of the Soundfont file name matches the name on line 33 of main.py (either adjust the code or the name of the file so this matches)
- Ensure the proper Python libraries and command line programs are installed
- Run the Python file main.py. The app will use your computer as the host and run as a private webpage in a browser (see the output of the run command to get the address to visit in a browser)

## Idea Management for Composers
For more information about this app (how and why it was designed, implementation details, etc.) see the Senior Independent study thesis "Idea Management for Composers" (included as a PDF file in this repository).

This software was developed in partial fulfillment of the requirements for the degree Bachelor of Arts in the Department of Computer Science and the Department of Music and the College of Wooster.
