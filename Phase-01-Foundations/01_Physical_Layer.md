# The Physical Layer (Layer 1)

The Physical Layer is the absolute foundation of the OSI model. It focuses on the hardware, the cables, and the method of moving raw **bits** from one place to another.

---

## 🏗️ Essential Vocabulary

### 1. Bit (Binary Digit)
* **Definition:** The smallest unit of data in computing. 
* **Value:** Either a `0` (off) or a `1` (on).
* **Speed:** Network speeds are measured in bits per second (**bps**).

### 2. Network Media
The physical "road" that data travels on.
* **Copper (Ethernet):** Uses electrical pulses. Most common in local networks (e.g., Cat6).
* **Fiber Optics:** Uses pulses of light. Extremely fast, travels long distances, and is immune to electrical interference.
* **Wireless (RF):** Uses radio waves to transmit data through the air.

### 3. NIC (Network Interface Card)
* **Definition:** The hardware chip or card that connects your device to the network.
* **Function:** It translates your computer's digital data into signals that the media (cables or waves) can carry.

---

## 🚦 Communication Modes (Duplex)

Understanding how "traffic" flows helps in troubleshooting slow networks.

| Mode | Description | Real-World Analogy |
| :--- | :--- | :--- |
| **Simplex** | Data flows in one direction only. | A Radio Station broadcast. |
| **Half-Duplex** | Data flows in both directions, but **one at a time**. | A Walkie-Talkie. |
| **Full-Duplex** | Data flows in both directions **simultaneously**. | A Cell Phone call. |

---

## 🗺️ Physical Topologies
This is the "map" of how your devices are physically plugged in.

* **Star Topology:** Every device connects to a central switch. If one cable breaks, the rest of the network stays online. (Most common today).
* **Mesh Topology:** Every device connects to every other device. Very expensive, but offers the highest reliability.
* **Bus Topology:** All devices share a single backbone cable. If the cable breaks, the entire network goes down.


---

## ⚡ Performance Concepts

* **Bandwidth:** The maximum capacity of the link (The size of the pipe).
* **Throughput:** The actual amount of data being moved (The flow of water).
* **Attenuation:** The loss of signal strength as it travels. This is why Ethernet cables are usually limited to **100 meters**.
* **EMI (Electromagnetic Interference):** "Noise" from power cables or fluorescent lights that can scramble electrical signals in copper wires.

---


[Back to Main Roadmap](../README.md)
