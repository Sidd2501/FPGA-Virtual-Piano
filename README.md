# FPGA-Virtual-Piano
Made a virtual piano using the on the Basys3 board, which is a type of FPGA. Each switch represented a certain note (sound frequency on the 16-octave scale) and when a switch was turned on, it emits the sound to a speaker which in our case, is a Piezo buzzer. We made LEDs light up according to the notes in sequence that follow the song, which is the Blue Danube Waltz. The user will attempt to play this song by flipping the switch in the order of the LEDs that light up, helping them play a song on a virtual piano. The user can play any note that they want, as long as they flip only one switch at a time.

Note: Only one clock divider note has been provided. Multiple were created but the code is redundant.
