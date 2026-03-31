# 📦 Box Height Sorting System
**PLC: CODESYS V3.5 | Simulation: Factory I/O**

A professional industrial automation solution for real-time box classification. This project focuses on high-speed sorting using a dual-sensor array to distinguish and route items based on their height.

## ⚡ Key Highlights
* **Height Classification:** 2-sensor digital array (High/Low) to identify Tall and Short boxes.
* **Dual Operation Modes:** Seamlessly synchronized between the physical control panel and a custom HMI.
* **Smart Diverters:** Logic-controlled pneumatic pushers for precise routing into exit lanes.
* **Dynamic HMI Feedback:** 
  - Real-time status messages (Idle, Running, Paused, Emergency).
  - Production counters for each box type.
  - Backlit direction indicators for active conveyors.
* **Safety Logic:** Integrated Emergency Stop handling with system-ready monitoring.

## 🏗️ Technical Setup
* **Logic:** **Structured Text (ST)** for the sorting state machine + **Ladder Diagram (LD)** for I/O mapping and HMI sync.
* **State Management:** Robust transitions using **ENUMs** and **CASE OF** logic to ensure deterministic operation.
* **Data Architecture:** Modular design using custom Function Blocks (FBs), Global Variable Lists (GVLs), and STRUCTs.
* **HMI Graphics:** Advanced visual feedback using dynamic color variables (DWORD) for industrial-grade UI.

## 📸 In Action
[System Demo](Media/Height_Sort_Factory_IO_Codesys.gif)
