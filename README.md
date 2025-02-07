# Basic Network Sniffer

This project is a basic network sniffer built in Python using the `scapy` library. It captures and analyzes network traffic, helping you understand how data flows on a network and how network packets are structured.

## Features

- Captures network packets on a specified interface.
- Logs detailed information about each captured packet, including:
  - Packet summary
  - Source and destination IP addresses (if available)
  - Source and destination ports for TCP and UDP packets (if available)
- Handles exceptions and user interruptions gracefully.

## Prerequisites

- Python 3.x
- `scapy` library

## Installation

1. Install Python 3.x from the [official website](https://www.python.org/downloads/).
2. Install the `scapy` library using pip:
   ```sh
   pip install scapy
