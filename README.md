# Aterms

A lightweight Termux-based web terminal that runs a local terminal inside any web browser.


---

🔧 Overview

Aterms launches an xterminal-like web shell in Termux. It starts a local web server and exposes a full interactive Terminal UI inside your mobile or desktop browser.

Use it to:

Access Termux from your browser

Use keyboard shortcuts more easily

Run commands over WiFi LAN

Share terminal access with another device



---

📥 Installation

Download the aterms executable script from GitHub.

git clone https://github.com/crossberry-in/Aterms.git
cd Aterms
chmod +x aterms

Or download only the file:

curl -LO https://raw.githubusercontent.com/crossberry-in/Aterms/main/aterms
chmod +x aterms

Move it to a global location (optional):

mv aterms $PREFIX/bin/


---

▶️ Run Aterms

Simply execute:

aterms

You will see something like:

Aterms Web Terminal running at:
http://localhost:8080

Open that link in any browser.

To access from another device on the same network:

http://<your-phone-ip>:8080


---

✨ Features

Web-based terminal interface

Auto-start server

Real-time command output

Supports networking access

Works with Chromium, Chrome, Firefox, Edge

Zero dependencies other than Termux



---

📁 Project Structure

Aterms/
│── aterms        # main bash script
│── README.md
└── public/       # html/css/js assets for web terminal


---

🔗 Author / Homepage

Developed by Crossberry

🌐 https://crossberry.vercel.app

GitHub Repo:

https://github.com/crossberry-in/Aterms


---

💡 Notes

Make sure Termux storage permission is granted if you serve additional files.

Use a strong password or LAN firewall if exposing to network.



---

📜 License

MIT License

Feel free to modify, improve, and contribute.


---

Enjoy Aterms — your portable web terminal!

Your full README.md is ready!
If you want edits (styling, logo, badges, screenshots, installation script, auto-start command, etc.), just tell me — I can update the document.
