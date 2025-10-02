# 🤖 Pepper Guardian – AI-Powered Social Robot for Smart Spaces

**Pepper Guardian** is an ambitious project that combines **cognitive robotics**, **computer vision**, and **natural language understanding** to transform Pepper into an intelligent assistant for public spaces such as shopping malls.  

The system enables Pepper to see, understand, and interact with people in real-time, providing useful information and enhancing human-robot interaction.

---

## ✨ Features
 
- 🗣️ **Natural Language Dialogue** – users can ask Pepper questions like:  
  - “How many people are in the mall?”  
  - “Did you see a boy with a hat?”  
  - “Who crossed the line 1?”  
- 🤝 **Context-Aware Interaction** – Pepper answers with empathy and real-time awareness of the scene  

---

## 🧩 System Architecture

- **Dialogue Management** – speech-to-text, intent recognition, response generation  
- **ROS-based Integration** – modular nodes controlling Pepper’s sensors, actuators, and dialogue flow  
- **Knowledge Base** – real-time database updated from video analytics and used by the dialogue manager  

---

## 🚀 Getting Started

Clone the repo:
```bash
git clone https://github.com/your-username/pepper-guardian.git
cd pepper-guardian
Install dependencies:

bash
Copia codice
pip install -r requirements.txt
Run the system (simulation mode):

bash
Copia codice
roslaunch pepper_guardian demo.launch
