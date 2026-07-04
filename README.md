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
NOTE: the servo is on 5v and the rfid is on 3.3v and the esp32 is pushed into a 430 pinbreadboard 
Libraries for codebase: ESP32Servo and MFRC522 and preferences
NOTE ON WIRING:
in order to keep this project plug and play you will need to strip bpth ends off a female dupoint wire with about 7mm left then strip 4mm of silicone off that so then you can take about 4mm of a male end of a dupoint wire and push that into a female end and then insert the stripped end of the female wire in and then you will have the special wire needed to go through the keyboard switch lid. 
assets/20260704_111557.jpg
this is the image of the finished product
