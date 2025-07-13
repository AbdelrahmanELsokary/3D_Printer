# 🖨️ 3D Printer Project (Open Source)

An open-source 3D printer project built using **Arduino Mega 2560** and **RAMPS 1.6**.  
This project aims to provide a fully customizable and affordable 3D printing solution for hobbyists, makers, and engineers.

---

## 🚀 Features

- ✅ Based on **Marlin Firmware** (2.1.2.4)
- ✅ Supports **12864 LCD**
- ✅ Designed for **PLA** filament
- ✅ Manual calibration + test models included
- ✅ Easy to build & modify

---

## 🧰 Hardware Used

| Component         | Description                     |
|-------------------|---------------------------------|
| Arduino Mega 2560 | Main controller                 |
| RAMPS 1.6         | Motor & heater driver board     |
| A4988 Drivers     | Stepper motor drivers           |
| 12864 LCD         | User interface                  |
| NEMA 17 Motors    | X, Y, Z axes and extruder       |
| Power Supply      | 12V or 24V                      |

---

## 🖥️ Software & Firmware

- **Firmware:** Marlin 2.1.2.4  
- **Host Software:** [Ultimaker Cura](https://ultimaker.com/software/ultimaker-cura)  
- **Slicing Tools:** Cura, PrusaSlicer, etc.

---

## 🧪 Test Models

Included under `models/`:
- Calibration cube (`xyzCalibration_cube.stl`)
- G-code samples
- Preview models (`.glb`)

---

## ⚙️ Configuration

Firmware settings adjusted for:

- **Steps/mm:**
  - X: 80
  - Y: 80
  - Z: 400
- **Movement Area:**
  - X: 220 mm
  - Y: 220 mm
  - Z: 250 mm

Configured in `firmware/Marlin_V2/Marlin-2.1.2.4/Marlin/Configuration.h`

---

## 🛠️ Build Instructions

1. Flash Marlin firmware using [PlatformIO](https://platformio.org/)
2. Wire up RAMPS, motors, endstops, and heaters
3. Connect LCD and calibrate movement
4. Test with included `.gcode` files

---

## 🤝 Contributing

Pull requests are welcome. Feel free to fork and suggest improvements.

---

## 📄 License

MIT License – use, modify, and distribute freely.

---

## 📫 Contact

If you have questions, feel free to open an issue or reach me at:

📧 `abdalrahmanelsokarey@gmail.com`

📱 `01022873425`


## 🛠️ Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/AbdelrahmanELsokary/3D_Printer.git
