![header](https://github.com/royyandzakiy/royyandzakiy/blob/master/docs/header.png)

# Hi, I’m Royyan

Senior Embedded / Firmware Engineer  
C++ • RTOS • Zephyr • ESP-IDF • Systems Architecture

I work on embedded systems that need to behave predictably in the real world.  
From bare-metal and RTOS firmware to device-to-desktop tooling, I focus on designs that are explicit, debuggable, and maintainable over time.

Primarily an individual contributor. I also contirbute into technical leadership discussing architecture, direction, or system boundaries.

## Currently

- Embedded Software Engineer at **LMesh IoT**
- Working on medical and industrial IoT systems using Zephyr, FreeRTOS, and various connectivity stacks
- Based in the Netherlands, working remotely

---

## How I think about software

- Code should be understandable and structured such that it's readable
- Explicit state and data flow means less time during debugging
- Event-driven designs that embraces modularity scale better than tightly coupled "efficient" control logic
- Tooling, build systems, developer experience, documentations should all be first class. Code should be made to be left behind and then seamlessly continued by the next contributor/employee
- Production constraints are part of the design, should.be early on, should be prepared for future changes

I enjoy experimenting with language features, patterns/idioms, and abstractions, whilst actively measuring the trade-offs and performance (especially in embedded systems).

---

## What I work on

- Embedded firmware for IoT, medical, and industrial devices
- RTOS-based systems using Zephyr and FreeRTOS
- Connectivity-heavy devices using BLE, Wi-Fi, and MQTT
- Sensor data acquisition under real-time and throughput constraints
- Previously also on rugged offline-first smart farming feeders mainly utilized in rural areas with minimal to no connectivity infrastructure
- Firmware architecture, refactoring, and system cleanup
- Native Windows tooling for device communication and diagnostics

---

## Core technologies

**Languages**
- C and Modern C++
- Python for tooling and scripting
- TypeScript for automation and internal tools

**Embedded and Systems**
- Zephyr RTOS, FreeRTOS
- ESP-IDF, nRF SDK
- State machines and event-driven designs
- Low-power systems, high data-rate systems

**Connectivity**
- BLE, Wi-Fi
- MQTT
- Custom binary protocols

**Tooling**
- CMake
- CI/CD for firmware projects
- Static analysis
- GoogleTest

---

## Selected repositories

These repositories are mostly explorations of architecture, language features, or tooling choices. Some are experimental by design.

Most of these projects exist to explore ideas, validate assumptions, or support real work.

### Embedded Systems
- **[multisensor-station](https://github.com/royyandzakiy/multisensor-station)**  
  Modular multi-sensor firmware architecture focused on extensibility and clear separation of concerns.

- **[esp-freertos-tutorial](https://github.com/royyandzakiy/esp-freertos-tutorial)**  
  Practical FreeRTOS patterns on ESP32, with an emphasis on task structure and concurrency clarity.

- **[zephyr-modern-cpp](https://github.com/royyandzakiy/zephyr-modern-cpp)**  
  Experiments using modern C++ features on Zephyr and ESP-IDF, including concepts, variants, and alternative state machine approaches.

- **[LoRa-RHMesh](https://github.com/royyandzakiy/LoRa-RHMesh)**  
  Early work around LoRa mesh networking and packet routing.

### Tooling and Architecture
- **[windows-lib-cpp-template](https://github.com/royyandzakiy/windows-lib-cpp-template)**  
  A C++ library template with structured CMake, CI, and native Windows integration.  
  Used internally in real projects.

- **[balancer-robot-workspace-manifest](https://github.com/royyandzakiy/balancer-robot-workspace-manifest)**  
  Zephyr and west workspace setup for a balancing robot project. Here is.the professional setup for Zephyr projects that I use in real work.
  
- **[gmock-sfinae-concepts-calculator](https://github.com/royyandzakiy/gmock-sfinae-concepts-calculator)**  
  Testing suite setup using templates, SFINAE, C++20 concepts.

---

## Contact

- LinkedIn: https://www.linkedin.com/in/royyandzakiy/

If you enjoy thinking about firmware architecture, trade-offs, and how things actually behave on hardware, we will likely have things to talk about.
