# Lab Datasheets Repository

This repository contains datasheets and supporting documentation for optoelectronic devices used in Lab 5: Lasers and LEDs.

## 📂 Structure
- `datasheets/LEDs/` → Datasheets for red, amber, green, and blue LEDs  
- `datasheets/Laser/` → Datasheet for the 650 nm laser diode  
- `datasheets/OpAmp/` → Datasheet for the MCP601 operational amplifier  
- `docs/lab_reports/` → Lab reports and analysis (e.g., Lab 5 PDF)

## ⚙️ Configuration
- `.gitignore` excludes OS files, editor temp files, and LaTeX build artifacts.  
- Use consistent naming for datasheets: `deviceName.pdf` (e.g., `red_led.pdf`).  
- Branching strategy: keep `main` clean, use feature branches for adding new datasheets.  
- Tags/releases can mark versions of the repo that correspond to lab submissions (e.g., `v1.0-lab5`).  

## 📖 Usage
Clone the repository and navigate to the relevant folder:
```bash
git clone https://github.com/yourusername/lab-datasheets.git
cd lab-datasheets/datasheets/LEDs
