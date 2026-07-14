# JumperZ Studio

Professional desktop EDA application that bridges a physical breadboard
with a digital design canvas. Users design a circuit visually; the
software reconfigures real hardware in real time through a 400-node
analog switching matrix, with live LED feedback and current measurement.

## My Role
Sole developer of the desktop application and lead of the physical
system design (PCB outlines, connector, enclosure).

## Highlights
- Six-layer domain-driven software architecture (Core, Domain,
  Infrastructure, Services, UI, App)
- Thread-safe publish–subscribe event system across 8 concurrent
  background threads
- USB CDC communication protocol with custom JSON command schema
- Circuit netlist builder (Union-Find) and Manhattan-style routing
  visualisation across a 400-node addressable LED matrix
- Custom RP2040 hardware, CH446Q switching matrix, WS2812B LEDs,
  INA219 current sensing

## Tech Stack
Python · PySide6 (Qt6) · RP2040 · USB CDC · AutoCAD

## Status
Final Year Project — full write-up and media coming soon.
Source code is proprietary; available for review on request.
