Spectrum
========

What is it?
-----------
Over Summer 2016 I built "Spectrum", a 7-channel (entirely analogue) sound-to-light art piece. Spectrum features a microphone and seven columns of LEDs, each indicating the strength of one of seven different audio frequency bands. This is achieved using seven bandpass filters, each followed by a peak detection stage and an LM3914 bar display driver. The finished piece can be placed next to a sound system and adds another dimension to the music.

Any problems?
-------------
The version I built featured a bug where LED D28 was not connected to Vcc as it should. This has been corrected in the schematic, pcb and gebers that I have uploaded.

RV1 can be replaced with a 1M trimmer instead of a 500k trimmer. This gives you the possibility of extra gain.

R54 and R55 can be replaced with 0ohm resistors if you like. I put them there when I wasn't sure if op amp offset current would be an issue.

How can I make my own?
---------------------
To create your own board, use the gerber files that are NOT in zip folders. The zip folders contained archived previous versions (potentially containing bugs and sadness).

Read more at http://projects.matthollands.com/category/spectrum/

![alt text](https://keepdevelopingprojects.files.wordpress.com/2016/10/20161012_180619.jpg)
![alt text](https://keepdevelopingprojects.files.wordpress.com/2016/10/img_1663.jpg)
![alt text](https://keepdevelopingprojects.files.wordpress.com/2016/10/img_1662.jpg)
