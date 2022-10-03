# Relay_board_Safety_System
This is repo containing the design details for constructing a relay board with CAN integration

I created a relay system that is driven by an Atmega32u4 and has CANBUS compatibility.
An Atmega32u4 is used to power the relay box and track the status of the shutdown systems. The relay box is also connected to the CAN bus using the MCU. This allows us to communicate the fault to the driver via the driver interface and allows the vehicle's control systems to be aware of the shutdown state as well.
