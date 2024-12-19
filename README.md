**Name**:SURAJ BORKUTE
**Company**:CODTECH IT SOLUTIONS
**ID**:CT08DSM
**Domain**:Cyber Security & Ethical Hacking
**Duration**: Dec to jan 2025
**Mentor**:Neela Santosh kumar


#  **Title: Vulnerability Scanning Tool**

A Python-based vulnerability scanner that helps identify open ports and potential vulnerabilities on a target system.

![WhatsApp Image 2024-12-18 at 17 18 30_2ff06c56](https://github.com/user-attachments/assets/2716e3f5-05cf-4c92-b6fa-bfdeceaa60ff)


![WhatsApp Image 2024-12-19 at 16 25 02_e7767ecd](https://github.com/user-attachments/assets/814b2fe3-43f3-4b31-9179-f0254cba0238)

![WhatsApp Image 2024-12-19 at 16 25 13_aac54a29](https://github.com/user-attachments/assets/21b8bef9-a1f6-49d4-b40c-58400fa58c13)

## Features
- **Target Scanning**: Scans a given IP address or domain.
- **Customizable Port Range**: Specify a range of ports to scan, or use the default range of 1-1024.
- **Protocol Analysis**: Identifies protocols associated with open ports.
- **Service Detection**: Highlights common services like HTTP on port 80.
- **User-Friendly Output**: Displays organized scan results with host details, protocols, ports, and states.

## Requirements
To use this tool, ensure the following are installed:
- **Python 3.x**: The script is written in Python and requires version 3.x or later.
- **Nmap**: The Nmap utility must be installed on your system.
- **Python-Nmap**: A Python library to interact with Nmap.

## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/vulnerability_scanner.git
   cd vulnerability_scanner
   ```
2. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure Nmap is installed. On Linux-based systems:
   ```bash
   sudo apt-get install nmap
   ```
   On macOS:
   ```bash
   brew install nmap
   ```
   On Windows, download and install Nmap from the [official website](https://nmap.org/download.html).

## Usage
Run the script using the following command:
```bash
python3 vulnerability_scanner.py
```

### Workflow
1. **Input the target**: Enter the IP address or domain you wish to scan.
2. **Specify port range**: Enter the range of ports to scan (default is 1-1024).
3. **View results**: The output will list the following:
   - Host and its state (e.g., up/down).
   - Open ports, their states, and associated protocols.
   - Any detected services, with additional notes for common ones like HTTP.

## Example
```
$ python3 vulnerability_scanner.py
Enter the target IP or domain: 192.168.1.1
Enter the port range to scan (default: '1-1024'): 
Scanning 192.168.1.1 for open ports...

Host: 192.168.1.1
State: up
Protocol: tcp
Port: 22	State: open
Port: 80	State: open	HTTP is open! Further testing can be implemented here.
Port: 443	State: open
```

## Commands for Modifications or Updates
- To update Python dependencies:
  ```bash
  pip install --upgrade -r requirements.txt
  ```
- To update the script or repository:
  ```bash
  git pull
  ```

## Contributing
If you'd like to contribute to this project, fork the repository, make your changes, and submit a pull request. Contributions are welcome!


## **🔗 Links**

For questions or inquiries, feel free to contact us:

**[LinkedIn Profile]**: (https://www.linkedin.com/in/suraj-borkute-512665341)

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## About
**Owner**: Suraj Borkute  
This project was developed to provide a simple, effective tool for vulnerability assessment and security scanning.

## Disclaimer
This tool is for educational purposes only. Ensure you have proper authorization before scanning any system.
