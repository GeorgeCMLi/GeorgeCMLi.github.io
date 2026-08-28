# Personal Technical Projects

## Navigation
* [Home](README.md)
* [About Me](about.md)
* [Collegiate Rocket Work](rpl.md)
* [Personal Projects](myproj.md)
* [Contact Information](contact.md)

## My Personal Technical Projects
1. SLAYER Flight Computer
2. Teeny Flight Computer
3. Cloud Buck Converter
4. W.I.P 915MHz RF Transceiver Board
5. W.I.P Fighting Game Controller

## 1. SLAYER Flight Computer [SLAYER Files](SLAYER_FlightComputer/Technical)
### Overview
SLAYER is a flight computer designed to fit inside a small sized model rocket to collect altidude and IMU data. The computer design is centered around an ESP32-C3-Mini-1U module which provides sufficient computational power as well as the capability of wireless communication.

### Details
- ESP32-C3-Mini-1U Module as MCU
- LSM6DSMTR IMU
- BMP581 Barometric Pressure Sensor for altitude reading
- W25Q128JVSIQ 16 MB SPI Flash Memory Storage
- Support for 1 pyrotechnic such as deploying parachute during flight
- Status LEDs
- 2.15" x 1.55" x 0.35" PCB

### Criteria
[Project Proposal PDF](SLAYER_FlightComputer/NonTechnical/SLAYER_ProjectProposal.pdf)
<br>
<img width="400" height="512" alt="SLAYER_ProjectProposal" src="https://github.com/user-attachments/assets/7da60d00-99dc-4571-96db-51dd1001a070" />

[Project Requirements PDF](SLAYER_FlightComputer/Technical/SLAYER_Requirements.docx)
<br>
<img width="400" height="512" alt="SLAYER_Requirements_Page1" src="https://github.com/user-attachments/assets/76b0b66d-ae1f-4564-8504-381365d28f2e" />

### [Project Schedule](SLAYER_FlightComputer/NonTechnical/SLAYER_Gantt.xlsx)
Download .xlsx above.
### [Trade Study](SLAYER_FlightComputer/Technical/SLAYER_TradeStudy.xlsx)
Download .xlsx above.
### Altium Files &nbsp; [SLAYER Altium Project](SLAYER_FlightComputer/Technical/SLAYER_Altium) &nbsp; [Bill of Materials](SLAYER_FlightComputer/Technical/SLAYER_Altium/Project%20Outputs%20for%20SLAYER_Altium/SLAYER_BOM_V1.xlsx)
I recommend downloading the SLAYER_Altium folder as it included all symbol, footprint, and CAD files for schematic and layout to avoid library issues. 



<br><br>
## 2. Teeny Flight Computer [Teeny Files](Teeny_FlightComputer/Technical/Altium%20Files/Teeny)
### Overview
Inspired by BPS Space's "Smallest Flight Computer" video (I'm a huge fan). I tried to make Teeny smaller than 16mm x 17mm while also adding a microSD slot but the slot took too much space. After many iterations in layout and component selection I managed to minimize the PCB footprint to 1" x 0.6" or about 25.4mm x 15.24mm. This project as less serious than SLAYER so no formal timeline or proposal was written.

### Details
- ATSAMD21E18A-MUT as a microcontroller
- LSM6DSRXTR IMU
- MicroSD Card Slot for storage
- Status LED
- 1" x 0.6" x 0.2" PCB

### Altium Files &nbsp; [Teeny Altium Project](Teeny_FlightComputer/Technical/Altium%20Files/Teeny) &nbsp; [Bill of Materials](Teeny_FlightComputer/Technical/Altium%20Files/Teeny/Project%20Outputs%20for%20Teeny/Teeny_BOM_V1.xlsx)



<br><br>
## 3. Cloud Buck Converter [Cloud Files](Cloud_BuckConverter)
### Overview
I noticed that current market options for a 5V buck converter could not handle much current with the highest one I found being able to do 5 A. So I decided to make my own both for personal use and as a challenge and opportunity to sharpen my embedded skills. The process included finding an appropriate switcher, capacitors, inductors, and trace calculations which ended up in a 9-24V input to 5V output 10 A design.

### Details
- TPS56A37RPAR as main step down chip
- Reverse polarity protection through PNP MOSFET
- Fused at input
- Status LEDs
- 2.4" x 1.83" x 0.5" PCB

### Criteria
[Project Proposal PDF](Cloud_BuckConvertor/NonTechnical/CloudBuck_ProjectProposal.pdf)

### Project Schedule
[Cloud Gantt](Cloud_BuckConvertor/NonTechnical/CloudBuck_Gantt.xlsx)

### Altium Files &nbsp; [Cloud Altium Project](Cloud_BuckConvertor/Technical/Cloud_Altium_Files/Cloud_BuckConverter) &nbsp; [Bill of Materials](Cloud_BuckConvertor/Technical/Cloud_Altium_Files/Cloud_BuckConverter/Project%20Outputs%20for%20Cloud_BuckConverter/Cloud_BuckConverter.xlsx)
