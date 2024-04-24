# Kyomaboard

This is a custom pcb design for a custom keyboard. There will be pictures available later on as well.
It is a 101% keyboard, I do love my numpad. The reason to build this was my stupid idea to make a case out of wood.
This proofed to be challenging, as spacing between the middle part and the main typing area and the numpad is quiet small.
To circumvent this issue I designed it myself, and because I was already at it, I made it left handed compatible by moving the numpad to the left side.
I also added a knob for some multi media control.

I am using a RP2040 as main controller and ws2812 LEDS for addressable LEDS without the need for an led matrix.
Since I want to have N-key-rollover there is an diode for every key.


This project is compatible with kicad 8. There is a PDF of the schematics available as well.
If you want to use this project feel free to copy or modify it and give attribution where its due.
Feel free to reach out to me if you have questions, I cant guarantee that any of this works at all ^^'

Know Issues and changes:
- The crystal oscillator is missing and needs to be added
- be careful with the power footprint, the
- maybe put everything on the back. backmounted leds are not that expensive and you wont need to solder everything by hand
- 
