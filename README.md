# TASK-2-HOME-AUTOMATION

*COMPANY*: CODTECH IT SOLUTION

*NAME*:K.KAVIVARMAN

*INTERN ID*: CT04DH284

*DOMAIN*:Internet Of Things

*DURATION*:4 WEEKS

*MENTOR*:Neela Santhosh 

## DESCRIPTION

# 🏠 Task 2: Home Automation System – IoT Internship (CODTECH IT Solutions)

##  Overview

As part of my IoT internship at *CODTECH IT Solutions, I developed a simple **Home Automation System* using Arduino UNO and the Wokwi online simulator. This project simulates the control of home appliances — specifically a *Blue LED as a Light* and a *Red LED as a Fan* — using the *Serial Monitor* as a virtual app interface.

##  Functionality

- A → Turns ON the *Light (Blue LED)*
- a → Turns OFF the Light
- B → Turns ON the *Fan (Red LED)*
- b → Turns OFF the Fan

Commands are sent via the Serial Monitor to simulate mobile app control.

## Tools & Components

- Arduino UNO (Wokwi)
- Blue LED (Light)
- Red LED (Fan)
- 2 x 220Ω Resistors
- Jumper Wires
- Serial Monitor (App simulation)

##  Circuit Setup

| Device | Arduino Pin | LED Color | Resistor | GND |
|--------|-------------|-----------|----------|-----|
| Light  | 13          | Blue      | 220Ω     |     |
| Fan    | 12          | Red       | 220Ω     |     |

- Each LED's anode is connected to the respective digital pin.
- Each cathode is connected to GND via a 220Ω resistor.

##  Code Summary

The Arduino reads characters from the Serial Monitor and toggles each output pin accordingly to control the simulated appliances.

##  Status

 Successfully tested on Wokwi Simulator  
 Blue LED = Light,  Red LED = Fan

##  Simulation Link

[Click here to open in Wokwi](#) (https://wokwi.com/projects/435879867347718145)

---

## OUTPUT

![Image](https://github.com/user-attachments/assets/94685632-b884-4a46-93c3-16a82e370fa3)
![Image](https://github.com/user-attachments/assets/59cf8631-bfdf-4d6b-b8d1-f5a973ab2aa5)
![Image](https://github.com/user-attachments/assets/c2edf360-6fef-4a7c-9b15-b2e9b5e039cf)
