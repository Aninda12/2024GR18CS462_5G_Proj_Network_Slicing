# 📶 5G Network Slicing Simulator

Welcome to the **5G Network Slicing Simulator** – a Python-powered simulation toolkit crafted to mimic and explore the behavior of network slicing in next-gen 5G infrastructure. This project allows researchers, students, and network enthusiasts to dive into how logical slices coexist and operate over a shared physical network, meeting diverse performance demands.

---

## 🧠 About the Project

**5G network slicing** is a game-changer in modern wireless communication, enabling operators to run multiple virtual networks – or *slices* – on top of a single physical infrastructure. Each slice is designed for a specific service type, balancing efficiency with tailored performance.

This simulator provides a playground to:

- Create and configure multiple network slices.
- Dynamically allocate system resources (bandwidth, compute power, etc.).
- Measure performance metrics like latency and throughput in real-time.



## ⚙️ Setup & Installation

### Requirements

- Python 3.8+
- Required packages listed in `requirements.txt`

### Installation Steps

1. Clone the repository:

    and then
    cd 5g-network-slicing-simulation
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the simulation with an input YAML file:

    ```bash
    python -m slicesim example-input.yml
    ```

---

## 🗂 Project Modules

Here’s what each core module does:

- `BaseStation.py` – Simulates 5G base station logic and client coordination.
- `Client.py` – Defines user behavior, demand, and interactions with slices.
- `Container.py` – Simulates applications deployed within slice environments.
- `Coverage.py` – Handles signal strength and spatial coverage logic.
- `Distributor.py` – Manages how system resources are split among slices.
- `Graph.py` – Visualizes simulation data and performance charts.
- `Slice.py` – Controls lifecycle and behavior of individual network slices.
- `Stats.py` – Gathers, logs, and analyzes key performance indicators.
- `utils.py` – Shared utility functions across the simulation.

---

## 🌍 Network Slice Types

This simulator supports different 5G slice categories, each representing a real-world use case:

- **eMBB** (Enhanced Mobile Broadband): High bandwidth for media-intensive apps like 4K streaming and VR.

- **mMTC** (Massive Machine Type Communications): Ideal for low-power IoT with dense connectivity.


Each slice can be independently configured and analyzed.

---

## 📊 Simulation Metrics

Track and evaluate slices using:

- **Latency** – End-to-end delay.
- **Throughput** – Data transmission success rate.
- **Utilization** – Efficiency of resource distribution among slices.

---

### Contributing Workflow

```bash
# Step 1: Fork the repo
# Step 2: Create a feature branch
git checkout -b feature/your-feature-name

# Step 3: Make changes and commit
git commit -m "Describe your changes"

# Step 4: Push and submit a PR
git push origin feature/your-feature-name


👥 Contributors
Aninda Paul

Ayush Kumar

Ritika

Ved Prakash Meena
