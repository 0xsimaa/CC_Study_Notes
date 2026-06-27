## 3.1 Understand Computer Networking

You don’t need to be a network engineer, but you **must** understand how data moves across networks and the basic models used to describe it.

### The OSI Model (7 Layers); Most Important Concept in This Domain

The OSI model is a **conceptual framework** that standardizes how different networking technologies communicate. It’s heavily tested.

| Layer | Name             | Function                                                                  | Example Protocols / Devices           | Mnemonic Word |
| ----- | ---------------- | ------------------------------------------------------------------------- | ------------------------------------- | ------------- |
| 7     | **Application**  | User interface, provides network services to applications                 | HTTP, HTTPS, FTP, SMTP, DNS           | Away          |
| 6     | **Presentation** | Translates data between application and network (encryption, compression) | SSL/TLS, JPEG, MPEG                   | Pizza         |
| 5     | **Session**      | Manages sessions/connections between applications                         | NetBIOS, RPC, SIP                     | Sausage       |
| 4     | **Transport**    | End-to-end delivery, segmentation, reliability (TCP/UDP)                  | TCP, UDP                              | Throw         |
| 3     | **Network**      | Logical addressing (IP), routing between networks                         | IP, ICMP, Routers                     | Not           |
| 2     | **Data Link**    | Physical addressing (MAC), error detection, switches                      | Ethernet, MAC addresses, Switches     | Do            |
| 1     | **Physical**     | Actual transmission of raw bits over physical medium                      | Cables, Hubs, Repeaters, WiFi signals | Please        |

### TCP/IP Model (4 Layers); The Practical Model

This is the model actually used on the internet. It’s simpler than OSI.