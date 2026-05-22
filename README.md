![header](https://github.com/royyandzakiy/royyandzakiy/blob/master/docs/header.png)

# Royyan Dzakiy

**Embedded Software Engineer — Firmware, Systems, and Tooling**

C • Modern C++ (17/23) • Zephyr RTOS • ESP-IDF • Embedded Linux (learning)

Netherlands · [LinkedIn](https://www.linkedin.com/in/royyandzakiy/)

---

I build embedded systems that behave predictably in the real world—from bare-metal firmware to desktop tooling that supports it. Currently at **LMesh IoT**, working on medical and industrial devices with Zephyr, FreeRTOS, and BLE/Wi-Fi stacks.

My work sits at the intersection of **deterministic firmware**, **modern C++ architecture**, and **developer infrastructure** (build systems, CI/CD, testing). I care about code that outlasts its author.

---

## What I bring

- **Firmware at the metal.** RTOS-based systems (Zephyr, FreeRTOS, ESP-IDF) on Nordic, Espressif, and STM32. High-throughput sensor pipelines, BLE/Wi-Fi connectivity, low-power design.
- **Architecture that scales.** Event-driven, state-machine-based designs. Legacy refactoring toward modular, testable structures. Explicit over clever.
- **Tooling as first-class.** Reproducible builds (CMake + Docker + CI), automated hardware-in-the-loop testing, static analysis, and developer documentation.
- **Systems thinking.** I don't just write firmware. I design the desktop SDKs, test rigs, and diagnostics tooling that support the device in production.

---

## Selected projects

These repositories reflect how I think and work. Most are explorations of architecture, language patterns, or tooling—some power real production systems.

### Embedded Systems & RTOS

| Repository | What it shows |
|------------|---------------|
| [**balancer-robot-workspace-manifest**](https://github.com/royyandzakiy/balancer-robot-workspace-manifest) | Professional Zephyr workspace orchestration using `west`. Multi-repo firmware + desktop app + docs, pinned and reproducible. This is how I structure real projects. |
| [**multisensor-station**](https://github.com/royyandzakiy/multisensor-station) | Modular multi-sensor firmware. Clean separation of sensor drivers, data pipelines, and application logic. |
| [**zephyr-modern-cpp**](https://github.com/royyandzakiy/zephyr-modern-cpp) | Modern C++ on constrained targets: concepts, `std::variant`-based state machines, and compile-time abstractions tested on Zephyr and ESP-IDF. |
| [**esp-freertos-tutorial**](https://github.com/royyandzakiy/esp-freertos-tutorial) | FreeRTOS patterns on ESP32 with emphasis on task structure and concurrency clarity. |

### Tooling, Build Systems & Testing

| Repository | What it shows |
|------------|---------------|
| [**cpp-project-template**](https://github.com/royyandzakiy/cpp-project-template) | Production-grade C++ project scaffold: CMake presets, vcpkg, clang-tidy, sanitizers (ASan/UBSan), Tracy profiler, GitHub Actions CI. The same infrastructure I use for host-side device libraries. |
| [**gmock-sfinae-concepts-calculator**](https://github.com/royyandzakiy/gmock-sfinae-concepts-calculator) | Unit testing with advanced C++ patterns: SFINAE-based mocking, C++20 concepts, and type traits to isolate hardware dependencies. |
| [**windows-lib-cpp-template**](https://github.com/royyandzakiy/windows-lib-cpp-template) | Native Windows C++ library template with structured CMake, CI, and WinRT integration. Used internally for BLE device communication SDKs. |

### Full-Stack C++ (Desktop, Web, UI)

| Repository | What it shows |
|------------|---------------|
| [**drogon-todo-project**](https://github.com/royyandzakiy/drogon-todo-project) | C++23 REST API with JWT auth, SQLite, and clean architecture (Controllers → Services → Repositories). Demonstrates non-blocking coroutines, structured error handling, and multi-platform build presets. |
| [**qt-qml-project**](https://github.com/royyandzakiy/qt-qml-project) | Qt 6 / QML desktop app with MVVM architecture. Login, SQLite CRUD, CSV export, serial port enumeration. Built as a reusable template with full architecture documentation. |

---

## How I think about software

> Code should be structured so the next engineer can continue without a séance.

- Explicit state machines and data flow over clever control logic
- Modular, event-driven designs that scale across teams and time
- Build reproducibility and automated verification are not optional
- Production constraints belong in the design phase, not as post-mortems
- Documentation, architecture decisions, and developer tooling are engineering output—not overhead

I enjoy pushing what's possible with C++ on small systems while measuring every abstraction against real hardware constraints.

---

## Currently learning

**Embedded Linux** — building Yocto images, writing kernel modules, and understanding the user-space/kernel boundary. I'm bridging a career of bare-metal and RTOS firmware toward Linux-based embedded systems.
