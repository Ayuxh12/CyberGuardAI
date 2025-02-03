# CyberGuardAI

CyberGuardAI is a **network traffic analysis** project designed for **cybersecurity threat detection**. It utilizes **machine learning** to analyze network packets and classify them as **normal or malicious traffic**.

## Features
- Parses network traffic data (e.g., packet size, protocol type, number of packets).
- Implements machine learning models for threat detection.
- Provides insights into network security threats.
- Generates predictions for real-time network monitoring.

## Dataset
The dataset used in this project contains:
- `packet_size`: Size of the network packet.
- `num_packets`: Number of packets in a session.
- `protocol_type`: Type of network protocol.
- `label`: Classification of the traffic (0 = Normal, 1 = Malicious).

## Requirements
Before running the project, install the necessary dependencies:

```bash
pip install -r requirements.txt
