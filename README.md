**8051 Development Board**

**📌 Project Overview**

This project documents the design and implementation of a custom 8051 development board based on the AT89C51RC2 microcontroller. The board was built to support firmware development, peripheral interfacing, and debugging experiments, making it a versatile platform for embedded systems learning and testing.

**Key highlights:**

Integrated regulated power supply, crystal oscillator, and power-on reset circuitry.

Added RS-232 interface (MAX232) for in-circuit programming and UART communication.

Expanded external memory with 32 KB NVSRAM mapped as XRAM using multiplexed address/data bus.

Included LCD, EEPROM, SPI DAC, and I/O expanders for driver development and application testing.

**⚙️ Features**

**Microcontroller Core**

AT89C51RC2 with programmable flash and serial UART interface.

**External Memory Expansion**

32 KB NVSRAM with SPLD-based glue logic for chip-select & address decoding.

P**eripheral Support**

Bit-banged I²C for EEPROM.

SPI DAC for analog output testing.

LCD module for text/visual output.

**Debugging Tools**

HEXDUMP display, read/write operations, and protocol verification with oscilloscope/logic analyzer.

**Scalable Design**

Header pins & expansion ports for adding new peripherals and modules.

**🖥️ Hardware Used**

AT89C51RC2 Microcontroller

MAX232 (RS-232 interface)

32 KB NVSRAM (external memory)

SPLD (for address decoding & glue logic)

LCD Display Module

I²C EEPROM

SPI DAC Module

**🛠️ Tools & Development**

Compiler: SDCC (Small Device C Compiler)

Debugger: Paulmon2 (reference monitor)

Testing: Oscilloscope & Logic Analyzer for protocol validation

**🚀 Getting Started
Prerequisites**

Install SDCC
 for compiling code

Programmer to flash firmware into AT89C51RC2

Serial terminal (e.g., Tera Term) for UART debugging

Example Applications

Displaying messages on LCD

EEPROM read/write using bit-banged I²C

DAC waveform generation via SPI

**📚 Learnings & Outcomes**

Designed a full hardware platform from scratch with microcontroller, memory, and peripherals.

Developed low-level drivers in C for EEPROM, SPI DAC, and LCD.

Strengthened debugging and validation skills using oscilloscope and logic analyzer.

Built a scalable testbed for future embedded projects and experiments.
