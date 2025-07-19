# chonkofly19
Based on [vlkv's Chocofly](https://github.com/vlkv/chocofly/tree/v3) keyboard layout, made to MX spacing and mounting points to allow for easier Choc V2 switch and MX stem keycap compatibility.

This keyboard is meant to be used with Pi Picos, specifically the YD-RP2040 as it has USB-C.

As is, this is *only* hotswap. If there is enough desire, I'm willing to make a board-soldered version.

## Features
- Kailh Choc V1 and V2 switch compatibility (hotswap)
- 19.05x19.05 MX keycap spacing
- Non-aggressive columnar stagger with fanned 2 outer columns
- 4 thumb key cluster with 2 upper thumb keys

### Chonkofly V1 PCB
<img width="1938" height="1085" alt="image" src="https://github.com/user-attachments/assets/c28eeca5-f6bc-429e-b860-4bd5e8459b26" />

## Differences and Why
### No encoders?
This is deliberate as the 2 EVQWGD001 roller encoders that were on the original Chocofly. They are expensive ($20-25 per) and they are not being made anymore. I personally do not use an encoder, but would be open to adding a low-profile rotary encoder. Or an alternative that uses mouse encoders like the ones detailed in [roBa](https://github.com/kumamuk-git/roBa/blob/main/doc/v3/buildguide_v3.md) build guide.

### "Sonshi"?
I certainly understand why vlkv would make the keyboard this way. I use this keyboard as my daily and I didn't like how it looks sitting on my desk without a case. I'm not using it as a keyboard replacement for my laptop, so portability is not as important to me. As a result, a bit of extra PCB has been removed from the sides. Mounting holes have been added for a 3D printed case.

### Wireless?
Since this keyboard is not for my laptop, this does not have a battery and thus doesn't need wireless. This makes the board a lot simpler too. Maybe I'd make a wireless version in the future? I do not know what the state of ZMK is on Pi Pico is at the moment, but I would be willing to look into it in the future.

### To Do
- 3D printed case
- 3D printed wristrest
- MX?
- Board-soldered option?
- Folding? Probably a different design at that rate
- Upload firmware
