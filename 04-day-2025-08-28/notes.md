# Day 4 – IP Address Classes and Subnetting

## Topics Covered
- IP address classes (A, B, C, D)
- Practical uses of different classes
- Subnet masks and CIDR notation (/8, /16, /24)
- Loopback IP addresses (127.x.x.x)
- Network vs Host portions of an IP

---

## Key Takeaways
- IP addresses are divided into **network** and **host** portions, and subnetting tells the computer which part is which.  
- **Class A (1–126):** Originally for very large organizations, but considered wasteful today. Default subnet mask: **/8** (255.0.0.0).  
- **Class B (128–191):** For medium-sized networks. Default mask: **/16** (255.255.0.0).  
- **Class C (192–223):** For smaller networks. Default mask: **/24** (255.255.255.0).  
- **Class D (224–239):** Reserved for multicast, not host addressing.  
- **Loopback range (127.0.0.0/8):** Used for testing and internal communication within a machine.  
- Subnetting is critical because it defines how many hosts can exist in a network and reduces waste.

---

## Personal Takeaway
This section has been **challenging**, but I feel the plane is starting to land.  
- I’m starting to see how IP classes descend from large-scale (Class A) to small-scale (Class C).  
- I understand now why Class A is rarely used — it wastes too many IPs.  
- I’ve gotten more comfortable with **Class A ranges** but still need more practice with **Classes B and C**.  
- The **subnet logic** is beginning to make sense: `/8` means the first octet is locked for the network (255.0.0.0).  
- Loopback IPs (127.x.x.x) were also something new I paid closer attention to.  

I also started attempting some **exam-relevant practice questions**, which made me realize that while memorizing ranges is hard, I’m getting better at it each time I review.

---

## Terms to Remember
- **Network Portion:** Identifies the network.  
- **Host Portion:** Identifies a device within the network.  
- **Class A:** 1.0.0.0 – 126.255.255.255 (/8).  
- **Class B:** 128.0.0.0 – 191.255.255.255 (/16).  
- **Class C:** 192.0.0.0 – 223.255.255.255 (/24).  
- **Class D:** 224.0.0.0 – 239.255.255.255 (multicast).  
- **Loopback Range:** 127.0.0.0/8.  

---

## Quick Quiz (Self-Check)
1. What is the default subnet mask for Class A?  
2. Why is Class A considered wasteful?  
3. Which IP class uses multicast?  
4. What does the subnet mask 255.255.0.0 represent in CIDR?  
5. Which IP range is reserved for loopback testing?
