<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=FF6EB4&height=120&section=header&text=Krinal%20Parmar&fontSize=36&fontColor=fff&fontAlignY=40&desc=Electronics%20%26%20Communication%20%E2%86%92%20Embedded%20Systems&descSize=14&descAlignY=65&descColor=FFD6EC" width="100%"/>
</div>

<br>

```zsh
~/krinal-parmar — zsh
$ whoami
  Krinal Parmar  // EC Grad → Embedded Systems Engineer

$ cat about.txt
  role:      Embedded Engineer (ESP32-S3 · ESP-IDF)
  target:    CPU Arch · SoC Validation · Hardware Systems
  companies: AMD · ARM · Qualcomm · NVIDIA · NXP · Google · Cisco
  location:  Ahmedabad, India 🇮🇳
  passion:   "where hardware meets firmware"

$ ./start.sh  █
```

<br>

---

## 🩷 `skills.json`

<table>
<tr>
<td valign="top" width="50%">

**⚙️ Firmware Architecture**

![ESP32-S3](https://img.shields.io/badge/ESP32--S3-FF3D9A?style=flat-square&logo=espressif&logoColor=white)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-FF6EB4?style=flat-square&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-FF3D9A?style=flat-square)
![State Machines](https://img.shields.io/badge/State_Machines-FF6EB4?style=flat-square)
![Plugin Architecture](https://img.shields.io/badge/Plugin_Architecture-FF3D9A?style=flat-square)
![Tasks & Queues](https://img.shields.io/badge/Tasks_%26_Queues-FF6EB4?style=flat-square)
![Event Groups](https://img.shields.io/badge/Event_Groups-FF3D9A?style=flat-square)

</td>
<td valign="top" width="50%">

**⚡ Protocols — Register Level**

![SPI](https://img.shields.io/badge/SPI_(register_level)-FF3D9A?style=flat-square)
![I2C](https://img.shields.io/badge/I²C_(register_level)-FF6EB4?style=flat-square)
![UART](https://img.shields.io/badge/UART_(custom_framing)-FF3D9A?style=flat-square)
![Modbus RTU](https://img.shields.io/badge/Modbus_RTU-FF6EB4?style=flat-square)
![Sensor Fusion](https://img.shields.io/badge/Sensor_Fusion_%26_Calibration-FF3D9A?style=flat-square)

</td>
</tr>
<tr>
<td valign="top">

**🌐 Connectivity**

![MQTT](https://img.shields.io/badge/MQTT_(QoS,_TLS)-FF3D9A?style=flat-square&logo=mqtt&logoColor=white)
![HTTP](https://img.shields.io/badge/HTTP_(GET,_POST,_TLS)-FF6EB4?style=flat-square)
![WebSockets](https://img.shields.io/badge/WebSockets-FF3D9A?style=flat-square)
![BLE](https://img.shields.io/badge/BLE_(GATT,_custom)-FF6EB4?style=flat-square&logo=bluetooth&logoColor=white)
![BLUFi](https://img.shields.io/badge/BLUFi_Provisioning-FF3D9A?style=flat-square)
![WiFi](https://img.shields.io/badge/WiFi_STA_/_AP-FF6EB4?style=flat-square)
![GSM](https://img.shields.io/badge/GSM_/_Cellular-FF3D9A?style=flat-square)

</td>
<td valign="top">

**🏗️ Computer Architecture**

![Cache](https://img.shields.io/badge/Cache_Hierarchy_(L1/L2/L3)-FF3D9A?style=flat-square)
![TLB](https://img.shields.io/badge/TLB_%26_Address_Translation-FF6EB4?style=flat-square)
![Virtual Memory](https://img.shields.io/badge/Virtual_Memory_%26_Paging-FF3D9A?style=flat-square)
![Pipeline](https://img.shields.io/badge/CPU_Pipeline_Stages-FF6EB4?style=flat-square)
![Branch Prediction](https://img.shields.io/badge/Branch_Prediction-FF3D9A?style=flat-square)
![MMIO](https://img.shields.io/badge/Memory--Mapped_I/O-FF6EB4?style=flat-square)

</td>
</tr>
</table>

**🔧 Languages**&nbsp;&nbsp;
![C](https://img.shields.io/badge/C-FF3D9A?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-FF6EB4?style=flat-square&logo=cplusplus&logoColor=white)

---

## 🩷 `projects/`

<details>
<summary><b>Hazosense</b> &nbsp;—&nbsp; ESP32-S3 · Industrial IoT Vibration Monitor &nbsp; <img src="https://img.shields.io/badge/active-FF6EB4?style=flat-square"/></summary>
<br>

> `ESP32-S3` `ADXL355B` `SPI` `FreeRTOS` `MQTT` `Grafana` `Loki` `Custom PCB`

A precision industrial vibration sensing platform built from scratch.

- **Hardware** — Custom PCB with 3× ADXL355B accelerometers (one per axis) for independent per-axis vibration capture
- **Firmware** — Register-level SPI drivers, 20-bit raw ADC assembly, full calibration pipeline (sign extension → scale factor → zero-offset subtraction)
- **Architecture** — Dual-channel HTTP/MQTT config sync, cloud authority pattern, HMAC-SHA256 payload signing, ETag-based bandwidth efficiency
- **Observability** — Grafana dashboards fed via Loki with custom LogQL unwrap queries for real-time accelerometer telemetry

</details>

<details>
<summary><b>CPU Architecture Deep-Dive</b> &nbsp;—&nbsp; Targeting AMD · ARM · Qualcomm · NVIDIA &nbsp; <img src="https://img.shields.io/badge/ongoing-7AABF0?style=flat-square"/></summary>
<br>

> `Cache` `TLB` `Virtual Memory` `Paging` `Pipeline` `Branch Prediction` `MMIO`

- Full memory hierarchy: registers → L1/L2/L3 → DRAM
- Cache mapping strategies: direct-mapped, set-associative, fully associative
- TLB operation and virtual-to-physical address translation pipelines
- Page replacement policies: LRU, FIFO, Clock algorithm
- CPU pipeline stages, hazards, branch prediction strategies
- Memory-mapped I/O and peripheral addressing

</details>

<details>
<summary><b>Custom Accelerometer Array PCB</b> &nbsp;—&nbsp; 3× ADXL355B · SPI · Precision Measurement &nbsp; <img src="https://img.shields.io/badge/shipped-555?style=flat-square"/></summary>
<br>

> `PCB Design` `ADXL355B` `SPI` `Sensor Fusion` `Calibration`

- Designed and fabricated custom board with three ADXL355B sensors for per-axis vibration capture
- Wrote complete SPI register-map drivers from scratch — no HAL abstraction
- Implemented 20-bit two's complement decoding with proper sign extension
- Built full calibration pipeline from raw ADC counts → physical acceleration in g
- Applied sensor fusion across three independent axes

</details>

---

## 🩷 `expertise.md`

```
Embedded Firmware (ESP-IDF)        ████████████████████  95%
Hardware Protocol Design           ██████████████████░░  88%
IoT Connectivity (MQTT / HTTP)     ████████████████░░░░  80%
FreeRTOS / RTOS Architecture       █████████████████░░░  85%
CPU Architecture / Memory Systems  ███████████████░░░░░  75%
PCB Design & Sensor Integration    ██████████████░░░░░░  72%
```

**Currently targeting:**

![CPU Architecture](https://img.shields.io/badge/CPU_Architecture-FF6EB4?style=flat-square)
![SoC Validation](https://img.shields.io/badge/SoC_Validation-FF3D9A?style=flat-square)
![Hardware Systems](https://img.shields.io/badge/Hardware_Systems-FF6EB4?style=flat-square)
&nbsp;
![AMD](https://img.shields.io/badge/AMD-7AABF0?style=flat-square)
![ARM](https://img.shields.io/badge/ARM-7AABF0?style=flat-square)
![Qualcomm](https://img.shields.io/badge/Qualcomm-7AABF0?style=flat-square)
![NVIDIA](https://img.shields.io/badge/NVIDIA-7AABF0?style=flat-square)
![NXP](https://img.shields.io/badge/NXP-7AABF0?style=flat-square)
![Google](https://img.shields.io/badge/Google-7AABF0?style=flat-square)
![Cisco](https://img.shields.io/badge/Cisco-7AABF0?style=flat-square)

> Not looking for software-primary roles. Looking for teams where **hardware understanding** is the core of the job.

---

## 🩷 `ping me`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-FF6EB4?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/krinal-parmar-75a069249/)
[![Email](https://img.shields.io/badge/Send_a_Mail-FF3D9A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:krinal.nileshparmar@gmail.com)

<br>

```
┌─────────────────────────────────────────┐
│   "The best firmware is the kind that   │
│    makes the hardware invisible."       │
└─────────────────────────────────────────┘
```

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=krinal-parmar.krinal-parmar&color=FF6EB4)

<img src="https://capsule-render.vercel.app/api?type=waving&color=FF6EB4&height=80&section=footer" width="100%"/>

</div>
