
# Laptop Cooling Pad

### Overview

Welcome to my laptop cooling pad project.
Here I have described the development of a laptop cooling pad that can change fan speed automatically according to the temperature of the laptop.

![image](https://github.com/tinal28/Laptop-Cooling-Pad/blob/main/photos/IMG-20230725-WA0028.jpg)

### Key Features

- **Automatic speed control** A thermistor sensor is used to measure the temperature of the laptop and according to the value read, fan speed is controlled.

- **PWM technique is used** speed of the fan is controlled using a PWM signal created using NE555 IC.
- **Better gaming experience** Included better low cost LED system in order to give a better gaming experience.

- **Proper ventilation** 3 fans are included to give a proper ventilation and a metel enclosure is also used to ensure a goog thermal conductance.
  
- **USB power in** Micro USB port is used to give 12V power in.

### *_Here you can find my_* 
- _Design Cycles (Conceptual Design & Preliminary Design)_
- _Circuit Designs_
- _PCB Designs_
- _Enclosure Design_
- _Component Selection and Supply Chain_

### Circuit Design

The main controlling circuit plays a major role in this project. This project is a complete **Analog electronic project**.
- **Power Supply** 12V DC power supply is used to power up the PCB, then 12V is converted into 9V in order to power up the fans and LEDs.

- **Input Signal** Input signal is taken using a 10k potentiometer or 10k NTC thermistor. This circuit have both automatic and manual controlling facility.

- **PWM signal** NE555 IC is used to generate the required PWM signal according to the given input temperature reading.

- **Output Signal** Generated PWM signal is amplified using a IRFZ44N power MOSFET.

### PCB Design

My PCB design plays a key role in the product's functionality and durability:

- **Precision Design:** Crafted using Altium Designer, our PCB design meticulously considers signal interferences and current requirements.

- **Layer Stack:** The 2-layer PCB features a well-defined layer stack.

- **SMD Components:** We've opted for surface-mount device (SMD) components to achieve a compact and space-efficient design without compromising performance.

![Final PCB Design](https://github.com/tinal28/Laptop-Cooling-Pad/blob/main/photos/pcb.png)

## Enclosure Design

The enclosure design adds both style and support and better ventilation to the cooling pad:

- **Metalic design:** We have used Stainless Steel and Aluminium metel to create the enclosure. 
- **Solidworks Software:** Using Solidworks, sheet metel, I've meticulously designed the enclosures and created a prototype.

![Final Design](https://github.com/tinal28/Laptop-Cooling-Pad/blob/main/photos/enclosure.png)

### I have added all the design files including PCB, Enclosure, Simulation files.



