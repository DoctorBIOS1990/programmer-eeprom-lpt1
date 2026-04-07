# SPI-Flash GUI: Low-Level Automation & Firmware Recovery Tool

**SPI-Flash GUI** is a specialized control interface developed in **Delphi** to automate the reprogramming of SPI 25xxx series memories. Originally created during my Pre-Engineer stage, this tool serves as a **Graphical Wrapper (GUI)** for low-level CLI engines (such as <a href="https://rayer.g6.cz/">Rayer</a> SPIPGM), providing a professional and error-free environment for firmware diagnostics and hardware recovery.

## 🚀 Key Features

* **CLI Automation (Wrapper Architecture):** Seamlessly orchestrates command-line tools by abstracting complex syntax into an intuitive graphical interface.
* **Bidirectional Communication:** Handles process execution and shell parameters to interact with the hardware interface via the **LPT1 (Parallel Port)**.
* **Operational Efficiency:** Eliminates manual command entry, significantly reducing human error and optimizing the workflow for electronic technicians.
* **Legacy Interoperability:** Designed to maintain high performance on legacy systems (Windows XP) while managing low-level bitstream communication.

## 🛠️ Hardware & Software Integration

This project was born out of technical necessity in a resource-limited environment, demonstrating **Engineering Resourcefulness**:

* **Software:** Developed using **Borland Delphi v7.0 Enterprise Edition**, leveraging native Win32 performance for hardware-timed operations.
* **Hardware Interface:** Engineered to work with custom electrical schematics for LPT1-to-SPI communication, ensuring signal integrity during the flashing process.
* **Target Hardware:** Specialized in **SPI 25xxx series** (BIOS/UEFI chips), common in motherboards, laptops, and video cards.

## 🛡️ Technical Achievements

* **Process Orchestration:** Implementation of a "Black Box" execution engine that monitors console output and translates it into real-time user feedback.
* **System Abstraction:** High-level management of low-level parameters, allowing technicians to focus on diagnostics rather than command-line syntax.
* **Legacy Preservation:** Actively maintained via **VMware** environments to ensure the tool remains functional for servicing legacy hardware that requires physical LPT1 access.

## 🧠 Engineering Context

This project represents my early transition into **Systems Engineering**. It demonstrates the ability to identify a bottleneck in hardware servicing and engineer a software solution that bridges the gap between complex low-level protocols and user-centric professional tools.

> [!IMPORTANT]
> ### :magnet: Dependencies:
>- ATViewer 3.1.0
>- VCLSkin
>- DevExpress Latino
>- Alpha Skin 8.41
>- Hexeditd
>- 
---

> **Community Impact:** This tool was widely utilized by the electronic technician community in my home country, providing a viable, cost-effective alternative to expensive imported hardware programmers.

<table align="center">
  <tbody>
      <tr>
          <td><img src="https://github.com/DoctorBIOS1990/Programmer-EEPROM-LPT1/blob/main/ScreenShot/Splash.jpeg" width="150"/></td>
          <td><img src="https://github.com/DoctorBIOS1990/Programmer-EEPROM-LPT1/blob/main/ScreenShot/Main.jpeg" width="150"/></td>
          <td><img src="https://github.com/DoctorBIOS1990/Programmer-EEPROM-LPT1/blob/main/ScreenShot/Screen.png" width="150"/></td>
          <td><img src="https://github.com/DoctorBIOS1990/Programmer-EEPROM-LPT1/blob/main/ScreenShot/Schematic%20Electric.jpeg" width="150"/></td>
      </tr>
  </tbody>
</table>



