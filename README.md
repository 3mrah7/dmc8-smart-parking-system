Smart Parking Lot System (DMC8)

This project simulates a smart parking lot management system using the DMC8 microprocessor and the DEEDS simulator. A master–slave architecture is used, where two push buttons represent vehicle entry and exit, and the total vehicle count is displayed on a 7-segment display.

The master processor handles input detection using polling and maintains the vehicle counter, while the slave processor receives this value and controls output peripherals to indicate parking status in real time.

LED Indicators

🟢 Green: Parking is mostly empty (vehicle count < 5)

🟡 Yellow: Parking is getting crowded (5–9 vehicles)

🔴 Red (Blinking): Parking lot is full (10 or more vehicles)

Components

Push Buttons (vehicle entry and exit)

7-Segment Display (vehicle count)

Green, Yellow, Red LEDs

PBSI (Push Button Sensor Interface)

Techniques Used

The system is implemented in DMC8 assembly language and demonstrates polling-based input handling, master–slave communication via I/O ports, and peripheral interfacing.
