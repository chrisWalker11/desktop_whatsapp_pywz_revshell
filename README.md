# Python Reverse Shell POC

this is a Python script designed to create a reverse shell connection to a remote server. It enables remote command execution through a hidden subprocess on the host machine.

## Warning

**IMPORTANT NOTICE**

This tool establishes a reverse shell connection, which can bypass standard security measures and may not be detected by antivirus software, including Windows Defender. Unauthorized use of this tool is prohibited and can lead to serious security breaches.

### Recent Related Vulnerability

A recent vulnerability in WhatsApp for Windows was discovered, allowing attackers to execute arbitrary Python and PHP scripts due to insufficient file restrictions. Although reported, Meta has not planned a fix, highlighting the importance of cautious interactions with files from unknown contacts. More details can be found in the [Bitdefender article](https://www.bitdefender.com/blog/hotforsecurity/vulnerability-in-whatsapp-for-windows-could-let-attackers-run-python-php-scripts/).

### Disclaimer

- **For Educational Purposes Only:** This script is intended for educational and research purposes in controlled environments where you have explicit permission to test and analyze security vulnerabilities.

- **Unauthorized Use is Prohibited:** Do not use this tool in unauthorized environments or on systems you do not own. Misuse can lead to legal consequences.

- **Security Risks:** Running this script can compromise system integrity. Always verify and understand the source code before execution.

- **Legal and Ethical Responsibility:** Users of this program are responsible for ensuring that its use complies with applicable laws and regulations.

### Usage

- **Authorization Required:** Ensure you have proper authorization before using this tool.
- **Isolated Environment:** Test in isolated and secure environments to prevent unintended harm.
- **Source Code Review:** Review the source code and understand its functionality before execution.

**By using this program, you acknowledge that you understand these risks and responsibilities.**

## How It Works

This script sets up a reverse shell by:

1. Creating a hidden PowerShell subprocess.
2. Establishing a socket connection to a specified IP and port.
3. Using threads to handle input and output between the subprocess and the remote server.

## Setup

1. Clone the repository.
2. Modify the IP address and port in the script to match your server configuration.
3. to test the POC you can download whatsapp for windows and then send yourself the file and open it 

