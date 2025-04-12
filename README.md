# 🎯 Lusky – Educational Python Remote Access Tool (RAT)

**Lusky** is a lightweight and educational Remote Access Tool built in Python. It's designed for cybersecurity demonstrations, ethical hacking tutorials, and automation scripting—all with full user consent.

> ⚠️ **Important**: This project is for **educational use only**. Do not deploy or distribute it without full permission from all parties involved. Misuse may violate laws.
Discord User: elite_qecdz sm me for suggesstions!!!!
---

## 📦 Features

- 🎮 **Telegram or Discord Control** – Choose your platform during build.
- 🖥️ **Screenshot Capture** – Capture the entire screen and send it to your bot/channel.
- 🎥 **Webcam Snapshot** – Take a webcam snapshot and send it to your bot/channel.
- 🎧 **Microphone Recording** – Record audio from the microphone (5s) and send the file.
- 💻 **Remote Shell Commands** – Execute commands remotely and receive the output.
- 📡 **System Info** – Fetch information about the operating system, hostname, and public IP.
- 🔈 **Text-to-Speech (TTS)** – Convert text to speech and play it via the machine’s speakers.
- ⚠️ **Popup Alert Messages** – Show message box alerts on the victim’s screen.
- 🔇 **Volume & Monitor Control** – Adjust system volume and turn off the monitor remotely.
- 🛑 **Website Blocking** – Block websites by adding entries to the hosts file.

---

## 🛠️ Setup

### 1. Clone the repo
Start by cloning the repository:
```
git clone https://github.com/your-username/lusky-rat
cd lusky-rat
2. Install dependencies
Install the necessary Python libraries

pip install -r requirements.txt
3. Run the Builder
Run the builder script to generate your RAT agent:




python builder.py
When prompted:

Choose 1 for Telegram or 2 for Discord.

Enter your bot credentials (bot token and chat/channel ID).

This will generate the lusky.py agent script.

4. Optional: Compile to .exe
If you want to compile the agent into an executable file, use PyInstaller:




pyinstaller --onefile --noconsole lusky.py
The .exe will be available in the dist/ folder.

🤖 Commands
Telegram (prefix: /)
/start – Start the bot and check connection.

/screenshot – Capture and send a screenshot.

/webcam – Take a webcam photo and send it.

/record – Record the mic for 5 seconds and send the audio.

/system – Get OS, hostname, and public IP info.

/cmd <command> – Execute shell command and send output.

/tts <text> – Convert text to speech and play it.

/popup <text> – Display a popup alert with the provided text.

/block <site> – Block a website by adding it to the hosts file.

/monitor off – Turn off the monitor.

Discord (prefix: !)
!screenshot – Capture and send a screenshot.

!webcam – Take a webcam snapshot and send it.

!record – Record the mic for 5 seconds and send the audio.

!system – Fetch OS, hostname, and public IP info.

!cmd <command> – Execute shell command and send output.

!tts <text> – Convert text to speech and play it.

!popup <text> – Display a popup alert with the provided text.

!block <site> – Block a website by adding it to the hosts file.

🔐 Ethical Use Only
This tool is intended for controlled educational labs, ethical hacking demos, and automation scripting.

Important guidelines:

Always obtain full consent from all parties before running this tool.

Do not use this tool on any unauthorized systems.

You are responsible for the ethical and legal use of this tool.

🎬 Used In
This tool was created as part of a YouTube tutorial on ethical cybersecurity and automation scripting. It demonstrates the basic principles of remote access tools and their use in ethical, educational environments.

📺 Watch the full tutorial: [Coming Soon]

🧠 License
MIT License – Use freely with cr. Do not cause harm.

Made with ❤️ for learning. Stay ethical, stay curious.

📑 Requirements
Create a requirements.txt file and install dependencies:

txt


soundfile
sounddevice
opencv-python
pyautogui
pynput
pyttsx3
telebot
discord.py
requests
Install dependencies

pip install -r requirements.txt
📝 Acknowledgements
This tool is built for educational purposes and follows ethical guidelines. It is inspired by various resources aimed at teaching cybersecurity concepts. Always ensure you're acting within the law and with permission when using such tools.

Note: The creators are not responsible for any misuse of this tool. It is your responsibility to ensure ethical and legal use at all times.


