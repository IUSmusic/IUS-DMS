IUS Official Sequencer

This project is a browser based prototype of the intended real world IUS drum sequencer. It demonstrates the planned sequencing layout, control flow, sound assignment behaviour, preview workflow, track playback, default audio handling, and accessibility theme switching for the final model.

Project contents

The root folder contains the main application file, the text documentation, the legal text files, and the hardware reference text files. The soundbank folder contains the bundled audio content used by the prototype. The assets folder contains the official logo files used by the interface.

Main files

index.html is the prototype application.
README.txt is the main project guide.
LICENSE.txt is the software license for the code.
TRADEMARK_NOTICE.txt explains the brand and logo restrictions.
technical_hardware_layout.txt describes the intended hardware layout.
final_concise_block_schematic.txt gives the high level hardware block structure.
hardware_handoff_summary.txt gives the hardware summary.
SAMPLE_FOLDER_NOTE.txt explains how to place your own sample files.

How to open the prototype

Step 1. Extract the zip file.
Step 2. Open the IUS Official Sequencer folder.
Step 3. Open index.html in a modern browser.
Step 4. The prototype will load with the main sequencer view.

What the prototype does

The prototype provides a multi track step sequencer interface with 31 steps per track. It lets you open the sound library, preview sounds, assign sounds to steps, upload a default track sound, record default track audio from microphone input where supported, start and stop playback, change BPM, use looping, inspect assignments, and switch between dark and light high contrast themes.

How to use the preview

Step 1. Open index.html in your browser.
Step 2. Click the library button in the top bar.
Step 3. Load audio files if you want to add custom sounds.
Step 4. Click a sound in the library to arm it.
Step 5. Click a step on any track to assign the armed sound.
Step 6. Use the play button on a track to hear the sequence.
Step 7. Use stop to reset the track.
Step 8. Change BPM on a track to alter playback speed.
Step 9. Use the loop control to keep playback cycling.
Step 10. Use the theme button in the top bar to switch between dark and light high contrast viewing modes.

Technical note

The prototype is implemented as a single page HTML application using browser native audio and media features. It is a front end prototype of the real model and is not the embedded hardware firmware.
