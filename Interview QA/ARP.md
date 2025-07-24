ARP – Address Resolution Protocol

##  What is ARP?
- ARP maps an **IP address to a MAC address**.
- Used when a device wants to communicate within a local network.

## How It Works:
1. Device checks ARP cache for MAC of destination IP
2. If not found → sends ARP Request (broadcast)
3. Target device replies with ARP Reply (unicast)
4. MAC is stored in ARP cache

## Commands:
- `arp -a` (Windows) → View ARP table
- Used in **Layer 2 + Layer 3 communication**

## Example:
- IP: 192.168.1.10 → Needs MAC of 192.168.1.1 (Gateway)
→ Sends ARP Request  
→ Gets ARP Reply with MAC address
