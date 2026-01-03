# Smart Parking Lot System (DMC8)

This project simulates a smart parking lot system using the DMC8 microprocessor and the DEEDS simulator. A master–slave architecture is used, where a push button represents vehicle entry and the total count is shown on a 7-segment display.

## LED Indicators
- 🟢 **Green**: Parking is available (vehicle count < 5)
- 🟡 **Yellow**: Parking is getting full (5–9 vehicles)
- 🔴 **Red (Blinking)**: Parking lot is completely full (≥ 10 vehicles)

## Components
- Push Button (vehicle entry)
- 7-Segment Display (vehicle count)
- Green, Yellow, Red LEDs
- PBSI (Push Button Sensor Interface)

The system is implemented in DMC8 assembly language and demonstrates polling-based input handling.
