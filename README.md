# 🔥 Hades Copilot

**The Ultimate Companion App for Hades**

A powerful, real-time companion application designed to enhance your Hades gameplay experience with intelligent build recommendations, synergy detection, and strategic guidance.

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

## ✨ Features

### 🎯 Core Features
- **Boon Tracker**: Track all boons collected during your run
- **Synergy Detector**: Real-time detection of powerful boon combinations
- **Build Advisor**: Smart recommendations for optimal build paths
- **Door Advisor**: Strategic room choice suggestions
- **Boss Prep Assistant**: Preparation tips before boss encounters
- **Legendary Tracker**: Track requirements for legendary boons
- **Duo Tracker**: Monitor duo boon requirements and possibilities

### 🎨 User Interface
- Modern, intuitive GUI built with CustomTkinter
- Dark theme optimized for gaming
- Real-time updates and notifications
- Minimalist design that doesn't distract from gameplay

### 📊 Advanced Features
- **Build Templates**: Save and load custom build strategies
- **Run Statistics**: Track your run performance over time
- **Export/Import**: Share builds with the community
- **Keepsake Recommendations**: Smart keepsake suggestions
- **Mirror Talent Advisor**: Optimal mirror upgrade paths

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/spiky529-pixel/hades-copilot.git
cd hades-copilot
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python main.py
```

## 📖 Usage

### Starting a New Run
1. Launch Hades Copilot
2. Select your weapon from the dropdown
3. Choose your starting keepsake
4. Click "Start Run"

### During Your Run
- **Add Boons**: Click the "Add Boon" button and select boons as you get them
- **Check Synergies**: The synergy panel automatically highlights powerful combinations
- **Get Advice**: The advisor panel provides real-time strategic recommendations
- **Track Progress**: Monitor your build strength and legendary/duo possibilities

### Build Templates
- **Save**: Click "Save Build" to store your current run configuration
- **Load**: Select a saved template to see recommended boons for that strategy
- **Share**: Export builds as JSON files to share with friends

## 🏗️ Project Structure

```
hades-copilot/
│
├── main.py                 # Application entry point
├── ui_components.py        # GUI components and layout
├── boon_tracker.py         # Boon tracking logic
├── synergy_detector.py     # Synergy detection algorithms
├── build_advisor.py        # Build recommendation engine
├── door_advisor.py         # Room choice logic
├── boss_prep.py           # Boss preparation assistant
├── data_manager.py         # Data persistence and management
│
├── data/
│   ├── boons.json         # Complete boon database
│   ├── synergies.json     # Synergy definitions
│   ├── builds.json        # Saved build templates
│   └── weapons.json       # Weapon data
│
├── assets/
│   └── icons/             # UI icons and images
│
├── requirements.txt        # Python dependencies
├── LICENSE                # MIT License
└── README.md              # This file
```

## 🎮 Supported Features by God

- ⚡ **Zeus**: All boons, chain lightning synergies
- 🌊 **Poseidon**: All boons, knockback synergies
- 🏹 **Artemis**: All boons, critical hit synergies
- ❤️ **Aphrodite**: All boons, weak synergies
- 🍷 **Dionysus**: All boons, hangover synergies
- ⚔️ **Ares**: All boons, doom synergies
- 🏃 **Hermes**: All boons, speed synergies
- 😈 **Chaos**: Chaos boons tracking
- 💀 **Thanatos**: (Future support)

## 🔧 Configuration

Customize the app by editing `config.json`:

```json
{
  "theme": "dark",
  "notifications": true,
  "auto_save": true,
  "sound_effects": false
}
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Setup

```bash
# Install development dependencies
pip install -r requirements-dev.txt

# Run tests
python -m pytest tests/

# Run linter
flake8 *.py
```

## 📝 Roadmap

- [ ] Live game data integration (screen capture)
- [ ] Machine learning build recommendations
- [ ] Multi-language support
- [ ] Web dashboard for statistics
- [ ] Mobile companion app
- [ ] Steam Workshop integration
- [ ] Hades 2 support (when released)

## 🐛 Known Issues

See [Issues](https://github.com/spiky529-pixel/hades-copilot/issues) for a list of known issues and feature requests.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Supergiant Games** for creating the amazing game Hades
- The Hades community for game data and strategies
- Contributors who help improve this tool

## 📧 Contact

- GitHub: [@spiky529-pixel](https://github.com/spiky529-pixel)
- Issues: [GitHub Issues](https://github.com/spiky529-pixel/hades-copilot/issues)

## ⚠️ Disclaimer

This is a fan-made tool and is not affiliated with or endorsed by Supergiant Games. Hades and all related properties are trademarks of Supergiant Games.

---

**Made with ❤️ by the Hades community**
