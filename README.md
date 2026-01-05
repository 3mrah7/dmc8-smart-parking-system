Smart Parking Lot System (DMC8)

This project simulates a smart parking lot system using the DMC8 microprocessor and the DEEDS simulator. A master–slave architecture is used where push buttons represent vehicle entry and exit, and the total vehicle count is shown on a 7-segment display.

LED Status

🟢 Green: Parking available (vehicle count < 5)

🟡 Yellow: Parking getting full (5–9 vehicles)

🔴 Red (blinking): Parking full (≥ 10 vehicles)

Components

Push buttons (entry and exit)

7-segment display


How to Run

Open the DEEDS Simulator.

Load the master and slave DMC8 assembly files.

Connect the I/O ports according to the project circuit.

Run the simulation.

Use the entry and exit push buttons to change the vehicle count and observe the display and LEDs.

Green, yellow and red LEDs

PBSI (Push Button Sensor Interface)

The system is implemented in DMC8 assembly language and uses polling to detect button presses. The master processor updates the vehicle count and sends it to the slave processor for display and LED control.
