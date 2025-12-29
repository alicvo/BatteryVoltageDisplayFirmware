# Battery Voltage Display Firmware

The microcontroller receives ADC values from the main microcontroller via UART. The values are then converted into digital values and processed to generate the correct bit patterns for each pin of the 7-segment decoders.

Battery Voltages:
MAX = 16.9 V
MIN = switch out battery once below 14.4 V
