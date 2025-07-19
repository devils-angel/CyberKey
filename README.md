# Cyber Ally — Accessible Anti-Cyberbullying Keyboard 🔐🧠

Developed during **Smart India Hackathon (SIH) 2020**, **Cyber Ally** is a custom Android keyboard designed to **detect and prevent cyberbullying** at the source — while typing. The project won the **national-level hackathon**, solving a real-world problem statement for the Indian government.

## 🌟 Key Features

- ✋ **Real-Time Cyberbullying Detection**: NLP-based detection of toxic, aggressive, or harmful language as the user types.
- ⚠️ **Instant Alerts**: Warns users and offers the chance to rephrase or delete potentially harmful content before it is sent.
- 🌐 **Multi-language Support**: Capable of handling input in multiple Indian languages.
- 🔤 **Full Android Keyboard Functionality**: Developed on top of the open-source **AnySoftKeyboard**, with seamless typing and UI responsiveness.

## 🧩 How It Works

1. Users type within any app using the Cyber Ally keyboard.
2. Input is passed through a lightweight NLP model.
3. If toxicity is detected:
   - The user is alerted.
   - Suggested edits or rewordings are offered.
4. Encourages behavior change and self-moderation.

## 🧪 Tech Stack

- **Java** / **Android SDK** — Keyboard base and app integration.
- **NLP (Natural Language Processing)** — For toxicity detection (via pretrained models / text classifiers).
- **AnySoftKeyboard** — Open-source Android keyboard forked and extended.
- **SQLite** — Optional local storage for custom input history or analysis.

## 🎯 Problem Statement

> **Ministry of Education, Government of India**  
> "Design a smart solution to reduce or prevent cyberbullying on social media and messaging platforms."

## 🧠 My Role

As part of the **winning team**, I focused on:

- 💡 **Designing the integration between the NLP pipeline and keyboard UI.**
- 🧪 **Testing and debugging input-to-alert logic.**
- 📲 **Adapting AnySoftKeyboard's architecture for real-time NLP feedback.**
- 🧩 **Collaborating on UI/UX for minimal user interruption during alerts.**

## 🏆 Achievements

- 🥇 **Winners of Smart India Hackathon 2020** (Software Edition)
- Recognized for creating a **practical, scalable tool to promote safer digital communication**.


## 🔧 Installation

### Prerequisites

- Android Studio
- Android Device / Emulator (API 21+ recommended)

### Build & Run

1. Clone the repository:
   ```bash
   git clone https://github.com/devils-angel/SIH_Keyboard2.git
