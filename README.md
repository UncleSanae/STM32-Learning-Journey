<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/STM32_Logo.svg/2560px-STM32_Logo.svg.png" width="300px">
  
  # STM32-Learning Journey
  
  ![STM32](https://img.shields.io/badge/Hardware-STM32F103C8T6-blue?style=for-the-badge&logo=stmicroelectronics)
  ![Language](https://img.shields.io/badge/Language-C%2FEmbedded_C-orange?style=for-the-badge)
  ![IDE](https://img.shields.io/badge/IDE-Keil_MDK_5-green?style=for-the-badge)
  ![Status](https://img.shields.io/badge/Status-In_Progress-yellow?style=for-the-badge)

  <p> ⚡ 记录我从零开始学习 STM32 嵌入式开发的完整历程 / My STM32 learning roadmap </p>
</div>

---

## 📖 简介 | Introduction

这里存放了我学习 STM32 过程中的所有练习代码、笔记和实验工程。
项目从基础的点灯（GPIO）开始，涵盖中断、定时器、通信协议（UART/I2C/SPI）以及 RTOS 实战。

> **Note:** 所有的代码都基于 STM32 HAL 库 (或标准库，按你实际写)。

## 🛠️ 开发环境 | Tech Stack

* **MCU**: STM32F103C8T6 (Blue Pill) / STM32F407ZGT6
* **IDE**: Keil uVision 5.38
* **Debugger**: ST-Link V2 / J-Link
* **Software**: STM32CubeMX, Serial Assistant (XCOM)

## 📂 目录结构 | Repository Structure

```text
STM32-Learning/
├── 01-GPIO/              # 基础 IO 操作 (LED, Buzzer)
│   ├── 01-LED_Blink/     # 点灯实验
│   └── 02-Key_Input/     # 按键输入
├── 02-UART/              # 串口通信实验
├── 03-Timers/            # 定时器与 PWM
├── 04-ADC_DAC/           # 模数转换
├── Docs/                 # 学习笔记与原理图
└── README.md             # 你现在看到的这个文件
