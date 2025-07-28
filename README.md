# AuraLink

### Inclusive AI Conversations for the Visually and Hearing Impaired 

AuraLink is an AI-powered conversational platform purposefully designed to empower **visually impaired**, **deaf**, **hard-of-hearing**, and **mute** individuals. While conventional AI tools cater to the general population, AuraLink focuses on making **accessible, intuitive, and human-like interactions possible for everyone**, regardless of communication ability.

AuraLink consists of two integrated systems:

* **SignGPT** – A sign-language-first conversational AI assistant for deaf and mute users
* **VoiceGPT** – A voice-first conversational AI assistant for visually impaired and blind users  

---

## Overview

Current AI assistants heavily rely on text or voice interfaces, excluding millions of users who face sensory disabilities. AuraLink aims to bridge this gap through:

* **Real-time sign language communication with AI avatars**
* **Voice-based AI interaction for screen-free accessibility**
* **Adaptive feedback formats (text, sign, audio) based on user preference or accessibility need**

---

## 1. SignGPT – AI for Deaf and Mute Users

SignGPT enables users to **communicate with the AI using sign language**, and the AI responds back in sign via animated 3D avatars. It eliminates the need for voice or text and provides a seamless interaction model using non-verbal communication.

### Features

* Sign-to-Sign AI communication using webcam-based gesture recognition
* Real-time sign language understanding and generation
* AI avatar delivers responses in sign language
* Optionally receive responses in text or audio
* AI avatar customization (appearance, expression, personality)
* Personality-driven interaction styles (formal, casual, humorous)
* Themed character avatars inspired by fictional universes (ex: superhero archetypes)

---

## 2. VoiceGPT – AI for Visually Impaired Users

VoiceGPT allows blind or visually impaired users to **interact hands-free** with the AI using only their voice. Responses are provided in natural spoken language, eliminating the need for screens or reading.

### Features

* Voice-first, screen-free interaction model
* Wake-word enabled voice activation and offline mode
* AI responds with natural speech synthesis
* Adjustable voice tone, pace, and interaction level
* Background-aware: can describe surroundings if integrated with camera
* Optional memory mode for recurring user needs (medication, navigation, etc.)

---

## Unified Accessibility System

AuraLink is designed with a **modular yet unified architecture**:

| Component           | SignGPT                         | VoiceGPT                       |
| ------------------- | ------------------------------- | ------------------------------ |
| Input Method        | Webcam (Sign Language)          | Microphone (Voice)             |
| Output Method       | 3D Sign Avatar / Text / Audio   | Audio                          |
| Target Users        | Deaf, Mute, Hard-of-Hearing     | Blind, Visually Impaired       |
| Optional Formats    | Text, Audio fallback            | N/A (Always Voice-first)       |
| Personality Options | Custom avatars + tone selection | Custom voice tone and behavior |

---

## Future Integration – AuraLink Meet

AuraLink will expand into a **real-time, sign-enabled video conferencing system** for accessibility-first virtual meetings between hearing and deaf users.

Planned features include:

* Real-time sign recognition in video calls
* Speech-to-sign and sign-to-text translation
* Accessible video UI with subtitle overlays and gesture space zoom
* AI-mediated communication between deaf and hearing users

---

## Tech Stack

| Layer              | Technology                                |
| ------------------ | ----------------------------------------- |
| Frontend           | React.js, TailwindCSS                     |
| Backend            | Node.js / FastAPI                         |
| Video Layer        | WebRTC (100ms / Daily.co / Twilio)        |
| Sign Detection     | MediaPipe, OpenPose, TensorFlow           |
| Speech Recognition | OpenAI Whisper, Google Speech-to-Text API |
| Speech Synthesis   | ElevenLabs, Google TTS                    |
| Avatar Rendering   | Three.js or Unity WebGL (for SignGPT)     |

---

## Installation

```bash
git clone https://github.com/Asvix-04/Auralink.git
cd Auralink
npm install
npm run dev
```

---

## Contributing

Auralink is actively seeking developers, designers, researchers, and accessibility advocates to join the mission. If you're passionate about creating accessible AI for all, we welcome your contributions.

* Submit a pull request with your proposed additions
* Reach out with ideas, research, or feedback at: **[agvskanda@gmail.com](mailto:agvskanda@gmail.com)**

---

## License

This project is open-source under the [MIT License](LICENSE).

---

**AuraLink is not just another AI platform. It's a reimagination of AI — for those who’ve been left out.**
Join us in building technology that truly includes everyone.

