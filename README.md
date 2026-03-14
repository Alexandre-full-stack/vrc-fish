# 🎣 vrc-fish - Automatic Fishing Helper for Windows

[![Download ▶️](https://img.shields.io/badge/Download-vrc--fish-blueviolet?style=for-the-badge&logo=github)](https://github.com/Alexandre-full-stack/vrc-fish/releases)

---

## 📝 About vrc-fish

vrc-fish is a Windows application designed to help with automatic fishing in VRChat. It uses image recognition and physics-based models to detect and catch fish with minimal input. The tool is built with C++ and OpenCV 4.6.0. While it offers an advanced option for model predictive control (MPC) and machine learning, those are optional features.

This program was initially created to assist a friend with a physical mobility challenge. The main goal is learning and research. Please use it responsibly and follow VRChat's rules and terms of service.

---

## 🔍 Features

- Automatic fish detection using template matching.
- Physics-based models for realistic fishing simulation.
- Optional MPC and machine learning for fine control.
- Runs smoothly on Windows systems.
- Minimal setup required.
- Designed for relaxing, low-effort use.
- Open source under GPL-3.0 license.

---

## 🌎 Supported Environments

vrc-fish is designed to work with VRChat fishing worlds. It adapts to the common fishing interfaces you’ll find there. These include:

- VRChat official fishing worlds.
- Popular community-created fishing worlds.
- Other compatible VRChat fishing experiences.

---

## 💾 Download vrc-fish

[![Download vrc-fish](https://img.shields.io/badge/Download-vrc--fish-7B68EE?style=for-the-badge&logo=github)](https://github.com/Alexandre-full-stack/vrc-fish/releases)

To get the software, visit the releases page linked above. Choose the latest release and download the Windows executable file (.exe). Make sure you pick the file that matches your system (usually 64-bit Windows).

---

## 🚀 Getting Started

Follow these steps to get vrc-fish running on your Windows computer. You do not need programming skills.

1. **Visit the Download Page**

   Click the badge above or go to this URL:  
   https://github.com/Alexandre-full-stack/vrc-fish/releases

2. **Download the Latest Version**

   Look for the most recent release. Under "Assets," find the file ending in `.exe`. Click it to download.

3. **Run the Installer**

   After download completes, double-click the `.exe` file. Windows may ask for permission; allow it to run.

4. **Install or Run Directly**

   Some versions may install automatically. Others run as a portable app. Follow on-screen instructions.

5. **Prepare VRChat**

   Start VRChat and load your fishing world of choice.

6. **Launch vrc-fish**

   Open vrc-fish on your PC. The app will try to detect your VRChat window and fishing area automatically.

7. **Start Fishing**

   Use the buttons in the app to activate fishing assistance. It will detect fish and perform actions to catch them.

---

## ⚙️ Adjusting Settings

vrc-fish has basic options you can change if needed.

- **Sensitivity:** Adjust how closely the program matches fish templates. If it misses fish or produces false catches, try lowering or raising this.
- **MPC Mode:** Turn on or off model predictive control features.
- **Calibration:** Run the calibration tool if the app underperforms or detects incorrectly.
- **Language:** The tool supports English and Chinese text in its interface.

Use these settings only if you feel the default works poorly in your fishing world.

---

## ⚙️ How It Works

vrc-fish uses template matching to recognize when a fish bites. It analyzes the VRChat screen image to spot fish movements. It then uses a physics-based model to simulate casting and reeling.

Optionally, advanced users can enable MPC to improve timing and control. MPC predicts fish motion and optimizes catch strategy.

---

## 🖥️ System Requirements

- Windows 10 or newer (64-bit recommended).  
- 4 GB RAM minimum.  
- OpenGL compatible graphics card.  
- VRChat installed and running.  
- Internet connection to download the app.  

This app uses OpenCV 4.6.0 and needs permission to capture your VRChat window for image processing.

---

## 🔧 Troubleshooting

If you see no fish detected or the app does not respond:

- Make sure VRChat runs in windowed or borderless window mode. Fullscreen may prevent detection.  
- Disable any overlays that might block the VRChat window.  
- Check your graphics drivers are up to date.  
- Restart vrc-fish and VRChat if it freezes or disconnects.  
- Run calibration from the settings menu.  
- Verify you downloaded the correct version for Windows.

---

## 🛠️ Building from Source (Advanced)

If you want to build vrc-fish yourself, you need:

- Visual Studio 2019 or newer.  
- C++ development tools installed.  
- OpenCV 4.6.0 libraries configured.  

Clone the GitHub repo, open the solution file, and build. Detailed steps and dependencies are in the `BUILD.md` file in the repository.

---

## 🙏 Acknowledgments

This tool was inspired by a friend with mobility challenges. It is mainly for learning and research. Thanks to the VRChat community for testing and feedback.

---

[🔽 Download vrc-fish](https://github.com/Alexandre-full-stack/vrc-fish/releases)