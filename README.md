<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=2563EB&center=true&vCenter=true&width=600&lines=Sonliy+%7C+Embedded+Software+Engineer;Architecture+%C2%B7+Low-Level+%C2%B7+RTOS" alt="Typing SVG" />

</div>

<p align="center">
  <b>嵌入式软件工程师</b> · 3年量产经验 · 4款产品 · 裸机/RTOS/Linux全覆盖
</p>

<p align="center">
  <a href="https://github.com/Sonliy/rtthread-app-framework">
    <img src="https://img.shields.io/badge/开源框架-rtthread--app--framework-2563EB?style=flat-square&logo=github" />
  </a>
  <img src="https://img.shields.io/badge/C-主力语言-2563EB?style=flat-square&logo=c" />
  <img src="https://img.shields.io/badge/MCU-STM32H7/GD32F4-2563EB?style=flat-square&logo=stmicroelectronics" />
  <img src="https://img.shields.io/badge/RT--Thread-自研框架-2563EB?style=flat-square" />
  <img src="https://img.shields.io/badge/AI on MCU-加分项-2563EB?style=flat-square&logo=tensorflow" />
</p>

---

### 关于我

一名嵌入式软件工程师，目前在新能源行业做产品研发。核心方向是**嵌入式软件架构设计** —— 从裸机 Super-Loop 到 RTOS 应用框架，从 OOP in C 到 FSM/HSM 状态机，追求高内聚低耦合、可复用、可验证的嵌入式软件。

自主设计并开源了一套 [RT-Thread 应用框架](https://github.com/Sonliy/rtthread-app-framework)，借鉴 QP/C Active Object 思想，用 OOP in C 落地了 dispatch/transition/state_handler 三层分离架构。AI on MCU（TF→Cube.AI→CMSIS-NN）是其中一个实践方向，但架构设计和底层系统才是主线。

---

### 技能矩阵

| 维度 | 等级 | 核心能力 |
|------|:--:|------|
| **C 语言** | ★★★★★★★ | 裸机/RTOS 生产级，函数指针/虚表/OOP in C/ |
| **架构设计** | ★★★★★★★★ | task_module_t 框架 300 行落地，三层分离，SOLID in C |
| **ARM/STM32** | ★★★★★★★ | H7/M4 深入（UART/ADC/DMA/SPI/Linker），Keil→GCC 移植 |
| **RTOS/系统** | ★★★★★★★ | RT-Thread 源码级，FreeRTOS，QP/C HSM |
| **调试能力** | ★★★★★★★ | 寄存器级调试，HardFault 定位，栈回溯 |
| **网络协议** | ★★★★★★☆ | Modbus/MQTT/LwIP/Goose |
| **AI on MCU** | ★★★★★★☆ | TF→Cube.AI→CMSIS-DSP，CNN 浮点推理 < 5ms |
| **Linux** | ★★★★★☆☆ | 内核裁剪/设备树/U-Boot/systemd |

---

### 代表项目

#### RT-Thread 应用框架 — 开源

自研 task_module_t 框架 + msg_bus 消息总线 + FSM 状态机，借鉴 QP/C Active Object 思想

```
300 行核心  |  三层分离  |  零 malloc  |  OOP in C  |  SOLID
```

`RT-Thread` `OOP in C` `FSM/HSM` `SOLID` `GCC`

#### AFCI 电弧故障检测 — 光伏逆变器

CNN 模型在 STM32H7 上浮点推理，独立负责 MCU 嵌入式软件全链路

```
准确率 99.9%  |  漏报 0%  |  推理 < 1ms
```

`TensorFlow` `Cube.AI` `CMSIS-DSP` `DMA双缓冲` `OTA` `Modbus RTU`

#### 无线数据采集器 — 量产交付

GD32 + 4G 模组，MQTT 双向数据链路，数据上云+远程控制+固件升级

`GD32` `MQTT` `4G` `UART` `OTA`

#### BMS 电池管理系统总控

Cortex-A7 + Linux，系统定制/移植，Modbus + Qt/C++

`Linux` `Cortex-A7` `Modbus` `Qt/C++`

---

### 学术

- **EI 论文 × 1**（一作）：Transformer + CNN 混合模型 — 超声心动图左心室分割，精度 97.5%
- 控制科学与工程（模式识别）硕士

---

### 技术栈

<p align="center">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" />
  <img src="https://img.shields.io/badge/RT--Thread-00BFFF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FreeRTOS-8A2BE2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/CMSIS--DSP-2563EB?style=for-the-badge&logo=arm&logoColor=white" />
  <img src="https://img.shields.io/badge/GCC-A42E2B?style=for-the-badge&logo=gnu&logoColor=white" />
  <img src="https://img.shields.io/badge/GDB-000000?style=for-the-badge&logo=gnu&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Modbus-FF6600?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white" />
  <img src="https://img.shields.io/badge/LwIP-00AA00?style=for-the-badge" />
</p>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sonliy&show_icons=true&hide_title=true&count_private=true&hide=prs&theme=default" height="140" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sonliy&layout=compact&hide_title=true&langs_count=6&theme=default" height="140" />
</p>

<p align="center">
  <sub>软件架构驱动硬件价值</sub>
</p>
