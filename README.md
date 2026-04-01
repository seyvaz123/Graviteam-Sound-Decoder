GraviteamSoundDecoder - End User Readme
======================================

What this program does
----------------------
GraviteamSoundDecoder converts Graviteam .sound files into playable audio files.

It can create:
- .xwma files
- .wav files

The EXE already includes the tools it needs.
You do NOT need to install Python, FFmpeg, or xWMAEncode separately.

How to use
----------
1. Double-click GraviteamSoundDecoder.exe
2. Click "Add Files" and choose one or more .sound files
3. Leave Decoder set to "auto"
4. Choose where you want the output saved
5. Click "Convert"

What you will get
-----------------
Depending on the options selected in the program, you will get:
- a rebuilt .xwma file
- a decoded .wav file

The .wav file is the one most media players can play directly.

Recommended settings
--------------------
For normal use:
- Leave Decoder on "auto"
- Save output next to source files, or choose an output folder
- Convert to .wav if you want the easiest file to listen to

Notes
-----
- Some Graviteam .sound files are music files wrapped in the AAF1 format.
- The program rebuilds them into valid .xwma files and can then decode them to .wav.
- Some unusual files may fail if they use a different internal format.

If a file fails
---------------
If conversion fails:
1. Try the file again with Decoder set to the other available option
2. Check the log/output message in the program window
3. Make sure the file is really a Graviteam .sound file

Tips
----
- You can select multiple .sound files and convert them in one go.
- .wav files are larger but are easier to play and edit.
- .xwma files are useful if you want to keep the intermediate rebuilt audio.

No extra setup needed
---------------------
This EXE is self-contained.
Just run it and convert your files.
