# Rfid-Drawer
An rfid locked drawer that opens with the correct rfid card 
BOM
-1 esp32 wroom
-jumper wires
-1 rc522
-1 keyfob or keycard
-3d printed drawer (see stls)
-1 9g servo
-1 1000 uf capacitor 25v
-1 130 pin breadboard
NOTE: the servo is on 5v and the rfid is on 3.3v and the esp32 is floating
Libraries for codebase: ESP32Servo and MFRC522 and preferences


NOTE ON WIRING
To achieve a low-profile connection that fits within the keyboard switch mount, I created a custom "bridge" interconnect. Follow these steps:

Prepare the female wire: Take a female Dupont wire and trim it, leaving approximately 7mm of wire exposed. Strip 4mm of the silicone insulation off the end.

Prepare the male wire: Take a male Dupont wire and expose about 4mm of the metal pin.

Assemble the bridge: Insert the exposed 4mm male pin into a separate female Dupont connector housing.

Connect: Insert the stripped 4mm end of your prepared female wire into that same female housing so it makes contact with the male pin.

Secure: Use the 3D-printed cap to hold the assembly in place on the switch terminal.
