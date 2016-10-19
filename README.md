# puppyaudio

Notes on setting up audio in puppylinux. I'm looking at two versions:

- tahr - 32-bit tahr for older devices (tested using a Dell Inspiron 1300)
- tahr64 - for modern hardware

##Qjackctl

This can be installed from the puppy package manager

Qjackctl doesn't seem to start out of the box. I fixed this by using MENU->Setup->ALSA Sound Wizard to pick the right card, and to 
tick the output and capture boxes on the 'adjust levels' dialog box

###tahr64 issues

I did the above, but also had to set the input and output device explicitly - I think it was trying to output to the HDMI and tripped over itself
