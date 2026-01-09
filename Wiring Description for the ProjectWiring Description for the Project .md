## Power Distribution
- Battery Pack (7.4V Li-ion 2S) → Buck Converter (DC 6–24V → 5V 5A)
- Converts high-voltage battery power to 5V for the Raspberry Pi and servos.
- Output 5V is fed into:
- Raspberry Pi 4 via GPIO or USB-C power
- PCA9685 servo driver board
- Optional peripherals (FPV camera, LEDs)
### Voltage Regulator (L7805)
- Can provide additional regulated 5V output for low-power modules if needed.
## Controller Connection
- FlySky FS-i6X RC Transmitter → FlySky Receiver (FS-iA6B/T)
- Receiver connects to Raspberry Pi GPIO pins to read PWM signals.
- Optional: PCA9685 can be controlled via I2C from Raspberry Pi for servo signals.
## Servo Wiring
### Servo Motor Pins (VCC, GND, Signal) → PCA9685 Driver Board
- Power: 5V from buck converter
### Signal: I2C commands from Raspberry Pi
- Servo Extension Cables & Jumper Wires route signals from PCA9685 to the servos mounted on arms/legs.
## FPV Camera & Goggles
### FPV Camera
- Connects to battery for power (usually 5V)
- Video output → 5.8G transmitter module
### FPV Goggles
- Receive the 5.8G analog video signal
- Built-in battery powers the goggles
## Connectors & Organization
- JST/XT30 connectors used for battery-to-board connections
- Heat shrink tubing protects solder joints and wire splices
- Male-to-male/female jumper wires and ribbon cables connect GPIO, sensors, and PCA9685 signals
- Ensure wires are routed through internal channels in the 3D-printed torso to prevent tangling and damage.



<img width="903" height="344" alt="image" src="https://github.com/user-attachments/assets/5f795ee0-5390-404a-80d5-95352f5f8eb1" />

