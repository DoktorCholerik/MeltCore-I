## MeltCore-I
is a powerful, open-source high-temperature 3D printer designed for extreme materials and demanding applications. Built on a modified HevORT architecture, MeltCore-I brings industrial-grade capabilities into the hands of makers, researchers, and small businesses.

---

## Key Features

- **Hotend up to 500 °C**  
  Industrial-grade **Chube hotend**, water-cooled for continuous high-temp printing

- **Enclosed heated chamber >120 °C**  
  Powered by dual **400 W PTC heaters** with active temperature control

- **Custom heated bed 1600 W @ 230 V**  
  Excellent thermal stability for PEEK, PEI, PA-CF and more

- **Large print volume: 410×410×330 mm (XYZ)**  
  In a compact 750×820×785 mm footprint

- **CoreXY kinematics with NEMA 23 JMC closed-loop servos**  
  Based on the **HevORT** motion system for high speed and accuracy

- **Watercooled VzHextrudort with watercooled 6t stepper**  
  Optimized for high-strength filament drive and heat resistance

- **Precision bed motion with belts + 10:1 planetary gear steppers**

- **Beacon sensor**  
  For accurate bed leveling and high-resolution probing

- **CPAP blower for active part cooling**  
  Controlled via PWM for reliable high-volume airflow

- **Runs on Kalico firmware**  
  Powered by **Octopus Pro mainboard** and **Raspberry Pi 5**  
  Full support for input shaping, remote tuning, and high-speed performance
  
---

## Firmware & Electronics

- **Firmware**: Kalico - Klipper based 
- **Mainboard**: 2x BigTreeTech **Octopus Pro**  
- **Host**: **Raspberry Pi 5**
- **Temperature control**: PT1000 sensors, solid-state relays for bed and chamber and 230v electronics fans 
- **Motion**: NEMA 23 closed-loop servos on XY, planetary gear stepper on Z  
- **Extruder**: VzHextrudort as main extruder, and secound extruder with custom belay to counter long ptfe tube 
- **Cooling**:  
  - **Water-cooled hotend assembly**  
  - **CPAP blower** for high-efficiency part cooling  
  - Active electronics cooling with filtered airflow

---

## First Look

Is posted – BOM, Build Guide, real-world print samples and performance tests of PEEK, PEI, PA-CF will follow in near future.

---

## 🤝 Contributing

All contributions are welcome – whether you want to improve documentation, fork the mechanics, or test firmware. Open an issue or pull request, or start a discussion!

---

## 📬 Contact

For feedback, collaboration, or community support, open an issue or reach out via Discord.

Follow development and updates here on GitHub.

---

## ⚠️ Safety Notice & Legal Disclaimer

**MeltCore-I** is an advanced **DIY high-temperature 3D printer platform** intended for experienced makers, engineers, and small businesses.  
It is designed for printing engineering-grade materials and requires careful handling during assembly and operation.

---

> ⚠️ **This is not a plug-and-play printer.**  
> MeltCore-I is a high-performance research and prototyping tool. Building and operating it requires technical knowledge in electronics, motion control, and thermal safety.

---

### 🔒 Safety Guidelines

Please follow these principles during your build:

- Use certified components and proper wiring techniques  
- Install thermal fuses, SSRs, and firmware-based thermal runaway protection  
- Follow electrical codes and insulate high-voltage sections appropriately  
- Ensure adequate enclosure ventilation for electronics and high-temp zones  
- Use protective equipment during testing and maintenance  
- Never leave the printer unattended during operation

---

### ⚖️ Legal Notice

MeltCore-I is an **independent, community-driven open hardware project**.  
It is **not affiliated with**, endorsed by, or officially supported by any third-party hardware or firmware creators.

All product names and trademarks are the property of their respective owners.  
This project integrates open-source components in good faith under their respective licenses to provide a **new, capable tool for the community**.

> 🛠️ **No warranty or liability is implied.**  
> Use this project at your own risk. Always comply with local safety regulations and workplace standards.

---
