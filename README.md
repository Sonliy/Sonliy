<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=2563EB&center=true&vCenter=true&width=600&lines=Sonliy+%7C+Embedded+AI+Engineer;AI+on+MCU+%C2%B7+RT-Thread+%C2%B7+STM32;Build+AI+that+runs+on+silicon" alt="Typing SVG" />

</div>

<p align="center">
  <b>嵌入式AI工程师</b> · 3年量产经验 · 4款产品 · 裸机/RTOS/Linux 全覆盖
</p>

<p align="center">
  <a href="https://github.com/Sonliy/rtthread-app-framework">
    <img src="https://img.shields.io/badge/开源框架-rtthread--app--framework-2563EB?style=flat-square&logo=github" />
  </a>
  <img src="https://img.shields.io/badge/C-主力语言-2563EB?style=flat-square&logo=c" />
  <img src="https://img.shields.io/badge/STM32-H7/GD32-2563EB?style=flat-square&logo=stmicroelectronics" />
  <img src="https://img.shields.io/badge/RT--Thread-源码级-2563EB?style=flat-square" />
  <img src="https://img.shields.io/badge/AI_on_MCU-量产-2563EB?style=flat-square&logo=tensorflow" />
</p>

---

### 关于我

一名嵌入式 AI 工程师，目前在新能源行业做光伏逆变器新产品研发。核心方向是**把 AI 模型跑在单片机上** —— 从 TensorFlow 训练到 Cortex-M7 推理部署的全链路。

自主设计了一套 RT-Thread 应用框架 [rtthread-app-framework](https://github.com/Sonliy/rtthread-app-framework)，借鉴 QP/C Active Object 思想，用 OOP in C 落地了 dispatch/transition/state_handler 三层分离架构。

---

### 技能矩阵

| 维度 | 等级 | 核心能力 |
|------|:--:|------|
| **C 语言** | ★★★★★★☆ | 裸机/RTOS 生产级，函数指针/虚表/OOP in C |
| **ARM/STM32** | ★★★★★★★ | H7 深入（MPU/Cache/时钟树/Linker），Keil→GCC 移植 |
| **架构设计** | ★★★★★★★★ | task_module_t 框架 800 行落地，三层分离 |
| **RTOS/系统** | ★★★★★★★ | RT-Thread 源码级，FreeRTOS，QP/C HSM |
| **AI on MCU** | ★★★★★★★ | TF→Cube.AI→CMSIS-DSP，CNN 浮点推理 < 1ms |
| **调试能力** | ★★★★★★★ | GDB 三阶段排查，HardFault 定位，2000 行笔记 |
| **网络协议** | ★★★★★★☆ | Modbus/MQTT/LwIP/Goose/USB CDC |
| **Linux** | ★★★★★☆☆ | 内核裁剪/设备树/U-Boot/systemd |

---

### 代表项目

#### AFCI 电弧故障检测 — AI on STM32H7
330kW 光伏逆变器直流电弧实时检测，CNN 在 H7 上浮点推理

```
准确率 99.9%  |  漏报 0%  |  推理 < 1ms  |  误报 ≤ 3%
```

`TensorFlow` `Cube.AI` `CMSIS-DSP` `DMA双缓冲` `OTA` `Modbus RTU`

#### RT-Thread 应用框架 — 开源

自研 task_module_t 框架 + msg_bus 消息总线 + FSM 状态机

```
800 行核心  |  三层分离  |  零 malloc  |  OOP in C
```

`RT-Thread` `OOP in C` `FSM/HSM` `SOLID` `GCC`

#### 无线数据采集器 — 分布式光伏

GD32 + 4G 模组，MQTT 双向数据链路，数据上云+远程控制+固件升级

```
量产交付  |  MQTT 双向  |  固件升级
```

`GD32` `MQTT` `4G` `UART` `OTA`

#### BMS 电池管理系统总控

Cortex-A7 + Linux，系统定制/移植，Modbus + Qt/C++ 上位机

```
系统定制  |  设备树  |  RS485/CAN
```

`Linux` `Cortex-A7` `Modbus` `Qt/C++`

---

### 工程亮点

- **OTA 三分区防变砖** — bsdiff 增量 + LZMA 压缩 + Bootloader 写保护 + 自动回滚
- **Keil→GCC 全链路移植** — 链接脚本/启动文件/分散加载，自建 VSCode+EIDE+GCC 工具链
- **2000 行调试复盘笔记** — GDB 三阶段排查 + HardFault 定位 + 逻辑分析仪/示波器

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
  <sub>⚡ Build AI that runs on silicon ⚡</sub>
</p>
