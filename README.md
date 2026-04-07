# Hi, I'm Riley Hernandez 👋
> WIP! Sorry if you're here early, but hope to have it completed soon.
## Founding Robotics Software Engineer @ Caldo Restaurant Technologies
> Robotics engineer interested in the full stack of hardware products with a background in food robotics, wearables, and industrial automation.

[**Download Resume (PDF)**](./riley-hernandez-resume.pdf) | [**LinkedIn**](https://linkedin.com/in/rileykhernandez) | [**Portfolio**](https://rileyhernandez.com)

---

## 🛠️ Featured Portfolio

### 1. Robotic Food Dispenser (Caldo)
**The Goal:** A robotic dispensing system for accurate portion control in high-vibration commercial kitchen environments for a variety of ingredients.

* [**Control System**](https://github.com/rileyhernandez/node-diagnostics) - Core dispensing control logic.
* [**Calibration and Commissioning App**](https://github.com/rileyhernandez/caldo-calibration) - Rust  based application for commissioning, calibration, and health diagnositics (user interface built with Tauri/Typescript/React). Calibration process can tune device to different ingredient types, dispense amounts, precision, and speed, editing filter parameters and setpoints in local configuration files and syncing changes with the cloud.
* [**On Device Application**](https://github.com/rileyhernandez/ichibui_dos) - Rust application for orchestrating dispensing module with auxillarly IO and user interactions (for operation/maintenance/cleaning) using Tauri/Typescript/React.
* [**Integrated Device Demo (Ryo)**](https://drive.google.com/file/d/1zdWAV8C1D0xQd5xSYEUwLIbrXgmbfKFm/view?usp=drive_link) - Solution integrating multiple dispensing modules along with bag dispensing and sealing.

**Hardware:** Linux SBC (ARM), load cells (w/ microcontroller-amplifier device), conveyors, Teknic servos and controller, linear actuators, limit switches, photoeyes, touchscreen display, EtherCAT IO terminal, heating element, stepper motors, gantry.

**Deployed Units:** 10

---

### 2. Inventory Tracking System (Caldo)
**The Goal:** A weight-based IOT solution for tracking food inventory for stockout alerts and analytics for determining usage patterns and optimizing ordering/restock scheduling.

* [**Scale Interface Library**](https://github.com/rileyhernandez/scale) - Rust crate for managing microcontrollers reading load cell data.
* [**Device Management**](https://github.com/rileyhernandez/menu) - Rust crate for handling product lines, serial numbers, configuration files, and metadata.
* [**Inventory Monitoring System**](https://github.com/rileyhernandez/libra-inventory) - Rust application for core inventory tracking logic detecting discrete changes in weight while filtering out noise and baseline drift.
* [**Project Package**](https://github.com/rileyhernandez/libra-setup) - Debian package for configuring ARM SBCs for deployment.
* [**Commissioning**](https://github.com/rileyhernandez/commission) - Rust application for commissioning inventory tracking devices including configuration file editing and generation, cloud syncing, and testing.
* [**Demo**](https://drive.google.com/file/d/19qYo45nozo5H124iB1lDX8J7dwX0Ugta/view?usp=drive_link) - Early proof of concept for product.

**Hardware:** Linux SBC (ARM), load cells (w/ microcontroller-amplifier devices).

**Deployed Units:** 48

---

### 3. Smart Plugs (Personal)
**The Goal:** Embedded devices for controlling lamps via smart phone.

* [**Orchestrator**](https://github.com/rileyhernandez/light-server) - Rust server for hosting frontend and handling MQTT communication with MCUs over WiFi. Can dynamically detect new clients at runtime.
* [**Client**](https://github.com/rileyhernandez/light-client) - [Rust (Embassy)](https://embassy.dev/) client code for controlling relay modules.

**Hardware:** local server, RP2040 microcontroller, CYW43439 WiFi chip, solid state relay (AC-AC 50A 24-240VAC)

---

### 4. Other
* **[Mezli](https://sf.eater.com/2022/8/17/23308389/mezli-robot-restaurant-open-menu-san-francisco)** - Former engineer at world's first fully automated restaurant.
* **Linux From Scratch** - Building a custom Linux system from source code on an immutable host ([Silverblue](https://fedoraproject.org/atomic-desktops/silverblue/)) inside an isolated container environment (Distrobox).
* **Kernel Development** - Learning Linux kernel and driver development using Rust for Linux (RFL).
* **[Neurotechnology Research](https://rileyhernandez.notion.site/Neurowrist-d0f882f0f6ed4a40908ab01e4a7e4027)** - Designed and built an EMG wearable using biosignals for HCI. 

---
*Built with 🫶 in Oakland, California, USA.*
