# Nmap-Scan
This was a Nmap Scan created using virtualized versions of Kali Linux and Ubuntu.

## Objective
The Nmap-Scan project aimed to ensure a connection between two virtualized systems (Kali Linux & Ubuntu, both virtualized through VMWare Fusion Pro. After establishing a controlled virtualization environment, this project enables the user to ensure roper connectivity and responsiveness by simulating an attack on one's home network, which allows the user to identify the attack, and defend against it in real-time, also allowing for real-time system and network hardening. 

### Skills Learned

- Advanced understanding of virtualization workspaces such as Kali Linux and Ubuntu.
- Enhancement of Bash Language syntax recognition.
- Proficiency in analyzing and interpreting network logs.


### Tools Used

- Virtualization System (VMWare Fusion Pro) for setting up a lab testing enviornment.
- Network analysis tools (Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps
1. Use VMWare to initilaize two virtual machines (Kali Linux & Ubuntu)
<img width="1800" alt="Screenshot 2024-07-03 at 9 45 41 PM" src="https://github.com/UJosephUdoh/Nmap-Scan/assets/173506181/27b4ea53-fe37-46c9-b9d0-1e3b2d73d552">


2. In KALI run the command "ip a" to get IP address of the VM
<img width="1102" alt="Screenshot 2024-07-03 at 9 47 32 PM" src="https://github.com/UJosephUdoh/Nmap-Scan/assets/173506181/eddc01f3-5188-44b6-866d-121c8750c35c">


3. Do the same for UBUNTU
<img width="941" alt="Screenshot 2024-07-03 at 9 48 39 PM" src="https://github.com/UJosephUdoh/Nmap-Scan/assets/173506181/fcb83072-cf52-4184-b7e1-89113382ed60">


4. Open Wireshark in UBUNTU
<img width="941" alt="Screenshot 2024-07-03 at 9 49 28 PM" src="https://github.com/UJosephUdoh/Nmap-Scan/assets/173506181/b694c7f6-5169-4d38-a1a1-f9b07ae11eab">


5. Run an Nmap of the ubuntu system on Kali
<img width="613" alt="Screenshot 2024-07-03 at 9 51 31 PM" src="https://github.com/UJosephUdoh/Nmap-Scan/assets/173506181/3debbc5a-a3ec-430e-bfe2-7af2e9028c93">

6. Analyze the influx of network traffic on the UBUNTU VM and use the information to properly defend against possible attacks.
<img width="1756" alt="Screenshot 2024-07-03 at 9 51 48 PM" src="https://github.com/UJosephUdoh/Nmap-Scan/assets/173506181/e97674ef-46eb-47ea-a42e-4682abc020b7">
