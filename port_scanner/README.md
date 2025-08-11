# autopi
# Security Automation Scripts
# Requirements - Python 3.x

# Script 1 - port_scanner.py
#Overview
# A simple Python script that scans specified ports on a target host to determine if they are open or closed. This tool demonstrates basic networking concepts and automation for security tasks.

## Features
- Scans a list of common ports (configurable)
- Displays open/closed status for each port
- Adjustable timeout for faster or slower scans

## Usage
1. Clone the repository.
2. Run the script:
   ```bash
   python port_scanner.py
3. Enter the target host when prompted.

## Example Output
pgsql
Enter target host: scanme.nmap.org
Port 21 is CLOSED
Port 22 is OPEN
Port 80 is OPEN
Port 443 is OPEN
