![header](https://github.com/royyandzakiy/royyandzakiy/blob/master/docs/header.png)

# Royyan Dzakiy

Embedded software engineer. C, modern C++ (17/23), Zephyr RTOS, ESP-IDF.

I work close to the hardware, currently at LMesh IoT on medical and industrial devices, mostly Nordic and Espressif silicon with Zephyr and FreeRTOS. Before that I led firmware and AIoT engineering at eFishery, managing up to 30 engineers. B.S. Informatics, Institut Teknologi Bandung.

Most of my work sits in two areas: making firmware testable before the hardware is available, and building toolchains and project structures that other engineers can pick up and run. I am currently extending that into embedded Linux, working with Yocto and the kernel to user-space boundary.

---

## Selected work

- [**zephyr-testing-workshop**](https://github.com/royyandzakiy/zephyr-testing-workshop) - the repo behind my Packt live workshop on automated testing in Zephyr. `native_sim`, `ztest`, Twister driving pytest, and CI running on a self-hosted runner.
- [**zephyr-devcontainer**](https://github.com/royyandzakiy/zephyr-devcontainer) - a Dockerized Zephyr toolchain, so a new machine can build the tree without a day of setup first.
- [**zephyr-ztest-gpio-emul**](https://github.com/royyandzakiy/zephyr-ztest-gpio-emul) - testing application logic against emulated GPIO on nRF Connect SDK, with hall sensors and buttons faked in CI.
- [**cpp-project-template**](https://github.com/royyandzakiy/cpp-project-template) - the scaffold I start host-side C++ tools from. CMake presets, vcpkg or Conan behind a toggle, clang-tidy, sanitizers, GitHub Actions.
- [**fc-simulation**](https://github.com/royyandzakiy/fc-simulation) - a minimal quadcopter flight controller in C++23, with a Python simulator to fly it against before any hardware exists. Being moved onto Zephyr.
- [**LoRa-RHMesh**](https://github.com/royyandzakiy/LoRa-RHMesh) - LoRa mesh routing experiments, and the most forked repo here.

The rest of this account is mostly single-purpose experiments, archived once they have served their purpose.

---

## Teaching and writing

I wrote and run the Packt live workshop *Practical Embedded Automated Testing for Zephyr*, and was technical reviewer for *Developing IoT Projects with ESP32, 2nd Edition*. I also speak at community events. More at [royyandzakiy.github.io](https://royyandzakiy.github.io).

---

[LinkedIn](https://www.linkedin.com/in/royyandzakiy/) · [royyandzakiy.github.io](https://royyandzakiy.github.io)
