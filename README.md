# Micromet Project

**Micromet** is an environmental sensing platform developed by **DotMote Labs** to monitor fine-scale microclimate and meteorological conditions in real time. Designed for research, agriculture, and environmental applications, Micromet combines wireless IoT sensors with cloud-based data services for scalable and actionable insight.

## 🌱 Project Overview

Micromet enables high-resolution tracking of:

- Air temperature and humidity
- Soil moisture and soil temperature
- Vapor pressure deficit (VPD)
- Solar radiation and light levels
- Rain gauge
- Wind speed and direction (optional)

All sensor data is transmitted wirelessly to a central gateway and then pushed to the DotMote cloud platform, where it can be accessed, visualized, or integrated into workflows.

---

## ⚙️ Features

- 🔧 Modular sensor architecture (plug-and-play support)
- 📶 Low-power LoRa or Wi-Fi connectivity
- 🔋 Solar-powered with backup battery
- ☁️ Native integration with SWEEP and TerraView™ dashboards
- 📈 Real-time API + CSV/JSON export for research workflows

---

## 📦 Repository Contents

| Folder/File         | Description                                       |
|---------------------|---------------------------------------------------|
| `/firmware/`        | Microcontroller code for Micromet sensor nodes    |
| `/gateway/`         | Gateway setup scripts and configuration           |
| `/cloud-api/`       | Python scripts and examples for data retrieval    |
| `/docs/`            | Technical specifications and deployment guides    |
| `/examples/`        | Sample applications and integrations              |

---

## 🚀 Getting Started

### Requirements

- Micromet Node (v1.2 or later)
- DotMote Gateway or compatible LoRa receiver
- Internet access for cloud sync (optional for local deployments)

### Setup Instructions

1. Flash firmware to your Micromet node using the `/firmware/` scripts.
2. Connect sensors according to the wiring diagrams in `/docs/`.
3. Power the node and ensure it connects to the gateway.
4. Use `/cloud-api/` scripts to pull or push data.
5. Optionally, integrate with your SWEEP workflow or TerraView dashboard.

---

## 📊 Visualization & Data Access

Micromet integrates directly with:
- **TerraView™**: for visual dashboards and alerts  
- **SWEEP**: for workflow-driven environmental automation  
- **Third-party APIs** via REST 

---

## 🛠️ Development

Want to contribute? See the [CONTRIBUTING.md](CONTRIBUTING.md) file or reach out to **support@dotmote.io**.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE), unless otherwise noted.

---

## 👥 Authors & Acknowledgments

**DotMote Labs**  
Lead: Aji John  
Collaborators: 

---

## 🔗 Contact & More Info

- 🌐 Website: [https://dotmotelabs.com](https://dotmotelabs.com)  
- 🛰️ Twitter/X: [@DotMoteLabs](https://twitter.com/DotMoteLabs)

---
