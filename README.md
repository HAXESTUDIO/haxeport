🚀 HaxePort – Advanced Port Scanner (CLI + GUI)




HaxePort is a professional and fast port scanner built for both ethical hacking and network analysis.
It gives users the choice to run either a Command-Line Interface (CLI) version for speed or a Graphical User Interface (GUI) version for ease of use.

✨ Features
🔹 Dual Mode: Run as CLI or GUI (PyQt5)

🔹 Fast Scanning: Multi-threaded for speed

🔹 Custom Port Range: Scan specific ports or all 65535

🔹 Detailed Output: Shows open/closed ports with service info

🔹 Cross-Platform: Works on Kali Linux, Windows, and MacOS

🔹 Educational Purpose: Great for cybersecurity learning

📸 Screenshots
GUI Mode

CLI Mode
sql
Copy
Edit
$ python3 haxeport.py --cli -t 192.168.1.1 -p 1-1000
[+] Scanning Target: 192.168.1.1
[+] Port 22 - Open (SSH)
[+] Port 80 - Open (HTTP)
🛠 Installation
bash
Copy
Edit
# Clone the repository
git clone https://github.com/yourusername/HaxePort.git
cd HaxePort

# Install dependencies
pip install -r requirements.txt
🎯 Usage
CLI Mode
bash
Copy
Edit
python3 haxeport.py --cli -t <target_ip> -p <port_range>
Example:

bash
Copy
Edit
python3 haxeport.py --cli -t 192.168.0.1 -p 1-500
GUI Mode
bash
Copy
Edit
python3 haxeport.py --gui
📂 File Structure
bash
Copy
Edit
HaxePort/
│── haxeport.py         # Main script with CLI & GUI
│── requirements.txt    # Python dependencies
│── README.md           # Documentation
│── screenshots/        # Screenshots for README
⚠ Disclaimer
This tool is strictly for educational purposes and authorized security testing only.
Do not scan networks without permission — illegal activities may lead to criminal charges.

📜 License
This project is licensed under the MIT License – free to use, modify, and distribute.

🤝 Contributing
Pull requests are welcome! If you find bugs or have feature suggestions, feel free to contribute.

🌐 Connect with Me
📧 Email: haxeestudio@gmail.com
🐙 GitHub: HAXESTUDIO
💬 Instagram: @haxe.studio
# haxeport
