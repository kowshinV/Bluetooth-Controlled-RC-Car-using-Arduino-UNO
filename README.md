🚗 Bluetooth Controlled RC Car using Arduino UNO:
This project demonstrates how to build a Bluetooth-controlled RC car using an Arduino UNO, L298N motor driver, and HC-05 Bluetooth module. The car can be wirelessly controlled from a smartphone app or any Bluetooth-enabled device.

🔧 Components Used:
* Arduino UNO
* L298N Motor Driver Module
* HC-05 Bluetooth Module
* 4 DC Motors (2 left, 2 right)
* 12V Battery Pack
* Connecting Wires and Chassis

⚙️ Arduino Code:
[View Code:](CODE_FOR_RC_CAR)

🧠 Working Principle:
* The HC-05 module receives commands via Bluetooth from a mobile app.
* The Arduino interprets these commands and controls the L298N motor driver to move the motors forward, backward, left, or right.

💡 Features:
* Wireless Bluetooth control
* Dual motor driver setup for differential steering
* Headlight indicator
* Simple, low-cost design

Circuit Diagram:
[View Circuit Diagram](RC_car.jpg)

📜 How to Use:
* Connect the circuit as shown in the diagram.
* Upload the Arduino code to the UNO board.
* Pair the HC-05 module with your phone (default password: 1234).
* Use a Bluetooth controller app to send movement commands.

🚀 Future Improvements:
* Add obstacle avoidance using ultrasonic sensor.
* Include speed control with PWM.
* Add a rechargeable Li-ion battery pack.

🖋️ Author:
KOWSHIN.V, https://github.com/kowshinV
