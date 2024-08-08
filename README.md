# Network Ping Scanner

This project is a Python script that scans a range of IP addresses within a given network to check their online or offline status using the ping command. The script prompts the user to enter a network address in CIDR format and a range of host IP addresses to scan. It then pings each IP in the specified range and reports whether the host is online or offline.

## About

This Python script is designed to perform a network scan by pinging a specified range of IP addresses within a network. It helps network administrators or users quickly identify which hosts are online or offline. The script uses the `subprocess` module to execute the ping command and parses the output to determine the status of each IP address.

## Features

- Network Scanning: Scans a specified range of IP addresses within a network.
- Ping Test: Uses the ping command to check if an IP address is online or offline.
- User Input: Allows the user to specify the network and range of IPs to scan.
- Real-Time Status: Continuously monitors the status of the specified IP range.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vigneshcsengineer/network-status-update-using-python/tree/main.git
   cd main.git

2.Run the script
  python network_ping_scanner.py

