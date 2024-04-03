# Heatpress

The "Heatpress" is a prototype press designed to melt and mold large sheets of recycled plastic into usable wall panels. This repository holds everything related to the electrical and firmware side of the project.

This project is managed and directed by Dillon Pranger at Illinois Tech - College of Architecture.

## Hardware

The heating elements consist of 25 100w heating cartridges split between a top and bottom plate, where the plates are hydraulically pressed against each other.\
The system as a whole uses around 25A at 120v, as such, is designed for a 30A circuit.

The main controller for the power relays is an STM32 development board.

## Interface

The control interface consists of an 80 character screen, and three buttons, where one button doubles as a rotary switch for selection.

The screen has a basic interface for setting a temperature set-point or manual control of the power relays.
