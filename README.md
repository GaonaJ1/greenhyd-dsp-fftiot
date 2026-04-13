# Green Hydrogen Digital Twin Simulator

## Overview

This project is an advanced **real-time digital twin** of a green hydrogen production plant. It integrates renewable energy systems, electrolysis, IoT monitoring, and signal processing into a single interactive simulation.

The platform combines **engineering, data science, and visualization** to model how hydrogen is produced, processed, and analyzed in a modern energy system.

---

## Key Features

* **Renewable Energy Simulation** (Solar + Wind)
* **PEM Electrolyzer Model** for hydrogen production
* **Hydrogen Storage System** with capacity tracking
* **IoT Sensor Monitoring** (temperature, light, system state)
* **DSP Signal Processing Pipeline** (AM modulation & recovery)
* **FFT Spectrum Analysis** with anomaly detection
* **3D Visualization (CesiumJS)** for full plant interaction
* **Real-time Charts & Oscilloscopes**

---

## System Architecture

The simulator integrates multiple subsystems:

1. **Energy Layer**

   * Solar and wind power generation
   * Dynamic load balancing

2. **Hydrogen Production Layer**

   * PEM electrolysis process
   * Efficiency degradation over time

3. **Storage Layer**

   * Hydrogen accumulation and tank capacity limits

4. **IoT Layer**

   * Sensor data generation
   * State classification and alerts

5. **Signal Processing Layer**

   * AM modulation and demodulation
   * Noise simulation and filtering
   * FFT-based anomaly detection

6. **Visualization Layer**

   * 3D digital twin (CesiumJS)
   * Real-time dashboards and charts

---

## Project Structure

```
.
├── green-h2-digital-twin.html   # Main simulator (frontend + logic)
├── assets/                      # Optional assets (images, styles)
├── README.md                    # Project documentation
```

---

## How to Run

1. Download or clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
```

2. Open the project folder

3. Run the simulator:

* Open `green-h2-digital-twin.html` in your browser

> ⚠️ No installation required — runs entirely in the browser

---

## Technologies Used

* **JavaScript (Vanilla)**
* **CesiumJS** (3D visualization)
* **HTML5 Canvas** (charts & signal rendering)
* **Digital Signal Processing (DSP)** concepts
* **Fast Fourier Transform (FFT)** algorithms

---

## Simulation Capabilities

* Real-time hydrogen production (kg/h)
* System efficiency tracking
* Renewable power fluctuation modeling
* Sensor-driven alerts
* Signal noise and filtering analysis
* Frequency-domain anomaly detection

---

## Use Cases

* Energy systems simulation
* Hydrogen production research
* Educational tool (engineering / physics / DSP)
* Digital twin prototyping
* Signal processing visualization

---

## Future Improvements

* Backend integration (Python / API)
* Machine learning for anomaly detection
* Multi-plant scaling
* Real-world data integration
* Control system optimization

---

## Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## License

This project is open-source and available under the MIT License.

---

## Author

Developed as an advanced simulation project combining:

* Renewable energy systems
* Hydrogen technology
* Signal processing
* Interactive visualization

---

## Support

If you like this project:

* Give it a ⭐ on GitHub
* Share it with others

---

**"Where energy meets intelligence — a living digital twin."**
