# ManiAmp

ManiAmp is my approach to modern audio amplifier module with DSP and remote control/monitoring.

This project is in early stage of development.

## Description

Maniamp is meant for low power applications, but with PA-centered features.
It should be well suited for portable audio, AV events and installation audio.

It is primarily inteded as module for embeding into small powered speakers (and providing active DSP crossovers) but could be made into standalone unit.

The whole amplifier is targeting simplicity and modificability.

## Hardware Design

Main part shall be single PCB, containing power amplifier, DSP and controller.

Audio amplification is handled by up to two TI TPA3116 / 3118 power ICs.

DSP functionality is handled by Anlog devices ADAU 1701/1401 chips.

Cóntroller is basen on ESP32 module.

The board is meant for 12 - 24V DC power input. AC power supply is out of scope of this project.

## Firmware

TBD