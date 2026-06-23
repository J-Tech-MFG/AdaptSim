# AdaptSim

> Open-source sim racing controls built from readily available hardware.

AdaptSim is a DIY sim racing ecosystem built around the idea that you should be able to create high-quality sim hardware using components you already have access to.

Instead of requiring exact hardware kits, STEP files are provided so builders can adapt the designs to their own components and fabrication methods.

---

## Features

### Pedals

- Load-cell brake pedal
- 200kg load cell
- HX711 amplifier
- Hall-effect throttle
- Hall-effect clutch
- KY-035 analog hall sensors
- 8mm × 3mm neodymium magnets

### Shifter

- H-pattern shifter
- 4x KW11-3Z-C limit switches
- 8mm linear rods
- LM8UU linear bearings
- Fully printable construction

### Wheel

- FFBeast direct drive wheel
- 6.5" hoverboard motor
- MT6701 magnetic encoder
- 24V power system

### SimHub Integration

- Dual pedal rumble
- Wind simulation
- Speed-based airflow
- Drafting effects
- Wheel lock feedback
- ABS feedback
- Traction control feedback

### Electronics

- STM32F407VET6 USB controller
- Modular RJ45 wiring
- Arduino-based SimHub accessories

---

## Philosophy

AdaptSim was designed around hardware I already had available.

The goal is not to create a kit that requires exact part numbers.

The goal is to provide adaptable CAD models that builders can modify to fit their own hardware.

Because of this:

- STEP files are provided
- Hardware counts are approximate
- Builders are encouraged to modify the designs
- Alternative hardware is expected

---

## Hardware Used

### Main Controller

- STM32F407VET6 Black Board

### Pedals

- 200kg Load Cell
- HX711 Amplifier
- 2x KY-035 Hall Sensors
- 2x 8mm × 3mm Neodymium Magnets
- 608 Bearings

### Shifter

- 4x KW11-3Z-C Limit Switches
- LM8UU Bearings
- 8mm Linear Rod

### Wheel

- 6.5" Hoverboard Motor
- MT6701 Encoder
- FFBeast Controller
- 24V 10A Power Supply

---

## SimHub Pedal Rumble

### Controller

- Arduino Pro Micro

### Driver

- DRV8833 Dual H-Bridge

### Motors

- 2x Xbox Controller Rumble Motors

### Power

- 5V 2A USB Supply

---

## SimHub Wind Simulation

### Controller

- Arduino Pro Micro

### Fans

- 2x Thermalright TL-C12C PWM Fans

### Power

- 12V 1A Power Supply

Features:

- Vehicle speed airflow
- Drafting effects
- Left/right wind balancing

---

## Attribution

### Pedals

Based on:

https://www.printables.com/model/1394243-sim-racing-pedals-with-load-cell-v2

The original STEP files were used as a starting point and modified extensively.

### Shifter Inspiration

Inspired by:

https://dazprojects.com/products/h-shifter-3d-models

No CAD files, models, or drawings from that project were used.

The shifter included here was modeled independently from scratch.

---

## License

See LICENSE for details.
