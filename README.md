Smart Parking Lot System (DMC8)

This project simulates a smart parking lot system using the DMC8 microprocessor and the DEEDS simulator. A master–slave architecture is used where push buttons represent vehicle entry and exit, and the total vehicle count is displayed on a 7-segment display.

LED Indicators

🟢 Green: Parking is available (vehicle count < 5)

🟡 Yellow: Parking is getting full (5–9 vehicles)

🔴 Red (Blinking): Parking lot is full (≥ 10 vehicles)

Components

Push Buttons (entry and exit)

7-Segment Display

Green, Yellow, Red LEDs

PBSI (Push Button Sensor Interface)

The system is implemented in DMC8 assembly language and uses polling to detect button presses. The master processor updates the vehicle count for both entry and exit and sends the result to the slave processor.
