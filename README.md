# BC547 LED Switch - KiCad PCB Project

A simple transistor-based LED switching circuit designed using KiCad.

## Project Overview

This project demonstrates a basic LED switching circuit using a BC547 NPN transistor.

The project was designed from schematic creation through PCB layout and Gerber generation.

## Components

| Reference | Component        | Value       |
|-----------|------------------|-------------|
| J1        | 2-pin connector  | Power input |
| R1        | Resistor         | 1kΩ         |
| R2        | Resistor         | 10kΩ        |
| D1        | LED              | 5mm LED     |
| Q1        | NPN Transistor   | BC547       |

## Circuit

The 9V supply is connected to the circuit through J1.

R1 limits the current through the LED, while R2 provides base bias to the BC547 transistor.

The BC547 operates as a switch to control the LED.

## KiCad Workflow

The project was developed using the following workflow:

1. Schematic design
2. Component selection
3. Electrical Rules Check (ERC)
4. Footprint assignment
5. PCB layout
6. PCB routing
7. Design Rules Check (DRC)
8. 3D PCB inspection
9. Gerber generation

## PCB Features

- Through-hole components
- Single-sided PCB routing
- Compact PCB layout
- Beginner-friendly circuit
- KiCad 3D visualization

## Tools:

KiCad 9, Schematic Editor, PCB Editor, 3D Viewer, Gerber Viewer

## Files

```text
├── Schematic/
│   └── BC547_LED_Switch.kicad_sch
│
├── PCB/
│   └── BC547_LED_Switch.kicad_pcb
│
├── Gerber/
│   ├── F_Cu
│   ├── F_Mask
│   ├── F_Silkscreen
│   ├── Edge_Cuts
│   └── Drill files
│
├── Images/
│   ├── Schematic.png
│   ├── PCB_Layout.png
│   └── PCB_3D.png
│
└── README.md
