![QUTMS Banner](https://github.com/QUT-Motorsport/QUTMS_Master/blob/master/src/qutmsBanner.jpg?raw=true)

# Battery Management System
Each pack inside the accumulator has it's own dedicated battery management which reports cell status and fault modes to the AMS.

## Features

- Balancing and cell voltage sensing using the MAX14920ECB+
- Temperature sense board demultiplexing
- Galvanically isolated CANBUS communication with the AMS
- Isolated fault line to send BMS fault signal to AMS
