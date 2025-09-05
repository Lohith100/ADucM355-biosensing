**1\. Project Overview**
------------------------

This repository contains the design files, firmware, and documentation for a **Multi-Modal, Modular Platform for Continuous Wearable Biosensing**. The project focuses on creating a miniaturized, ultra-low-power sensing system capable of performing real-time electrochemical measurements for continuous biomarker monitoring. Built around the **ADuCM355 Precision Analog Microcontroller**, this platform is designed to be highly efficient and portable for a variety of wearable applications.

**2\. Key Features**
--------------------

*   **Miniaturized Design:** A compact form factor of approximately **1cm x 2cm**, ideal for integration into wearable devices.
    
*   **Ultra-Low Power:** Achieves an impressive **50 µW** power consumption in active sensing mode, enabling an extended operational life.
    
*   **High Sensitivity:** Capable of detecting target biomarkers with a sensitivity as low as **0.1mM**.
    
*   **Validated Performance:** The platform's performance was validated against a commercial potentiostat, demonstrating a strong correlation with an **R² value of 0.97** across amperometric, voltammetric, and Electrochemical Impedance Spectroscopy (EIS) tests.
    
*   **Wireless Connectivity:** Integrates a low-latency **BLE module (LBEE5KL1DX-883)** for efficient and reliable data transmission.
    
*   **Extended Battery Life:** Achieves a **5-day operational life** on a single CR927 coin cell battery due to aggressive power management.
    

**3\. Hardware & Software**
---------------------------

### **Hardware**

The system is centered on the **ADuCM355**, which provides a fully integrated analog front-end (AFE) for precise electrochemical measurements. A **BLE module** handles all wireless communication, and the entire system is powered by a **CR927 coin cell battery**. All schematics and PCB layout files are available in the ```Hardware/``` directory.

### **Software**

The firmware is developed using **Keil MDK** for the **ARM Cortex-M3** processor core within the ADuCM355. The code is structured to manage the ADuCM355's AFE, handle data processing, and interface with the BLE module for seamless data transfer. All source code is located in the ```Main/``` directory.

**4\. Project Files & Assets**
------------------------------

This repository includes the following design files and images:

*   **Hardware Design Files**:
    
    *   **Altium** project files for PCB schematics and layout.
        
*   **Firmware**:
    
    *   Source code, project files, and compiled binaries.

![PCB 3D Model](https://github.com/user-attachments/assets/c67bc5bb-dccb-491f-883d-31da3d32d057)
![PCB Design](https://github.com/user-attachments/assets/42c4054b-d329-42a1-ace8-d7a2b304c46d)
![PCB Schematic](https://github.com/user-attachments/assets/a2e5ea89-0ae3-4374-85a6-4a653fdb4996)
