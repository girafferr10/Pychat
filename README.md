# Pychat
A small python based app used for talking with your friends!
Ai was used to help with the making of the app.

README
=========
Documentation for the handling of the above linked program

Please email 948425@scienceandtech.org for questions.

See the EXTRA NOTES section of this document for extra details.

SETUP NOTES:

0.1 Acquire IP Addresses
=========================
Identify server (mentioned later) IP to connect to using the client. Please use the correct instructions for your operating system. Please note that the server cannot be run from Windows unless you have admin permissions.

0.11 | Windows:
Open Windows PowerShell and type in "ipconfig" then press Enter. Search under "Wireless LAN Adapter (WiFi)" for "IPv4 Address". The number there should be in this format, though the numbers will vary: 000.00.00.00. Keep this number if you are setting up the server (mentioned later) because you will need this code.

0.12 | Linux:
Open Terminal (this can typically be done by pressing CTRL-ALT-T) and then type in "hostname -I" (Terminal is case-sensitive). The number there should be in this format, though the numbers will vary: 000.00.00.00. Keep this number if you are setting up the server (mentioned later) because you will need this code.

0.13 | macOS:
Open System Settings and then navigate to Network. Search there for a number that should be formatted like this: 000.00.00.00. Keep this number if you are setting up the server (mentioned later) because you will need this code.

0.2 Python Setup
=================
Before opening the program, you will need to configure Python to include the dependencies required to run it, as they are NOT installed automatically. Please use the correct instructions for your operating system.

0.21 | Windows:
Open python.org and download the Python 3.14 installer. Run this and install Python. When complete, open the Python app and type "pip install -m websockets" to install the dependencies needed to run the program.

0.22 | Linux:
Python will already be installed but you should run all system updates for your distribution to make sure your Python version is up to date. Then, open Terminal and type "pip install websockets".

0.23 | macOS:
Open python.org and download the Python 3.14 installer. Run this and install Python. When complete, open the Terminal and type "pip install websockets".

0.3 Acquire access to program
==============================
Obtain access to the PyChat Google Drive via this email: 948425@scienceandtech.org

1.0 Download program
=====================
Open the PyChat Google Drive folder and download "relay_server.py" if you are planning to host a server as well as "chat_client.py" for everyone in order to join servers. Ideally, these files should be saved to their own "PyChat" folder on your computer.

1.1 Setup Server
=================
ONLY FOLLOW THESE STEPS IF YOU ARE HOSTING A SERVER. Open "relay_client.py". If it reports a traceback error, you do not have websockets installed and will need to troubleshoot. The server will start automatically and will be open to any connecting clients with that server's IP address.

1.2 Setup Client
=================
Open "chat_client.py". It will ask for a server IP address. If a server is running at a given IP address, you can type that IP in and you will now be in that server. You will be asked to input your username and then you will be chatting with anyone else in that server.

EXTRA NOTES:

1.A Chat Limitations
======================
Only ASCII characters (basic letters, numbers, and punctuation) are supported. Typing emojis or other non-supported characters can lead to server instability or even crash a client or server.

1.B IP Warning
===============
Do NOT share IP addresses with people you do not trust as leaked IP addresses allow hackers to hack networks and cause instability. Use caution when distributing a server's IP.

Finn Walsh wrote this.
