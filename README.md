# Apple II Keyboard Adapter

This is a simple Arduino project to allow connecting a PS/2 keyboard to the
16 pin DIP keyboard connector on an Apple II. I've tested it on a
ReactiveMicro reproduction Apple II+ RFI logic board and it works great.

All keys are mapped to modern keyboard equivalents and the Apple can be
reset with the Ctrl-PrtScrn key combo.

Parts list:
 1. Arduino. I used a cheap Arduino Pro Micro clone from Amazon but
    you could probably adapt to use whatever you have on hand.
 2. Female PS/2 connector
 3. 2 8-pin male machine pin headers, or some other connector for the
    DIP-16 socket on the logic board.

![Hookup Diagram](docs/wiring_diagram.svg)

_Warning_: The DIP-16 connector on the logic board does have some pins with
higher voltages that will destroy your Arduino if you accidentally connect to
them, so take care.


![Captura de tela 2024-10-10 224555](https://github.com/user-attachments/assets/cb72da11-3018-4c6e-a7b4-470129d353ca)
