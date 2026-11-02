# Firewalls

## 1\. Introduction

A **firewall** is a network security system that protects computers and networks from unauthorized access and cyber attacks. It monitors incoming and outgoing network traffic and allows/ blocks data based on predefined security rules.

Firewall acts as a barrier between a trusted internal network and an untrusted network. Firewalls can be implemented through **hardware or software**.

---

## 2\. Data Packets/ IP Packets 

When data is transferred over a network, it is divided into smaller units called **data packets** or **IP packets**  and it is consists of two main parts:

1. **Header:** Contains information such as source IP address, destination IP address, and protocol details.
2. **Payload:** Contains the actual data being transferred, such as text, images, or files.

A firewall examines packet information and decides whether the data should be **allowed or blocked**.

---

## 3\. Types of Firewalls

### 3.1 Packet Filtering Firewall

A packet filtering firewall checks data packets based on information such as source and destination IP addresses, port numbers and protocols. It allows/ blocks packets according to predefined rules.

It is commonly used in routers and small networks to block unwanted traffic and restrict access to specific ports.

### 3.2 Proxy Firewall (Application-Level Firewall)

A proxy firewall acts as an intermediary between a user and the destination server. It examines application-level traffic before forwarding requests. It also helps to hide internal network information from external systems.

It is used in schools and organizations to monitor internet usage, block restricted websites and inspect web traffic.

### 3.3 Hybrid Firewall

A hybrid firewall combines features of different firewall technologies, such as packet filtering, stateful inspection and application-level filtering.

It is suitable for large organizations and businesses that require multiple layers of network protection.

---

## 4\. Limitations of Firewalls

Although firewalls improve network security, they have certain limitations:

- **Insider Intrusion:** They may not prevent malicious activities performed by authorized internal users.
- **Direct Internet Traffic:** Traffic that bypasses the firewall may remain unprotected.
- **Trusted Networks:** Attackers who gain access to an internal network may exploit its trusted status.
- **Masquerading:** Attackers may use fake IP addresses to hide their identity and bypass basic filtering rules.

These vulnerabilities show that firewalls alone are not able to prevent every cyberattack. Additional security measures are necessary.

---

## 5\. Hardware Firewall vs. Software Firewall

| Hardware Firewall | Software Firewall |
| --- | --- |
| A physical device that protects a network. | A program installed on a computer. |
| Protects multiple connected devices. | Mainly protects an individual device. |
| Commonly used in organizations. | Commonly used on personal computers and servers. |
| Example: Firewall-enabled network router. | Example: Windows Defender Firewall. |


---

## 6\. Conclusion

Firewalls are an essential part of network security because they help to prevent unauthorized access and control network traffic. Packet filtering, proxy and hybrid firewalls provide different levels of protection depending on network requirements.

However, firewalls have limitations and cannot protect against every security threat. Therefore, they should be combined with other security practices to maintain a safe and reliable network.

---

## 7\. References

- [YouTube – Firewall Video Series](<https://www.youtube.com/watch?v=eO6QKDL3p1I&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6>)
- [NIST – Guidelines on Firewalls and Firewall Policy](<https://csrc.nist.gov/pubs/sp/800/41/r1/final>)
- [Canadian Centre for Cyber Security – Cyber Security Guidance](<https://www.cyber.gc.ca/en/guidance>)
- [NIST – Firewall Definition and Cybersecurity Resources](<https://csrc.nist.gov/>)
