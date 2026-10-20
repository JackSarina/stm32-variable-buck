# stm32-variable-buck (In Progress)
A digitally-controlled variable DC-DC buck converter powered by the **LTC3851** switching controller and managed by an **STM32** microcontroller (via an I²C digital potentiometer or PWM feedback trim).

## Project Status

- [x] LTSPICE simulation of analog buck stage
- [ ] Schematic and PCB design (Altium)
- [ ] Firmware development for SMT32
- [ ] Physical prototyping and testing

## Hardware

- **DC Controller:** LTC3851 Step-down Controller
- **Switching Elements:** RJK0305DPB N-Channel MOSFETs
- **Control Interface:** SMT32 Nucleo Board
- **Feedback Control:** I²C Digital Potentiometer

## Repository Layout 

- 'hardware/ltspice/' - Simulation files for the power stage.
- 'hardware/altium/' - PCB schematics and layout files.
- 'firmware/' - SMT32 initialization and control code. 
