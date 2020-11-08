# battery-tester
JLCPCB Sponsored Battery Tester PCB Project with Penn Electric Racing

![Battery Tester PCB](https://user-images.githubusercontent.com/14287399/98461428-a2209f00-2171-11eb-851c-0b3c0d586043.png)

The battery tester is a board that will be used to test the charging/discharging of the battery. We charge/discharge the battery via the MOSFETs in the IGBT module, and we are able to control the charge/discharge process by sending signals to these MOSFETs. We can monitor the voltage of the battery multiple ways.

Supplies:

* JLCPCB PCB Manufacturing and Assembly

* The key components in this board are the IGBT Module and the MCU.

IGBT (FF600R12ME4): The IGBT module is a transistor which has the high input impedance and switching speeds of a MOSFET with the low saturation voltage of a BJT. This component takes in signals from the MCU and drivers to control the charge/discharge of batteries.

![IGBT Module](https://user-images.githubusercontent.com/14287399/98461305-adbf9600-2170-11eb-8a29-801513ff2699.png)

Features:

* Low V_CEsat (Saturation voltage, collector-emitter)
* T_vj op (operating junction temperature) = 150°C
* V_CEsat with positive temperature coefficient
* High power density
* Isolated base plate
* Standard housing

MCU (STM32F777VIT6): The MCU is the brain of the board. It takes in signals, performs calculations, then outputs signals. It sends out \Enable, an active low signal, to the IGBT to turn it off if needed.

![MCU](https://user-images.githubusercontent.com/14287399/98461328-e7909c80-2170-11eb-8f4c-ca17ae70a5a5.png)

Features:

* Arm® 32-bit Cortex®-M7 CPU with DPFPU, ART Accelerator™ and L1-cache
* Dual mode Quad-SPI
* Clock, reset and supply management
* Up to 168 I/O ports with interrupt capability
* Low-power
* Debug mode

**JLCPCB Manufacturing and Assembly**

**Step 1: Ordering the PCBs**
![Step 1](https://user-images.githubusercontent.com/14287399/98461464-e6ac3a80-2171-11eb-87b8-73d03b442f44.png)

Now, with our PCB design in hand, it's time to order the PCBs and Assembly. For this step, head to JLCPCB.com, and click on QUOTE NOW.

JLCPCB has sponsored our project. JLCPCB (ShenzhenJLC Electronics Co., Ltd.), is the world's largest PCB prototype company and the leading high-tech manufacturer specializing in quick PCB prototypes and small volume PCB production. You can order PCB and SMT Assembly starting at just $2 for 5 PCBs. You can read more about them on our website here: https://www.pennelectricracing.com/s/JLCPCB-Sponsorship-Document.docx. 

**Step 2: Add Your Gerber File**
![Step 2](https://user-images.githubusercontent.com/14287399/98461472-02174580-2172-11eb-9566-454a12e74ed0.png)

After exporting your gerber and drill files from Altium (see Files section for instructions), compress them and upload your zip file to JLC's website.

**Step 3: Confirm Options**
![Step 3](https://user-images.githubusercontent.com/14287399/98461487-1bb88d00-2172-11eb-899d-3cd1b2b19e98.png)

Here, you can see we successfully uploaded our zip file. We are then able to review our board using the Gerber Viewer function to ensure that both the Top and Bottom layers look good. 

**Step 4: Order Assembly**
![Step 4](https://user-images.githubusercontent.com/14287399/98461507-31c64d80-2172-11eb-883d-d9dbf623a54b.png)

We opted to have JLC assemble the bottom side of our PCB. For this step, we uploaded our BOM file and Pick and Place file exported from Altium, confirmed our part selection from JLCPCB's parts library, and verified the orientation of all of our SMT parts. 

To place the order, hit Save to Cart and then Checkout securely. Our PCBs took less than a week for fabrication and assembly and arrived at our door 3 days after that using the DHL delivery option. We were very happy to receive our well-packaged PCBs, and their quality was excellent. 
