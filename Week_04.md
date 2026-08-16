# Week 04 - Consolidation and Further Study

**Date:** 16 August 2026

## Overview

Following the initial transition into Arduino and embedded systems, the past few weeks were primarily spent consolidating the concepts introduced in Week 03 and investigating the questions that arose during the initial study. Practical Arduino work was temporarily put on hold while I focused on strengthening my understanding of the underlying concepts.

## Concepts Studied

* Arduino Architecture
* Microcontrollers
* Digital Input and Output
* Analog Input and Output
* GPIO
* PWM
* Breadboard Fundamentals
* Capacitors
* Arduino `setup()` and `loop()`
* Arduino `.ino` sketches
* Relationship between Arduino programming and C++

## Key Findings

* Arduino provides a practical interface between software and physical electrical systems.
* Digital pins represent discrete logic states, while analog inputs allow the microcontroller to measure a range of voltage levels.
* PWM does not produce a continuously variable analog voltage. Instead, it rapidly switches a digital output between HIGH and LOW, with the duty cycle controlling the average power delivered to a load.
* Capacitors store energy in an electric field and their voltage cannot change instantaneously in an ideal circuit.
* Arduino `.ino` sketches are written using C++ and are processed by the Arduino development environment before being compiled and uploaded to the microcontroller.
* The `setup()` function is executed once when the Arduino starts, while `loop()` is repeatedly executed afterward.
* Understanding the electrical behaviour behind Arduino functions is important for progressing beyond simply following example programs.

## Research

Investigated the questions raised during the previous week's study, particularly:

### PWM

Explored how PWM can be used to control things such as LED brightness despite an Arduino digital pin only having HIGH and LOW states.

### Capacitors

Studied the basic behaviour of capacitors and why they oppose sudden changes in voltage.

### Microcontrollers

Investigated how an Arduino's microcontroller differs from a general-purpose computer and how uploaded programs are executed.

### Arduino and C++

Clarified the relationship between Arduino `.ino` sketches and C++. Arduino programming uses C++ while providing libraries and a simplified development environment for interacting with microcontroller hardware.

## Open Questions

* How can the behaviour of capacitors be analysed quantitatively using circuit equations?
* How does PWM interact with inductive and capacitive loads?
* How does the Arduino's ADC convert an analog voltage into a digital value?
* How does the microcontroller execute compiled machine code at the hardware level?
* How can the circuit principles studied in MIT 6.002 be directly applied to Arduino projects?

## Reflection

The past few weeks were less focused on producing physical projects and more focused on understanding the concepts introduced during the initial Arduino preparation. This helped clarify several areas that were initially treated as simple Arduino programming concepts but are actually connected to fundamental Electrical Engineering principles.

The main objective going forward is to stop extending the preparation phase unnecessarily and begin applying these concepts through physical experiments. The Arduino Uno R3 Starter Kit is available, so the next stage will focus on building and testing simple circuits while using the theory to understand the results rather than simply following instructions.
