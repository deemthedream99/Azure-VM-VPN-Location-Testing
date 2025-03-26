# VM & VPN Location Testing 

## Overview
This lab demonstrates IP tracking, geographic differences, and VPN effects by creating an Azure Virtual Machine, testing IP addresses, and using ProtonVPN.

## Components
- Cloud Provider: Microsoft Azure
- VM OS: Windows 10
- VPN Service: ProtonVPN

## Steps Taken
1. Record Your Local IP
    - Browse to https://whatismyipaddress.com/ from your actual machine.
    - Save your public IP address in a text file.
    - Log into the VM via Remote Desktop and record its IP.
2. Create an Azure Virtual Machine
    - Create a new resource group in Azure.
    - Deploy a Windows 10 Virtual Machine in a different geographic region (preferably another country).
    - Log into the VM using Remote Desktop.
3. Record the VM’s IP Address
    - Inside the VM, browse to https://whatismyipaddress.com/.
    - Save the VM’s public IP address in a text file.
4. Set Up ProtonVPN
    - On your actual computer, sign up for a free ProtonVPN account: ProtonVPN Signup.
    - Inside the VM, download and install the ProtonVPN client.
5. Connect to a VPN Server
    - Log in to ProtonVPN inside the VM: ProtonVPN Login.
    - Choose a VPN server in a different country (e.g., Japan).
    - Browse to https://whatismyipaddress.com/ again and record the new IP.
6. Test Website Differences
    - Visit Google, Disney, and/or Amazon from the VPN-connected VM.
    - Observe any regional differences (e.g., language, URL changes, localized content).

## Verification Screenshots
![My device's IP address](https://github.com/user-attachments/assets/22e67f53-cdbe-4ebe-9844-46cdc9541154)
![VM IP Address](https://github.com/user-attachments/assets/4b510f01-e515-409a-8b2f-1ff6c366a18e)
![VPN Setup on VM](https://github.com/user-attachments/assets/c19e8ac6-6508-42d7-a8c6-647693c44cab)
![IP address after connecting to VPN](https://github.com/user-attachments/assets/d0a0b1bd-6356-41b2-8802-18a2bcd7528e)
![Google (Brazil)](https://github.com/user-attachments/assets/71e7c134-9fda-46e1-8e65-3d3d7eafbae6)
![Amazon (Brazil)](https://github.com/user-attachments/assets/f3cbe33f-bc7c-4214-9025-2a1c42a9b35f)






