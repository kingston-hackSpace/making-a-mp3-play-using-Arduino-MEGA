# Instructions for playing an mp3

The mp3 shield allows audio playback using an arduino as the trigger. Speakers can be plugged in using a phono jack.

——

### assembly

you will need...

- Arduino MEGA
- speark fun mp3 shield
- speaker with phono jack

assemble the kit as shown in the diagram above

### libraries

- download the library from [here](https://learn.sparkfun.com/tutorials/mp3-player-shield-hookup-guide-v15)

- add the SFEMP3Shield folder to the arduino library folder. Drag and drop it to the documents->arduino->libraries folder using the finder.

- when you load arduino, the library should be loaded.

### SD card

- take the SD card and insert into a card reader or desktop computer.

- Add the files to the card. make sure the SD card has the files labeled TRACK_01.mp3 and then in sequence.

- insert the SD card to the mp3 shield

### run the sketch

-Upoad the sketch above to the arduino. 

- It should play the first track on the mp3 shield.
