# PixelWater-Open-Source-
PixelWater is an open-source project that combines electronics, fluid mechanics, and creative technology to create visual effects with falling water. Using an Arduino-based controller, 16 solenoid valves, and a strobe LED light, the system generates floating images, patterns, and animations with columns of water in mid-air. 

# 🌊 PixelWater

PixelWater is an **open-source hardware and software project** that explores the intersection of **electronics, fluid mechanics, and visual art**.  
It uses **16 high-speed solenoid valves** to control falling water streams in precise patterns, combined with a strobe light to create the illusion of floating or animated images in mid-air.  

This repository includes all the necessary resources to replicate, study, and improve the project:
- Arduino firmware (C++)
- PCB schematics and layouts
- 3D printable parts for the valve body
- User manuals and technical documentation

---

## 🎯 Project Goals

- Democratize access to experimental water display technology.  
- Provide a **modular, low-cost, and educational platform** for students, makers, and researchers.  
- Encourage **community-driven innovation** in art, education, and engineering.  

---

## ⚙️ How It Works

1. **Solenoid Valves**: Open and close rapidly to release water drops at precise intervals.  
2. **Arduino Control**: Microcontroller processes patterns (binary sequences) and synchronizes valve timing.  
3. **Strobe Light**: Flashes at the right moment, “freezing” the falling water into a visible shape.  
4. **Modularity**: Each valve body + solenoid is independent, allowing scalability and customization.  

---

## 📂 Repository Contents

- `/firmware` → Arduino `.ino` code  
- `/hardware` → PCB schematics, layouts, and bill of materials (CERN OHL v2)  
- `/3d_models` → STL files for 3D-printed valve bodies and mounts  
- `/docs` → Manuals, guides, and schematics (CC-BY-SA)  
- `/examples` → Pattern sequences and animations  

---

## 📜 Licenses

PixelWater is a **fully open-source project**:

- **Firmware**: [GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html)  
- **Hardware (PCBs & 3D parts)**: [CERN OHL v2](https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2)  
- **Documentation & Media**: [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)  

👉 In short: You are free to use, modify, and distribute this project, **as long as derivative works remain open**.

---

## 🚀 Getting Started

1. Clone or download this repository.  
2. Install [Arduino IDE](https://www.arduino.cc/en/software).  
3. Open and upload `/firmware/PixelWater.ino` to an Arduino UNO.  
4. Assemble the hardware following the [User Manual](docs/Manual.pdf).  
5. Power with a **12V / 15A supply** and enjoy your first water patterns!  

---

## 💡 Applications

- Educational demonstrations (physics, electronics, fluid dynamics)  
- Interactive art and installations  
- Novel advertising and visual displays  
- Research platform for control systems  

---

## 👥 Contributing

PixelWater is **community-driven**.  
You can contribute by:
- Improving firmware performance and adding new patterns  
- Designing alternative PCBs or drivers (e.g. I²C expanders)  
- Enhancing the 3D models of valve bodies  
- Sharing your builds, experiments, and documentation  

👉 Contributions are welcome via **pull requests** and discussions.  

---

## 🙌 Acknowledgments

This project started as a **student initiative** with very limited resources, built on top of open-source tools like **Arduino** and **FreeCAD**.  
Thanks to the open hardware/software community for the inspiration and the tools to make this possible.  

---

## 📧 Contact

For questions, collaboration, or sharing your build:  
**Email**: [19041104@itdurango.edu.mx]  
**GitHub Issues**: Open an issue in this repo  

---

✨ *PixelWater: turning falling water into open-source pixels.*
