# Portfolio
### jacobhackov47@gmail.com | +91 8138090384  
<br/>

# Projects
## Automated NAS & Media Streaming Server
### Tech Stack: Unraid, PC Hardware, Networking, SMB, Docker
Repurposed a legacy Intel Core i5-3470 system into a high-speed network-attached storage (NAS) server running Unraid 7.1.2, integrating a dedicated Gigabit Ethernet card to maximize network throughput. Architected a fault-tolerant storage array utilizing salvaged hardware, featuring a 1TB parity drive, two 500GB storage drives, and a 128GB SSD for high-speed caching. Established secure remote access via a Tailscale virtual private network and configured SMB shares, automating continuous household media backups using PhotoSync for over 200GB of active data. Deployed a Plex Media Server to stream hosted video content locally and remotely, establishing a scalable foundation for hosting future containerized applications.  
<br/>
## RFID-Based Smart Attendance System
### Tech Stack: C/C++, ESP32/Arduino, SPI/I2C Protocols, Bluetooth
Developed a contactless, real-time attendance tracking system utilizing a microcontroller paired with an MFRC522 RFID reader and an I2C LCD. The custom firmware operates over the SPI bus to authenticate, read, and parse 32-byte user name strings from MIFARE tags. Integrated the BluetoothSerial library to enable the secure, trigger-based wireless exportation of attendance logs directly to a mobile device.  
<br/>
## Transit Location Vending Machine Controller
### Tech Stack: Verilog HDL, Intel ModelSim, Digital Logic Design
Designed and simulated a multi-currency vending machine controller driven by a Mealy Finite State Machine (FSM). Modeled in Verilog HDL and validated using Intel ModelSim , the architecture processes real-time inputs for 11 snack options. It features a robust 4-state system (IDLE, ACCEPT, DISPENSE, RETURN) that seamlessly handles exact payments, refunds, and invalid currencies across five global denominations (Rupees, Euros, Dollars, Yen, and Pounds).  
<br/>
## Analog Battery Level Indicator
### Tech Stack: Analog Circuit Design, Multisim, PCB Prototyping
Designed and prototyped an energy-efficient analog circuit to accurately monitor a 12V battery's state of charge, preventing over-discharge. Simulated in Multisim and constructed on a breadboard , the system leverages LM324 Operational Amplifiers acting as voltage comparators. It utilizes a resistor ladder and a 1N4733A Zener diode to establish a constant 5.1V reference voltage , successfully driving an array of LEDs to provide immediate visual feedback on charge thresholds up to 12V.
