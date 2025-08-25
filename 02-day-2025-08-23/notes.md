# Day 2 – Cisco Operating System and the Transport Layer

## Topics Covered
- Cisco IOS (Internetwork Operating System) basics
- Navigating Cisco device modes
- The Transport Layer in the OSI model
- Functions of TCP and UDP
- TCP header structure
- Ports: well-known, registered, and ephemeral

---

## Key Takeaways
- **Cisco IOS** is the software that runs on Cisco devices (routers, switches, firewalls). It provides the CLI (command line interface) used for configuration and troubleshooting.  
- Devices have different **modes**: 
  - User EXEC (limited commands)  
  - Privileged EXEC (more commands, system view)  
  - Global Configuration (system-wide changes)  
  - Interface Configuration (configures a specific interface like Ethernet)  
- The **Transport Layer** ensures data delivery between devices:
  - **TCP (Transmission Control Protocol):** connection-oriented, reliable, acknowledgment-based.  
  - **UDP (User Datagram Protocol):** connectionless, faster, less reliable.  
- **TCP Header** contains fields like Source Port, Destination Port, Sequence Number, Acknowledgment Number, Flags, and more. It governs how TCP ensures reliability.  
- **Port Ranges:**
  - **Well-known ports (0–1023):** Reserved for core services (HTTP 80, HTTPS 443, SSH 22, etc.).  
  - **Registered ports (1024–49151):** Assigned to user or vendor applications.  
  - **Ephemeral ports (49152–65535):** Temporary, automatically chosen for client connections.  

---

## Personal Takeaway
This day stretched me in two directions:  
1. **Cisco IOS** was very challenging. I had to pause my Udemy course and use a YouTube series to understand the basics: [How To Network – Cisco IOS Basics](https://www.youtube.com/watch?v=-Pkwmb8oTDk&ab_channel=howtonetwork). Even then, I know IOS will take repeated practice to feel natural.  
2. **TCP Header and Ports** were new and difficult. The sheer number of fields in the header was overwhelming at first, but I can see how each field has a purpose in ensuring reliable communication. This is another area I’ll need to revisit until it sticks.  

What helped me was connecting ports to real examples:  
- **Well-known ports:** email (25, 110, 143), web (80, 443), SSH (22).  
- **Registered ports:** vendor apps.  
- **Ephemeral ports:** my computer picking a random high-numbered port when opening a web page.  

---

## Terms to Remember
- **Cisco IOS:** Operating system on Cisco devices.  
- **User EXEC / Privileged EXEC:** Different access levels in IOS.  
- **TCP Header:** Contains fields like sequence, acknowledgment, flags, ports.  
- **Well-known ports:** 0–1023, reserved for key protocols.  
- **Registered ports:** 1024–49151, for applications.  
- **Ephemeral ports:** 49152–65535, temporary client-side ports.  

---

## Quick Quiz (Self-Check)
1. What does IOS stand for in Cisco devices?  
2. Which Cisco mode allows system-wide configuration?  
3. Name 3 fields in the TCP header.  
4. What port number is used for HTTPS?  
5. Which port range is reserved for temporary, client-side connections?  
