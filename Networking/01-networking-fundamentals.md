# Day 1 - Networking Fundamentals

## 📚 Topics Covered
- What is a Network
- Types of Network (LAN, WAN, Internet)
- IP Address (IPv4)
- Public vs Private IP
- OSI Model (Basic Understanding)
- TCP vs UDP Difference

---

## 🌐 What is a Network?

A network is a system where two or more devices are connected to share data and resources. These devices can be computers, servers, mobile phones, or other networking devices.

### Types of Networks:

- **LAN (Local Area Network):**  
  A network that connects devices within a small area like a home, school, or office.

- **WAN (Wide Area Network):**  
  A network that covers a large geographical area, such as multiple cities or countries.

- **Internet:**  
  The largest WAN in the world that connects millions of networks globally.

---

## 🖥 What is an IP Address?

An IP (Internet Protocol) address is a unique address assigned to every device connected to a network. It helps in identifying and locating devices for communication.

### Types of IP Address:

- **Public IP:**  
  An IP address that is accessible over the internet and assigned by an ISP.

- **Private IP:**  
  An IP address used inside a local network. It is not directly accessible from the internet.

### Private IP Ranges:
- 10.0.0.0 – 10.255.255.255  
- 172.16.0.0 – 172.31.255.255  
- 192.168.0.0 – 192.168.255.255  

---

## 🧱 OSI Model (Basic Idea)

The OSI Model is a 7-layer model that explains how data travels from one device to another over a network.

1. **Physical Layer:** Handles physical transmission of data (cables, signals).
2. **Data Link Layer:** Handles MAC addresses and local network communication.
3. **Network Layer:** Handles IP addressing and routing.
4. **Transport Layer:** Ensures reliable or fast delivery using TCP or UDP.
5. **Session Layer:** Manages sessions between devices.
6. **Presentation Layer:** Handles data formatting and encryption.
7. **Application Layer:** Provides services directly to the user (HTTP, FTP, etc.).

---

## 🔥 TCP vs UDP

### TCP (Transmission Control Protocol):
- Connection-oriented
- Reliable data transfer
- Ensures data reaches in correct order
- Slower but secure

### UDP (User Datagram Protocol):
- Connectionless
- Faster transmission
- No guarantee of delivery
- Used in streaming and online gaming

---

## 🛠 Practical Commands Executed

### 1️⃣ ipconfig
This command shows IP configuration of my system.

**Observation:**
- My IPv4 Address: (Write your IP here)
- IP Type: (Private/Public)
- Default Gateway: (Write here)

---

### 2️⃣ ping google.com
This command checks connectivity with another server.

**Observation:**
- Packets Sent: (Write)
- Packets Received: (Write)
- Packet Loss: (Write)
- Average Time: (Write)

---

### 3️⃣ tracert google.com
This command shows the path taken by packets to reach the destination.

**Observation:**
- Total Hops: (Write)
- Time taken at each hop: (Short summary)

---

## 🧠 What I Understood Today

Today I understood how devices communicate in a network and how IP addressing works. I also learned how data travels through different OSI layers and the difference between TCP and UDP. These concepts are important for a SOC Analyst because understanding network traffic and protocols is essential for detecting suspicious activities.
