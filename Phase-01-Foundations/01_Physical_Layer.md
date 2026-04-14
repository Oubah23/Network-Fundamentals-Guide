# Phase 1: The Physical Layer (Layer 1)

This is where the "magic" of the internet meets the physical world. Layer 1 isn't about logic or software; it’s about moving raw electrical pulses, light, or radio waves across a distance. If Layer 1 is broken, nothing else matters.

---

## 🏗️ The Building Blocks

### 1. The "Bit"
Think of a **Bit** as the heartbeat of the network. It’s either a `1` (On) or a `0` (Off). 
* **Speed Check:** When your ISP says you have "100 Meg," they mean 100 million of these bits can travel through your wire every second (**100 Mbps**).

### 2. The Medium (The Road)
How are those bits traveling?
* **Copper (Ethernet):** The old reliable. Uses electricity. It's cheap, but it hates magnets and power cables (which cause "noise" or interference).
* **Fiber:** The "Speed Demon." Uses pulses of light. It's immune to electrical interference and can travel for miles without slowing down.
* **Wireless:** Using the air. Convenient, but easily blocked by walls or your neighbor's microwave.


---

## 🚦 How We Talk (Duplex)

In the real world, "how" we talk is as important as "what" we say.

* **Simplex:** One-way only. Like a TV broadcast. You listen, but you can't talk back.
* **Half-Duplex:** You can talk and listen, but **not at the same time**. Think of a Walkie-Talkie. If two people talk at once, the message is garbled (a **Collision**).
* **Full-Duplex:** The modern standard. Like a phone call. You can talk and listen simultaneously. This is why modern switches are so much faster than old hubs.


---

## 🗺️ Network Topologies (The Map)

How are the cables actually laid out in the building?

* **Star:** Everything plugs into one central switch. **Why it's the hero:** If one person's cable breaks, everyone else stays online. 
* **Mesh:** Everyone is connected to everyone. **Why it's the hero:** It’s almost impossible to take down, but it’s very expensive to wire.
* **Bus:** One long cable that everyone "taps" into. **The problem:** if that one cable breaks, the whole network dies instantly.




---

## ⚡ The "Hidden" Physics
These are the terms that help you troubleshoot when "the internet feels slow."

* **Attenuation:** Signal fade. Just like your voice gets quieter as you walk away, electrical signals get weaker. This is why Ethernet cables shouldn't be longer than **100 meters**.
* **Crosstalk:** When wires are too close together and their signals "bleed" into each other. We fix this by **twisting** the pairs of wires inside the cable.
* **EMI (Interference):** When a power cable or a large motor messes with your data. **Pro-Tip:** Never run your Ethernet cables directly on top of fluorescent lights or power lines!

---

## 🏁 Field Notes & Mastery Check
1. **The Hub vs. Switch Rule:** Hubs are Layer 1 (they just repeat signals). Switches are Layer 2 (they actually look at where data is going). Always use a switch.
2. **The "Light" Advantage:** If you have to connect two buildings, use Fiber. Copper can act like a giant lightning rod and fry your equipment if there's a strike nearby.

**Question for the reader:** If your computer says "Network Cable Unplugged" but the cable is clearly in, which Layer 1 components would you check first?

[Back to Main Roadmap](../README.md)
