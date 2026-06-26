# 🧠 MemGUI-Agent - Smart Automation for Your Mobile Apps

[![Download from Releases](https://img.shields.io/badge/Download-MemGUI--Agent-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/agelong-tanglebush251/MemGUI-Agent/releases)

## 🚀 What Is MemGUI-Agent?

MemGUI-Agent is a desktop program that helps you automate tasks on your phone or tablet. It watches your mobile screen, understands what you see, and carries out long sequences of actions for you. Think of it as a smart assistant that can tap, swipe, and type inside any app – without you touching the screen.

The program remembers what it did before and uses that knowledge to decide what to do next. This makes it ideal for jobs that take many steps, like filling out forms, setting up devices, or testing an app from start to finish.

You do not need to write any code. You do not need to know about artificial intelligence or programming. Just download, install, and run.

## ✨ Features

- **See and act on your phone screen** – MemGUI-Agent connects to your mobile device and sees exactly what you see. It can tap buttons, scroll lists, and enter text.
- **Work through long tasks** – The agent keeps track of where it is in a multi‑step process. It does not lose its place even after hundreds of actions.
- **Learn from context** – It remembers the current app, the previous steps, and your goal. This helps it make smart decisions without needing constant instructions.
- **Use vision and language together** – The program uses a vision‑language model (VLM) to understand images and text on the screen. It reads buttons, labels, and icons as well as a human would.
- **Proactive management** – If something unexpected happens (like a pop‑up or a loading screen), MemGUI-Agent adjusts on its own and continues.
- **Works on Windows** – The tool runs on a Windows PC and connects to an Android or iOS device over USB or Wi‑Fi.

## 💻 System Requirements

Your computer needs to meet these minimum requirements to run MemGUI-Agent smoothly.

| Requirement | Minimum | Recommended |
|-------------|---------|-------------|
| Operating System | Windows 10 64‑bit | Windows 11 64‑bit |
| Processor | Intel Core i5 (8th gen) or AMD Ryzen 5 | Intel Core i7 or AMD Ryzen 7 |
| RAM | 8 GB | 16 GB |
| Graphics | Any GPU that supports DirectX 12 | NVIDIA GTX 1060 or better |
| Storage | 500 MB free space | 2 GB free space |
| Internet | Broadband connection for first download | Broadband connection |
| Mobile Device | Android 8+ or iOS 13+ | Android 12+ or iOS 15+ |

Your mobile device must have **USB debugging** enabled (Android) or **Developer Mode** turned on (iOS). You will need a USB cable or the same Wi‑Fi network for the connection.

## 📥 How to Download

1.  Go to the [MemGUI-Agent Releases page](https://github.com/agelong-tanglebush251/MemGUI-Agent/releases).
2.  Look for the newest version at the top of the list (it says “Latest”).
3.  Click the file that ends with **`.exe`** (for example `MemGUI-Agent-1.0.0-win64.exe`).
4.  Your browser will download the installer. Save it to your **Downloads** folder or your desktop.

If you see a warning from Windows Defender, that is normal. The program is new and has not been downloaded by many people yet. Click “Keep” or “Run anyway” to continue.

## 🛠️ How to Install

1.  Open the `.exe` file you downloaded. If a User Account Control prompt appears, click **Yes**.
2.  Follow the setup wizard. It will ask you where to install the program. The default location (`C:\Program Files\MemGUI-Agent`) works fine.
3.  Check the box that says **Create a desktop shortcut** so you can start the program easily later.
4.  Click **Install**. The process takes about a minute.
5.  When the wizard finishes, click **Finish**. MemGUI-Agent will launch automatically.

## 🔌 How to Connect Your Mobile Device

Before you run the agent, you must connect your phone or tablet to your Windows PC.

**For Android (USB)**

1.  On your phone, go to **Settings > About phone** and tap **Build number** seven times to enable Developer options.
2.  Go to **Settings > Developer options** and turn on **USB debugging**.
3.  Plug your phone into the PC with a USB cable. On your phone, allow USB debugging when the prompt appears.
4.  Open MemGUI-Agent. It will detect your device and show its name.

**For Android (Wi‑Fi)**

1.  Connect both the PC and the phone to the same Wi‑Fi network.
2.  Enable USB debugging on the phone (as above).
3.  In MemGUI-Agent, click **Connect over Wi‑Fi** and enter the IP address shown in your phone’s developer options.

**For iOS**

1.  Install the **WebDriverAgent** helper app on your iPhone (the MemGUI-Agent installer includes instructions).
2.  Connect your iPhone via USB.
3.  Trust the computer on your iPhone when asked.

Once connected, you will see your device screen inside the MemGUI-Agent window.

## ▶️ How to Run an Automation

1.  Start MemGUI-Agent using the desktop shortcut or the Start menu.
2.  On the main screen, click **New Task**.
3.  Give your task a name (like “Sign up for newsletter”).
4.  Choose a **goal** – tell the agent what you want it to do. For example: “Open the Settings app, then go to Wi‑Fi and turn it off.”
5.  Click **Start**. The agent watches your phone screen and begins working.
6.  You can watch each step in real time. The agent highlights the button it is about to tap.
7.  When the task finishes, the agent stops and shows a summary of what it did.

You do not need to record any steps. The agent plans its own actions based on your goal.

## 🧩 Tips for Best Results

- **Keep the screen on** – Make sure your phone screen stays unlocked and bright while the agent works. You can change the screen timeout to 30 minutes or more.
- **Use simple goals** – For your first try, ask the agent to do one simple thing (like opening an app). Longer tasks will work, but start small to learn the feel.
- **Close other apps** – If your phone has many apps open, the agent might confuse itself. Clear recent apps before you start.
- **Check the connection** – If the agent loses sight of your device, the task pauses. Reconnect the USB cable or refresh the Wi‑Fi connection.
- **Pause or stop** – You can pause at any time by pressing **Pause** on the task screen. To cancel, press **Stop**.

## 🐛 Troubleshooting

| Problem | Solution |
|---------|----------|
| Agent does not see my phone | Make sure USB debugging is on (Android) or WebDriverAgent is running (iOS). Try a different USB cable. |
| “Device not found” error | Restart MemGUI-Agent and reconnect your phone. On Android, revoke USB debugging permissions and re‑enable them. |
| Agent taps the wrong button | The lighting or screen rotation might confuse the vision model. Keep your phone flat and well lit. |
| Task runs very slowly | Close other programs on your PC. A lower resolution on your phone can speed up the agent. |
| Windows Defender blocks the program | Click “More info” then “Run anyway”. The program is safe – it does not access your personal data. |
| Agent stops mid‑task | A pop‑up or notification may have appeared. The agent tries to dismiss it, but you can manually close it and press **Resume**. |

## 📄 License

This project is licensed under the **MIT License**. You are free to use, copy, modify, and distribute the software. See the LICENSE file in the repository for full details.

## 🔗 Get Help and Stay Updated

- **Releases and downloads** – [GitHub Releases page](https://github.com/agelong-tanglebush251/MemGUI-Agent/releases)
- **Report a bug** – Open an issue on the repository
- **Official paper** – “MemGUI-Agent: An End-to-End Long-Horizon Mobile GUI Agent with Proactive Context Management” (linked in the repository description)

MemGUI-Agent is a research project. The developers provide it as‑is, with no guarantees, but they welcome feedback to improve it.