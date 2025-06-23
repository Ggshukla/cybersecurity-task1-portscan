# cybersecurity-task1-portscan

## Objective
To perform a TCP SYN scan using Nmap/Zenmap and identify open ports on devices in the local network.

---

## Tools Used
- **Zenmap (Nmap GUI)**
- Windows Command Prompt (to check IP and subnet)

---

## Network Information
- My IP: `192.168.13.178`
- Subnet Mask: `255.255.255.0`
- Target Range: `192.168.13.0/24`

---

## Scan Results

###  Host: `192.168.13.132`
- `53/tcp` open – DNS service

###  Host: `192.168.13.178` (My System)
- `135/tcp` open – Microsoft RPC
- `139/tcp` open – NetBIOS session service
- `445/tcp` open – Microsoft directory services (SMB)

---

##  Security Analysis
- Port 53 (DNS) might be exposed to DNS-based attacks.
- Ports 135, 139, and 445 are commonly targeted for exploits.
- If not required, these services should be blocked or disabled via firewall.

---

##  Files in This Repo
- `scan_results.txt`: Raw Nmap scan output
- `screenshot.png`: Zenmap screenshot
- `README.md`: Explanation and analysis

---

##  Learning Outcome
- Understood how to run a port scan using Nmap.
- Analyzed open ports and their associated risks.
- Gained basic skills in network reconnaissance.
