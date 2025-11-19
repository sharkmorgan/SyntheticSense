<div align="center">
  <h1>SyntheticSense</h1>
  <img src="https://github.com/Jewelzufo/SyntheticSense1.1/blob/main/SyntheticSense.png?raw=true" height="500" width="500">
</div>

<div align="center">
  
  ![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)
  ![Status](https://img.shields.io/badge/status-research%20concept-orange)
  ![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen)
  
  **Open-Source Assistive Technology for the Deaf-Blind Community**

  
</div>

---

## 🌟 About

**SyntheticSense** is an open-source assistive technology project designed to provide deaf-blind individuals with integrated spatial awareness and communication capabilities. This project combines AI-powered computer vision with haptic feedback in a wearable system that anyone can build, modify, and improve.

### Why Open Source?

This project is **freely available** for everyone to use, study, modify, and distribute. We believe assistive technology should be:
- ✅ **Accessible** - No licensing fees or proprietary restrictions
- ✅ **Collaborative** - Built by and with the community it serves
- ✅ **Educational** - A learning platform for students and researchers
- ✅ **Adaptable** - Customizable for individual needs and preferences

**No patents. No restrictions. Pure innovation for social good.**

---

## 🎯 Core Functionality

The system provides two essential features in a unified, wearable platform:

### 1. Real-Time Obstacle Detection
- **Sony IMX500 AI camera** with embedded neural processing detects objects in real-time
- **Directional haptic feedback** alerts users to obstacles (left, center, right positioning)
- **Edge AI processing** ensures low-latency responses without cloud dependency
- **Privacy-first design** - all processing happens locally on device

### 2. Haptic Braille Communication
- **Grid of vibration motors** arranged to represent Braille characters
- **Wireless messaging** via MQTT/Wi-Fi for remote communication
- **NumPy-based encoding** converts text to haptic Braille sequences
- **Customizable patterns** - users can define their own tactile codes

---

## 🔧 Technical Architecture

**Hardware Components:**
- **Primary Computing**: Raspberry Pi Zero 2W (analyzes camera data, generates alerts)
- **Haptic Control**: Raspberry Pi Pico (drives vibration motor arrays with precise sequencing)
- **Vision Processing**: Sony IMX500 (provides on-sensor AI inference)
- **Communication**: MQTT/Wi-Fi (enables remote message transmission)
- **Power**: Modular, low-power design for extended battery operation

**Software Stack:**
- Python 3.x for main control logic
- NumPy for message encoding/storage
- OpenCV/IMX500 SDK for vision processing
- MicroPython for Pico firmware
- MQTT client for wireless communication

**Design Philosophy:**
- 🔋 Low-power edge computing
- 🔒 Privacy-preserving (no cloud required)
- 🧩 Modular architecture (easy to modify/extend)
- 💰 Affordable components (~$150-200 BOM)
- 📚 Well-documented for learning

---

## 💡 Innovation

SyntheticSense addresses a critical gap in assistive technology. While existing devices typically focus on either:
- **Navigation** (ultrasonic canes, guide systems), OR
- **Communication** (electronic Braille displays)

**This system integrates both** in a single wearable platform, enabling:
- Safer navigation with real-time obstacle alerts
- Tactile communication without external displays
- Independence through combined awareness and messaging
- Affordable, hackable design anyone can build

---

## 🚀 Applications

### Primary Use Cases
- **Assistive navigation** for deaf-blind individuals in daily environments
- **Emergency communication** systems for sensory impairments
- **Augmented spatial awareness** for rehabilitation and training

### Research & Education
- **Edge AI demonstrations** for computer science students
- **Haptic interface studies** in HCI research
- **Accessibility technology** curriculum development
- **Multi-modal feedback** system experiments

### Extended Applications
- Virtual reality accessibility interfaces
- Industrial safety alert systems
- Silent communication in specialized environments
- Prototype platform for custom assistive devices

---

## 🛠️ Getting Started

### Prerequisites
```bash
# Hardware (estimated cost: $150-200)
- Raspberry Pi Zero 2W
- Raspberry Pi Pico
- Sony IMX500 AI Camera
- Vibration motors (6-8x)
- Motor driver board
- Battery pack
- Miscellaneous wiring/components

# Software
- Python 3.8+
- NumPy
- OpenCV (or IMX500 SDK)
- MQTT client library
```

### Installation
```bash
# Clone the repository
git clone https://github.com/creativeacttech/SyntheticSense.git
cd SyntheticSense

# Install dependencies
pip install -r requirements.txt

# Follow setup guide in /docs
```

> **Note**: Detailed setup instructions, hardware assembly guides, and code documentation coming soon!

---

## 📊 Project Status

### Current Stage: 🔬 **Research Concept**

This project is in active development. Current status:

✅ **Completed:**
- System architecture design
- Component selection and testing
- Conceptual diagrams and documentation
- NumPy-based Braille encoding system

🚧 **In Progress:**
- Hardware integration testing
- Python control software
- Haptic feedback calibration
- User interface refinement

📋 **Planned:**
- Full code release (Q2 2026)
- Assembly instructions with photos
- Video demonstrations


---

## 🤝 Contributing

**We welcome contributions from everyone!** Whether you're:
- An accessibility advocate with user insights
- A hardware engineer with design improvements
- A software developer with code contributions
- A researcher with testing data
- Someone who wants to build and test the system

### How to Contribute

1. **Report Issues**: Found a bug or have a suggestion? [Open an issue](https://github.com/creativeacttech/SyntheticSense/issues)
2. **Improve Documentation**: Help make this more accessible to builders
3. **Code Contributions**: Submit pull requests with improvements
4. **Test & Provide Feedback**: Build the system and share your experience
5. **Spread the Word**: Share with accessibility communities and researchers

### Contribution Guidelines
- Check existing issues before creating new ones
- Document your changes clearly
- Test your contributions when possible
- Be respectful and inclusive

---

## 🎓 Educational Use

This project is ideal for:
- **University courses** in assistive technology, embedded systems, or AI
- **Hackathons** focused on accessibility or social good
- **Capstone projects** for engineering students
- **Research platforms** for haptic interface studies
- **Maker spaces** and accessibility workshops

**Educators**: Feel free to use and adapt this project for your curriculum. Contact us if you'd like educational support materials.

---

## 📚 Documentation

- **[Hardware Bill of Materials](docs/BOM.md)** - Component list with suppliers *(coming soon)*
- **[Assembly Guide](docs/ASSEMBLY.md)** - Step-by-step build instructions *(coming soon)*
- **[Software Setup](docs/SOFTWARE.md)** - Installation and configuration *(coming soon)*
- **[API Reference](docs/API.md)** - Code documentation *(coming soon)*


---

## 🌐 Community

### Connect With Us
- **Discussions**: [GitHub Discussions](https://github.com/creativeacttech/SyntheticSense/discussions)
- **Issues**: [Report bugs or request features](https://github.com/creativeacttech/SyntheticSense/issues)

### Acknowledgments
- Inspired by the deaf-blind community's resilience and feedback
- Built with open-source tools and libraries
- Special thanks to accessibility advocates

---

## 📖 Citation

If you use SyntheticSense in your research or project, please cite:

```bibtex
@software{syntheticsense2025,
  author = {Gonzalez, Julian Anival},
  title = {SyntheticSense: Open-Source Haptic Navigation and Communication System},
  year = {2025},
  url = {https://github.com/creativeacttech/SyntheticSense}
}
```

---

## 📜 License

This project is licensed under the **Apache License 2.0** - see the [LICENSE](LICENSE) file for details.

**What this means:**
- ✅ Free to use, modify, and distribute
- ✅ Commercial use allowed
- ✅ Patent grant included
- ✅ Changes must be documented
- ✅ Original attribution required

**No patents held or claimed on this design.** This is intentionally open for everyone to use and improve.

---

## 🔮 Roadmap

### Version 1.0 (Target: Q3 2026)
- [ ] Complete Python control software
- [ ] Hardware assembly guide with photos
- [ ] Basic haptic Braille library
- [ ] MQTT communication implementation
- [ ] Battery optimization

### Version 2.0 (Future)
- [ ] Machine learning-enhanced object detection
- [ ] Customizable haptic patterns
- [ ] Mobile app for remote messaging
- [ ] Multi-language Braille support

### Community Wishlist
- Voice-to-haptic conversion
- Integration with smart home systems
- Fall detection and emergency alerts
- Location tracking for caregivers
- *Your ideas here!*

---

## ⚠️ Important Notes

### Safety Considerations
This is an **assistive aid**, not a replacement for:
- Mobility training
- White canes or guide animals
- Professional orientation services
- Medical devices

**Always prioritize safety** and consult with accessibility professionals when implementing assistive technology.

### Project Disclaimer
This is a **research concept and educational platform**. While we strive for quality and safety:
- System reliability needs extensive real-world testing
- Users should conduct their own safety assessments
- No warranties or guarantees are provided
- Community feedback is essential for improvement

---

## 🌟 Join the Movement

**Assistive technology should be open, accessible, and community-driven.**

Whether you're building this for yourself, contributing code, sharing feedback, or simply spreading awareness - you're helping make technology more inclusive for everyone.

**Star this repository ⭐** to follow our progress and show your support for open assistive technology!

---

<div align="center">

## Conceptual Diagrams

</div>

### Configuration 1: Raspberry Pi 5 Setup

<div align="center">
 <img src="https://github.com/CreativeActtech/SyntheticSense/blob/main/RPI-5.jpg?raw=true" height="400" width="400">
</div>

>This diagram illustrates a wearable haptic interface that helps users detect obstacles through vibration. When the AI camera spots an object, the Raspberry Pi 5 activates motors on the side closest to the object—vibrating to alert the user.
>
>**This is the central configuration, which various configurations and features can be added in future iterations.**

---

## Configuration 2: Multi-Directional Interface

<div align="center">
 <img src="https://github.com/CreativeActtech/SyntheticSense/blob/main/ui_config2.jpg?raw=true" height="400" width="400">
</div>

>This diagram presents a multi-directional haptic navigation interface designed to assist deaf-blind individuals with basic spatial awareness. When an object is detected, specific motors vibrate in directional patterns—forward, back, left, right, or multi-directional—alerting the user to the obstacle's location. The tactile feedback helps guide navigation without relying on sight or sound.

**These designs can be modified as needed!**

---

<div align="center">
  
**Built with ❤️ for the accessibility community**

Made by [Julian Anival Gonzalez](https://github.com/jewelzufo) | IBM Champion 2025

</div>
