# Cybersecurity Lab Environment Setup

## Project Overview
This project documents the step-by-step setup and network configuration of a virtual cybersecurity testing environment using VirtualBox and Kali Linux (NetworkWalks Batch B084 - Week 1).

---

## Setup Steps

### Step 1: Download & Extract Kali Linux
Downloaded the Kali Linux virtual machine image and extracted the compressed files.

### Step 2: VirtualBox Installation
Downloaded and installed VirtualBox as the hypervisor.

<img width="1366" height="768" alt="Screenshot (540)" src="https://github.com/user-attachments/assets/6181c369-b2f2-4d75-be6b-6ec650e98389" />

### Step 3: NAT Network Setup
Created and configured a custom NAT Network in VirtualBox using the subnet `10.0.0.0/24`.

<img width="1366" height="768" alt="Screenshot (541)" src="https://github.com/user-attachments/assets/58895576-4599-485f-9b05-1421405d0951" />

### Step 4: Import Kali Linux VM
Imported the Kali Linux virtual machine into VirtualBox and attached it to the NAT Network.

<img width="1366" height="768" alt="Screenshot (537)" src="https://github.com/user-attachments/assets/a96834af-7ed2-4004-b03f-cc7e0c60c3b6" />

### Step 5: Network Configuration in Kali Linux
Configured manual static IPv4 settings within Kali Linux:

- **IP Address:** `10.0.0.2/24`
- **Gateway:** `10.0.0.1`
- **DNS:** `8.8.8.8`

<img width="1366" height="768" alt="Screenshot (542)" src="https://github.com/user-attachments/assets/0049024e-6548-4d8b-9e2f-278e956fb72e" />

step 6: I have created snapshot and I tacked the name clean kali linux network setup
