# stm32h7a3-nucleo-144-rs-lab

Personal lab monorepo containing Rust applications and crates for the STMicroelectronics
[STM32H7A3 Nucleo-144](https://www.st.com/en/evaluation-tools/nucleo-h7a3zi-q.html) development board,
featuring the 280 MHz [STM32H7A3xI/G](https://www.st.com/resource/en/datasheet/stm32h7a3zi.pdf)
family of Arm(R) Cortex(R)-M7 MCUs with double-precision FPU.

---

## `STM32H7A3ZI`

### General Description

_`STM32H7A3xI/G` devices are based on the high-performance Arm(R) Cortex(R)-M7 32-bit RISC core operating at
up to 280 MHz. The Cortex(R)-M7 core features a floating point unit (FPU) which supports Arm(R) double-precision
(IEEE 754 compliant) and single-precision data-processing instructions and data types. STM32H7A3xI/G devices
support a full set of DSP instructions and a memory protection unit (MPU) to enhance application security._

_`STM32H7A3xI/G` devices incorporate high-speed embedded memories with a dual-bank flash memory of up
to 2 Mbytes, around 1.4 Mbyte of RAM (including 192 Kbytes of TCM RAM, 1.18 Mbytes of user SRAM and
4 Kbytes of backup SRAM), as well as an extensive range of enhanced I/Os and peripherals connected to four
APB buses, three AHB buses, a 32-bit multi-AHB bus matrix and a multi layer AXI interconnect supporting internal
and external memory access._

_All the devices offer two ADCs, two DACs (one dual and one single DAC), two ultra-low power comparators, a
low-power RTC, 12 general-purpose 16-bit timers, two PWM timers for motor control, three low-power timers, a
true random number generator (RNG). The devices support nine digital filters for external sigma delta modulators
(DFSDM). They also feature standard and advanced communication interfaces._

### Reference Manual

* [RM0455 Reference manual](https://www.st.com/resource/en/reference_manual/rm0455-stm32h7a37b3-and-stm32h7b0-value-line-advanced-armbased-32bit-mcus-stmicroelectronics.pdf), includes:
  * `STM32H7A3/7B3`
  * `STM32H7B0`

---

## Getting Started

### Required Hardware

>The following instructions assume, for simplicity, the existence of an available USB Type-A port on the host device. Use of an adapter providing a USB Type-A port to USB-C connector should also work.

A **USB Micro-B to Type-A cable** is required for connection between the development board and the host device. The USB Micro-B connector plugs into the USB Micro-B port, flat side up, i.e., away from the PCB.

![USB Micro-B port](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/USB_Micro-B_receptacle.svg/150px-USB_Micro-B_receptacle.svg.png)

![USB Type-A connector](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/USB_Type-A_receptacle_Black.svg/150px-USB_Type-A_receptacle_Black.svg.png)

### Required Software

#### macOS

>TODO

#### Windows

>TODO

#### Linux

>TODO

---

## License

[MIT License](https://spdx.org/licenses/MIT.html)

---

`./README.md`
