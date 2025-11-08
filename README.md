# Hyphen Elemental Hardware Series

Hyphen Elemental is a family of rugged, open IoT hardware designed for **environmental sensing**, **resilient field deployments**, and **tight integration with the HyphenOS firmware + Hyphen Command Center ecosystem**.

Our goal is simple: **Never Fail. Always On. Field-ready.**  
Whether powering remote flood monitoring sites, rain gauges, water level sensors, or wildfire early-warning systems — Hyphen Elemental devices are engineered to *run indefinitely in the real world.*

## 🔋 Product Line Overview

| Model | Battery System | Nominal Output | Charging Source | Ideal Use Cases |
|------|----------------|----------------|-----------------|----------------|
| **Hyphen Elemental 4060XR** | 3× 18650 (3S) | ~12.6V max | Solar + Aux | High-power deployments, long endurance, satellite uplinks, multiple sensor payloads |
| **Hyphen Elemental 4050XR** | 2× 18650 (2S) | ~8.4V max | Solar + Aux | General environmental sensing, remote stations, water-level sensors |
| **Elemental4 Breakout Board** | N/A | 5V logic | Powered from your MCU / Solar board | Rapid prototyping, sensor integration, low-power analytics |

---

## 🌞 Hyphen Elemental 4060XR (12.6V, 3-Cell Solar Power System)

Designed for **long-term deployments** where reliability matters more than anything.

**Features**
- 3× 18650 series pack (**3S**) providing **up to 12.6V**
- High-efficiency MPPT-style solar charging
- Integrated protection circuitry (OVP / UVP / OCP / short-circuit)
- Designed to run **HyphenOS devices for years with minimal maintenance**
- Supports **multiple sensor rails** and external radios

**Recommended For**
- Remote flood early-warning nodes  
- Satellite uplinked sensor stations  
- Dual-radio communication setups  

---

## 🔦 Hyphen Elemental 4050XR (8.4V, 2-Cell Solar Power System)

A compact and efficient power system for **general IoT deployments**.

**Features**
- 2× 18650 series pack (**2S**) providing **up to 8.4V**
- Solar input protection and safe long-duration trickle
- Low-noise regulated output suitable for ESP32 / STM32 / AVR / HyphenOS boards
- Works with **HyphenConnect** for telemetry + OTA management

**Recommended For**
- Weather sensors  
- Water level sensors  
- Air/temp/humidity sensing nodes  

---

## 🧠 Elemental4 Breakout Board (Sensor + System Module)

The **Elemental4** is a supporting subsystem board designed to remove the “hard parts” from IoT deployments.

**On-Board Hardware**
- **Hardware watchdog** (ensures *never-hang* deployments)
- **Accelerometer** (for tamper detection or vibration triggers)
- **MicroSD card slot** for local datalogging / buffering during network downtime
- **Power-good / system supervisor circuits**
- 5V regulated rail with noise-filtered sensor supply lines

**Designed For**
- HyphenOS
- HyphenConnect devices
- ESP32-based sensor controllers

**In short:** *Plug sensors in. Deploy. Stay online. Always.*

---

## 🌍 Hyphen Ecosystem Integration

Hyphen Elemental hardware works seamlessly with:

| Component | Purpose | Repository |
|---------|---------|------------|
| **HyphenOS** | Embedded firmware for resilient sensing & control | https://github.com/similie/hyphen-os |
| **HyphenConnect** | Unified connection management + OTA + device identities | https://github.com/similie/hyphen-connect |
| **Hyphen Command Center** | Fleet management UI | https://github.com/similie/hyphen-command-center |
| **Hyphen Command Center API** | REST API + secure backend orchestration | https://github.com/similie/hyphen-command-center-api |

---

## 🛠️ Designed for Real-World Deployment

- Works in **full sun, monsoon, and long-cloud conditions**
- Resists brownouts, brown-ins, and voltage collapse events
- Watchdog ensures **hard auto-recovery**, even in firmware crashes
- Built for **field maintainability** and **low-touch sustainability**

---

## 📦 Manufacturing & Licensing

Hyphen Elemental hardware is **open to assemble** and designed to support local manufacturing ecosystems.  
BOM, schematics, and assembly notes will be released incrementally.

**License:** MIT (hardware & firmware are openly remixable)

---

## 🤝 Contributing

We welcome:
- Hardware improvements
- New regulated rail / sensor module designs
- PRs improving HyphenOS compatibility

Open an Issue or Discussion to begin.

---

## 💬 Questions? Partnerships? Field Deployment?

Similie specializes in climate resilience systems for real-world communities.

**Contact:** info@similie.org  
**Website:** https://similie.com