# Design and Implementation of Microstrip Array Antenna Operating at 5.8 GHz

## 📌 Project Overview
This project was carried out during my **3-month internship (May–July 2025) at Altair Engineering** using **Altair FEKO**.  
The goal was to design and simulate a **rectangular microstrip patch antenna at 5.8 GHz** and extend it into a **2×2 array** for improved gain and directivity.  

## 🎯 Challenge
Single microstrip patch antennas suffer from **low gain and narrow bandwidth**.  
The challenge was to design a **compact antenna at 5.8 GHz** with good impedance matching and then improve its performance using an array configuration.  

## 💡 Solution
- Designed a **single patch antenna** using transmission line model equations.  
- Simulated in **CADFEKO**, analyzed results in **POSTFEKO**.  
- Extended the design into a **2×2 array** with λ/2 spacing.  
- Compared **S11, VSWR, gain, and radiation patterns** between the single and array designs.  

## 📊 Results
- **Single Patch Gain:** ~6.8 dBi  
- **2×2 Array Gain:** ~10.2 dBi  
- **Return Loss (S11):** –17 dB (single) vs –24 dB (array)  
- **Applications:** Radar systems, Wi-Fi, UAV communication, IoT networks  

## 📂 Repository Structure
- `/docs` → Report, presentation, references  
- `/design` → CADFEKO models, screenshots, calculation notes  
- `/results` → Simulation outputs (S11, VSWR, radiation patterns)  

## 🔧 Tools Used
- **Altair FEKO** (CADFEKO + POSTFEKO)  
- Simulation Range: 4 GHz – 7 GHz  
- Substrate: εr = 3.4, h = 1.6 mm  

## 🙏 Acknowledgments
Special thanks to **Anvesh Katta** and **Ramesha** for their guidance and to **Altair Engineering** for providing access to FEKO tools.  

---

### 📜 License
This project is open-sourced under the MIT License.  
