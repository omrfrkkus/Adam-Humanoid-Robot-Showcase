# 🤖 Adam Humanoid Robot: Embodied AI Showcase

<p align="center">
  <img src="assets/senin_en_havali_hareketli_gif_dosyan.gif" width="600" alt="Adam Robot Interaction Demo">
</p>

> **Note:** Due to the proprietary nature and commercial potential of this project, the core C++ and Python source codes are kept private. This repository serves as an architectural showcase.

## 📌 The Vision
The goal of the **Adam** project is to bridge the gap between advanced cloud-based Large Language Models (LLMs) and physical, physical hardware. It explores how AI can inhabit a physical body, perceive its environment, and react with ultra-low latency.

---

## 🧠 Cognitive Architecture (The "Brain")
Adam doesn't just parse text; it understands context and user traits.

* **LLM Integration:** Powered by a dynamic pipeline switching between **Google Gemini, Llama, and Ollama** depending on the task complexity.
* **Episodic Memory (RAG):** I engineered a localized Retrieval-Augmented Generation (RAG) system. Adam actually "remembers" past conversations, allowing for continuous and evolving interactions with users.
* **Multimodal Perception:** Real-time **Computer Vision** analyzes facial landmarks, while Voice Activity Detection (VAD) monitors audio cues, adapting the robot's "mood" dynamically.

<p align="center">
  <!-- Buraya RAG mimarisini veya kod terminalini gösteren küçük bir resim veya GIF koyabilirsin -->
  <img src="assets/senin_ai_veyaterminal_resmin.jpg" width="400" alt="AI Processing">
</p>

---

## ⚙️ Middleware & Synchronization (The "Nervous System")
The biggest challenge in Embodied AI is masking the cloud processing latency. When you speak to an AI, it takes seconds to process. A robot standing perfectly still for 3 seconds feels "dead".

* **Asynchronous Micro-movements:** I developed a multithreaded edge-computing architecture in **C++ and Python**. While the cloud AI is "thinking," the software generates autonomous idle movements (blinking, head tilting, breathing simulation). This creates the illusion of continuous, zero-latency awareness.

---

## 🔩 Hardware & Embedded Systems (The "Body")
Every part of Adam was built and assembled from scratch.

* **Mechanical:** Fully 3D-printed chassis housing over 20+ independent servo motors.
* **Communication:** Established an ultra-low latency UDP network between the processing unit and the microcontrollers.
* **Failsafes:** Programmed strict firmware limits in C++ to prevent physical collisions, overheating, and servo burnout during complex gestures.

<p align="center">
  <!-- Buraya kabloların, motorların veya 3D baskı parçalarının göründüğü teknik bir fotoğraf koy -->
  <img src="assets/senin_donanim_resmin.jpg" width="600" alt="Hardware Assembly">
</p>

---

### 📫 Let's Discuss Robotics & AI
I am actively looking for opportunities to bring this level of hardware-software integration to professional engineering teams. If you're interested in the deep technical details of Adam's architecture, feel free to reach out for an interview!
