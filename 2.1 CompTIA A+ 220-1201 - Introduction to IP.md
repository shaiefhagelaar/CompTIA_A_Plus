## Introduction to IP (CompTIA A+ 220-1201)

The **Internet Protocol (IP)** is the primary protocol in the Network Layer of the OSI model. It is responsible for addressing and routing packets across a network so they can reach their destination. For the CompTIA A+ exam, understanding how these addresses are structured and how they function is foundational.

---

### 1. IPv4 (Internet Protocol version 4)
IPv4 is the most widely used addressing scheme. Despite the exhaustion of new addresses, it remains the standard for most local area networks (LANs).

* **Structure:** A 32-bit binary address displayed in **dotted-decimal notation**.
* **Format:** Four numbers (octets) separated by periods (e.g., `192.168.1.1`).
* **Value Range:** Each octet ranges from 0 to 255.
* **Total Addresses:** Approximately 4.29 billion ($2^{32}$).



---

### 2. IPv6 (Internet Protocol version 6)
IPv6 was developed to replace IPv4, offering a significantly larger address space and built-in security features like IPsec.

* **Structure:** A 128-bit address displayed in **hexadecimal**.
* **Format:** Eight groups of four hexadecimal digits (hextets) separated by colons (e.g., `2001:0db8:85a3:0000:0000:8a2e:0370:7334`).
* **Abbreviation Rules:** 1.  Leading zeros in a group can be omitted.
    2.  One consecutive section of zeros can be replaced with double colons (`::`).
* **Total Addresses:** Approximately $3.4 \times 10^{38}$ (340 undecillion).

---

### 3. Key IP Configurations
To communicate on a network, a device needs more than just an IP address. The following components are essential:

| Component | Function |
| :--- | :--- |
| **Subnet Mask** | Distinguishes which part of the IP address identifies the **network** and which part identifies the **host**. |
| **Default Gateway** | The "exit point" (usually a router) that allows a device to communicate with devices outside its local subnet. |
| **DNS Server** | Resolves human-readable domain names (e.g., google.com) into IP addresses. |



---

### 4. Address Assignment Methods
Devices can receive IP addresses in two primary ways:

* **Static IP:** Manually assigned by an administrator. The address never changes. Ideal for servers and printers.
* **Dynamic IP:** Automatically assigned by a **DHCP (Dynamic Host Configuration Protocol)** server. This is the standard for most workstations and mobile devices.
* **APIPA (Automatic Private IP Addressing):** If a device cannot reach a DHCP server, Windows assigns an APIPA address. 
    * **Range:** `169.254.0.1` through `169.254.255.254`.
    * **Limitation:** Only allows communication with other devices on the same local subnet.

---

### 5. Logical vs. Physical Addressing
It is crucial to distinguish between the two types of addresses used in networking:
* **MAC Address (Physical):** Burned into the Network Interface Card (NIC). It is the "permanent" hardware ID.
* **IP Address (Logical):** Assigned by software. It changes based on the network location of the device.

Source: https://www.youtube.com/watch?v=RRFjKXxYJdM&list=PLG49S3nxzAnnes8ZGI-OBlKEukHCX46N8&index=7
