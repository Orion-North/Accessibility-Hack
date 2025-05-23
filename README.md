# Accessibility-Hack
**2025 STEM Project**

This USB Rubber Ducky payload automatically enables core accessibility settings on a Windows machine for users with visual impairments. It provides instant, hands-free access to key assistive technologies, reducing dependency on sighted setup and empowering independent use.

This project is a class project and was designed to accomidate the following ficticious client:
- Client Profile 2: Jamal, 29, Visual Impairment
    - Jamal is a 29-year-old graphic designer who was diagnosed with retinitis pigmentosa, leading to significant vision loss. He struggles with reading small text, navigating unfamiliar environments, and using standard computer interfaces. Despite his condition, Jamal is determined to continue his career and maintain his independence. Adaptive technologies like screen readers, braille displays, or wearable navigation aids with audio feedback could help him access digital content and move safely in his surroundings.

## ⚙️ Features Enabled
- **Narrator** — Screen reader for blind/low vision users
- **Magnifier** — Zoom into portions of the screen
- **High Contrast Mode** — Enhanced UI clarity
- **On-Screen Keyboard** (OSK) — For users with difficulty locating physical keys
- **Ease of Access Settings** — Opens full accessibility options menu

## Target System
- Designed for Windows 11 Systems
- No admin required

## 🪛 How It Works
The payload simulates keystrokes to toggle built-in Windows accessibility features. It waits briefly for the system to stabilize, then sequentially issues keyboard shortcuts and run commands to configure the environment for low-vision use.

## Usage
- Move the payload file in the desired folder to the root directory of the USB Rubber Ducky
- Plug in the USB Rubber Ducky and allow the payload to complete