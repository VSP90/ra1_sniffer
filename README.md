# Advanced Network Sniffer Tool

## Description

This is an advanced network sniffer tool built using Python and Scapy. It captures and analyzes network traffic similar to Wireshark.

## Requirements

- Python 3.x
- Scapy

## Installation

1. Install Python 3.x and Scapy if not already installed:

    ```bash
    sudo apt update
    sudo apt install python3 python3-pip
    pip3 install scapy
    ```

2. Clone the repository or download the `ra1_sniffer.py` and `run_ra1_sniffer.sh` files.

3. Make the shell script executable:

    ```bash
    chmod +x run ra1_sniffer.sh
    ```

## Usage

Run the tool using the shell script:

```bash
./run_ra1_sniffer.sh -i <interface> -c <count> -p <protocol> -o <output_file> -t <timeout>
