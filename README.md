# Xiang Wang

Mechanical engineering senior at Penn State with a minor in mechatronics, graduating December 2026. My work spans mechanical design, power and motor control electronics, and embedded firmware. I am looking for full time hardware and robotics engineering roles.

[LinkedIn](https://linkedin.com/in/xiangwang102) · [Email](mailto:20o5xwang@gmail.com)

## Featured project: Autonomous Tracking Turret

<img src="assets/cycloidal_drive.gif" alt="Assembly animation of the 12:1 cycloidal reducer on a NEMA 17 stepper" width="760">

Two axis turret that tracks a person and keeps them centered in the camera frame. Built in two weeks for under $150 with a University of Maryland student, who wrote the pose tracking software.

- **Mechanical:** 12:1 and 18:1 cycloidal reducers, designed in SolidWorks and 3D printed, on NEMA 17 steppers. 360° azimuth and −30° to +80° pitch.
- **Electrical:** ESP32 controller, A4988 stepper drivers on a 12 to 24 V rail, AS5600 magnetic encoder on the pitch axis, and relay switched 12 V solenoids for pneumatic actuation.
- **Firmware:** the ESP32 streams camera video over WiFi and converts UDP aim corrections from the tracking software into stepper moves.

[Code, CAD, and wiring schematic](https://github.com/xiang-wang-US/Stepper-Pneumatic-Turret)

## Experience

**Microsoft** · Mechanical Engineering Intern, Surface Hardware · Summer 2026\
Designed and prototyped a user serviceable mounting architecture for a device input component. Modeled in Creo and built over multiple prototype cycles, consolidating 6 CNC machined parts into 2 formed sheet metal parts. Delivered a tradeoff analysis across mechanical, cost, industrial design, and RF impact.

**The Learning Factory, Penn State** · Machine Shop Instructor · 2024 to 2026\
Trained students on safe operation of 30+ machines, including mills, lathes, and welders, in a shop serving 500+ students and faculty weekly.

## Other projects

**Heavy Lift Drone** · ASME Design Team, electrical subsystem lead · 2026\
Power distribution, cable fabrication, and motor control for a drone rated to lift 30 lb. Reduced a carbon fiber tube coupling from 10 components to 6, cutting its weight 14%.

**Combat Robot** · ASME Design Team, electrical subsystem lead · 2026\
Power, motor control, and radio systems for a 6 lb combat robot that placed 2nd of 16 teams.

**Competitive Hovercraft** · ASME Design Team, lead engineer · 2024\
Led a team of 16 to build a hovercraft on a $100 budget that placed first. Selected the skirt material with a weighted trade study of 8 materials against 10 criteria.

**Klipper Printer Rebuild** · 2024\
Reflashed and tuned a 3D printer on Klipper firmware, cutting print time 70% with equal or better quality.

## Skills

- **CAD and analysis:** SolidWorks, Creo, Fusion 360, FEA, CFD, DFM/DFA, tolerance stackup
- **Electronics and controls:** ESP32, motor control, power distribution, PCB design, digital logic and FSM design, soldering
- **Programming:** embedded C++, MATLAB, VHDL
- **Fabrication:** sheet metal, welding (MIG, TIG, stick), lathe, mill, 3D printing, laser engraving
