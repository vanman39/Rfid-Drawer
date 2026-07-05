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
-1 keyboard switch
NOTE: the servo is on 5v and the rfid is on 3.3v and the esp32 is floating
Libraries for codebase: ESP32Servo and MFRC522 and preferences


Custom Potted Connection (Keyboard Switch Interface)
To create a low-profile, permanent connection for the keyboard switch, I used a custom potting method to replace standard heat-shrink and DuPont housings:

Preparation: Cut a female DuPont wire and strip 6mm of insulation.

Mounting: Plug the female header onto the switch terminal. Secure the header body directly to the internal case wall using hot glue to prevent any mechanical movement.

Routing: Pass the stripped wire ends through the designated holes in the lid.

The "Potting" Seal: Once the lid is positioned, join the stripped wire ends to the corresponding female DuPont headers. Instead of using heat shrink, encapsulate the entire joint in hot glue. This acts as both electrical insulation and a permanent mechanical "potting" to prevent shorts and wire fatigue.
