# UART-Implementation
The Universal Asynchronous Receiver Transmitter protocol is a communication protocol which is not synchrnous with clock and is based on serial transmission of Bits. It uses special bits like stop bit, start bit, and parity bit. 
These bits are generated in the Transmitter Block of the UART. The transmitter contains the following blocks: PISO register(parrlel input serial output), Transmitter FSM, MUXs, Parity bit generator. 
The Receiver detects the start bits and receiives the message using the SIPO register (serial input parllel output register. The Receiver contains the following block: SIPO register, Parity bit check, Start bit detector, Stop bit detector, Receiver FSM
