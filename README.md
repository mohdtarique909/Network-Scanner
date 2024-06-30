# Network-Scanner

A simple Python script that scans a given IP address or IP range to find devices on the network. It uses ARP requests to identify active devices and displays their IP and MAC addresses.

## Features

- Scans a specified IP address or range.
- Displays the IP and MAC addresses of discovered devices.
- Suppresses deprecation warnings related to cryptographic algorithms.

## Prerequisites

- Python 3.x
- `scapy` library

## Installation

1. Clone the repository:
    ```sh
    https://github.com/mohdtarique909/Network-Scanner.git
    ```

2. Change to the project directory:
    ```sh
    cd Network-Scanner
    ```

3. Install the required Python libraries:
    ```sh
    pip install -r requirements.txt
    ```

    This command will install all the dependencies listed in the `requirements.txt` file. The `requirements.txt` file contains the names of the libraries your project needs, such as `scapy` and `cryptography`.

## Usage

Run the script with the target IP or IP range as an argument:

```sh
python Network_Scanner.py -t <target_ip_or_range>


