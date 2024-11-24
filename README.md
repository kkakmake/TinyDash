# TinyDash
TinyDash is a customized RP2040-Tiny connector board for self-made keyboards. It fits between hot-swap sockets to make your keyboard thinner.


<img src="https://github.com/user-attachments/assets/30df5dc5-afa0-4a0e-a3f8-583f36942edb" width="60%">


<img src="https://github.com/user-attachments/assets/c97ade18-8c1b-4acf-8c9e-075f706fa4ca" width="60%">

## TinyDash Choc 

**TinyDash Choc** fits Choc sockets. Currently, TinyDash only has this one type.

<img src="https://github.com/user-attachments/assets/9f9fbdef-b6f9-48fc-ada5-3edef9ec492f" width="30%">

### Schematic
The power LED and reset switch found in the original circuit have been omitted. However, the reset button is implemented as a pad, which can be shorted with tweezers to reset the RP2040-Tiny.

<img src="https://github.com/user-attachments/assets/0ffe8ad7-f78d-4a35-9114-5ce9839ca203" width="60%">

### Resources
#### Production data
[TinyDash/Gerber/TinyDashChoc/v2.0/](https://github.com/kkakmake/TinyDash/tree/51dfb41c6dbbbea27f5ecb82bc694be61e01b232/Gerber/TinyDashChoc/v2.0)

Please note that the production data is in the form of ordering to JLCPCB. Also, since it is assumed to be a single-sided PCBA, you will need to solder the tact switch yourself. The switch used is a 3*4*2mm four-legged surface mount tact switch. 

<img width="113" alt="tactsw" src="https://github.com/user-attachments/assets/c4481b4b-f900-4242-95fe-605c1ef56824">

Please look for the part that matches "Button_Switch_SMD:SW_Push_1P1T_NO_CK_KMR2" in KiCAD's footprint library.

<img width="218" alt="tactsw_fp" src="https://github.com/user-attachments/assets/57a7c0f8-d68b-4ea4-bed6-02aaad13f4b9">

#### Foot print (KiCAD)
[TinyDash/Footprint/TinyDashChoc/v2.x/](https://github.com/kkakmake/TinyDash/tree/51dfb41c6dbbbea27f5ecb82bc694be61e01b232/Footprint/TinyDashChoc/v2.x)

### How to use TinyDash Choc

#### Mount on a main board
The TinyDash Choc use 3 sets of M1.6 screws and nuts.

<img src="https://github.com/user-attachments/assets/0428b465-f241-4982-ba6e-874011c571f3" width="50%">

#### Push BOOTSEL button
You can use the needle to press the BOOTSEL button through the gap between the keys.

<img src="https://github.com/user-attachments/assets/b11ee690-49ba-4a40-8a57-1f35cf911d6c" width="50%">

# License
TinyDash* is published under CC-BY-4.0.

If you make a keyboard using TinyDash, please let me know.
