
# 🚗 MATLAB Shock Absorber Force Tester

This MATLAB application is designed to **test and calculate the pressure/force** inside a shock absorber using data collected from a **load cell sensor** connected via **PLC (Programmable Logic Controller)**.

## 🧰 Features

- 📡 **Serial Communication with PLC** to read real-time force values.
- 📊 **Live Data Plotting** of Force vs Distance.
- ✅ **Calculation of Key Metrics**:
  - Desired Newton Force
  - Stroke Length
  - Up/Down Tolerances
  - Calculated Force Ranges
  - Individual Force Points (F1, F2, F3, F4, FR)
- 💾 **Save & Export** test results.
- 🆘 **Emergency Stop** functionality.
- 🖨️ **Printable Graphic Reports** with metadata: responsible person, reference number, and date.

## 🖼 Interface Preview


![image](https://github.com/user-attachments/assets/90b170d4-1c8e-4ef7-b272-2531e66e01ef)



## 🔌 How It Works

1. Connect your **PLC via COM port** (e.g., COM7).
2. Press **"Start Test"** to begin reading data from the load cell.
3. The application will **record, plot, and calculate** key values.
4. View or save the test results and graphical output.
5. Use **"Emergency Stop"** to halt the operation safely.

## 📂 Installation

This application runs on **Windows systems** with MATLAB installed.

> ⚠️ You must have MATLAB installed with necessary toolboxes (e.g., Instrument Control Toolbox) for serial communication.

## 👨‍🔧 Developed by

Abdulaziz Fahmy – Electrical and Electronics Engineering Student  
[Uludağ University](https://uludag.edu.tr)

---


