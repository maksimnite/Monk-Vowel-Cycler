# Monk-Vowel-Cycler
No Pitch bend Slider? No problem.

This entire project was a hour long ChatGPT Conversation about MonkSynth's (Delay Lama) Vowel slider, and how deeply inconvinient it is when used in **Cantabile lite**.

The idea was simple, a plugin that edits the Vowel for each note played, but this gave the notes a pretty akward feel, as if every note did a unique sound that didnt sound natural to me. What did i do? Throw everything out the window and ask the Big AI notorious for fixing my python code.

As a result, a tool that uses [LoopMidi](https://www.tobias-erichsen.de/software/loopmidi.html) to actively cycle through different Vowels on its own after each individual press of a key.

### Attention
This Build only works on Windows, i cant test it on linux and probably wont make a whole port for it in the future, sorry :(

## Installation & Tutorial
This is super simple but **IMPORTANT**

1. Install [LoopMidi](https://www.tobias-erichsen.de/software/loopmidi.html) and complete the setup there.
2. Open LoopMidi and Add a New Port, Name it after whatever you like, but to make it distinct something like "Monk Vowel Out" will do.
<img width="484" height="325" alt="image" src="https://github.com/user-attachments/assets/c6b0f514-0246-4246-9a38-72cb1687ecf6" />

Once youre done, you can keep it open in the background and close the window.

3. Start "Run_MonkVowelCycler.bat" found in the .ZIP, and Look for Midi Input and Output on the top of the window.
4. In the Input field, Select your Plugged Midi device.
5. In the Output field, Select the Port you created in LoopMidi.
<img width="518" height="488" alt="image" src="https://github.com/user-attachments/assets/2056fde9-db55-46ee-8e89-748369b15f5d" />

6. In Cantabile Lite, find the Midi ports Section inside the settings, and Add the Vowel Cycler Port as an Input. You can Connect the New Input device into the MonkSynth Plugin now.

<img width="990" height="640" alt="image" src="https://github.com/user-attachments/assets/7702c94d-6a60-419c-93b9-0c7c604c730f" />
<img width="380" height="162" alt="image" src="https://github.com/user-attachments/assets/01580d0f-acdf-46d6-a435-828213a17e4f" />



