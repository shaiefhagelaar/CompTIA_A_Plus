For the **CompTIA A+ 220-1201 (Core 1)** exam, "Wireless Technologies" is officially categorized under **Objective 2.2** (whereas Objective 2.1 focuses on Ports and Protocols). The following summary is optimized for the latest exam standards, including the addition of Wi-Fi 7 and the 6 GHz spectrum.

# Summary: Wireless Technologies (CompTIA A+ 220-1201)

Wireless networking allows devices to communicate without physical cabling. This objective covers the evolution of the 802.11 standards, frequency bands, and peripheral wireless technologies.

---

## 1. 802.11 (Wi-Fi) Standards
CompTIA requires you to distinguish between standards based on frequency, speed, and hardware capabilities.

| Standard           | Common Name   | Frequency         | Max Theoretical Speed | Key Features |

| **802.11b**    | - | N/A           | 2.4 GHz           | 11 Mbps               | Oldest widely used standard; prone to interference. |
| **802.11a**    | - | N/A           | 5 GHz             | 54 Mbps               | Not compatible with b/g; shorter range than 2.4 GHz. |
| **802.11g**    | - | N/A           | 2.4 GHz           | 54 Mbps               | Backward compatible with 802.11b. |
| **802.11n**    | **Wi-Fi 4**       | 2.4 & 5 GHz       | 600 Mbps              | Introduced **MIMO** (Multiple Input, Multiple Output). |
| **802.11ac**   | **Wi-Fi 5**       | 5 GHz             | 6.9 Gbps              | Introduced **MU-MIMO**; utilizes wider 80/160 MHz channels. |
| **802.11ax**   | **Wi-Fi 6 / 6E**  | 2.4, 5, 6 GHz     | 9.6 Gbps              | **6E** adds the 6 GHz band; uses **OFDMA** for better efficiency. |
| **802.11be**   | **Wi-Fi 7**       | 2.4, 5, 6 GHz     | 46 Gbps               | **Extreme High Throughput (EHT)**; 320 MHz channels; 4K QAM. |



---

## 2. Wireless Frequencies and Channels
Understanding the trade-off between range and speed is critical for troubleshooting connectivity.

### **2.4 GHz Band**
* **Pros:** Long range; penetrates solid objects (walls) better than higher frequencies.
* **Cons:** Very crowded (interference from microwaves, baby monitors, Bluetooth); only **3 non-overlapping channels** (1, 6, and 11).

### **5 GHz Band**
* **Pros:** Much faster data rates; far less crowded than 2.4 GHz.
* **Cons:** Shorter range; easily absorbed by walls and furniture.

### **6 GHz Band (Wi-Fi 6E/7)**
* **Pros:** Massive amount of new spectrum; essentially no interference from legacy devices; allows for the widest possible channels (up to 320 MHz).
* **Cons:** Very short range; requires the newest hardware.



---

## 3. Key Wireless Technologies & Terminology
* **MIMO (Multiple Input, Multiple Output):** Uses multiple antennas to send/receive more data simultaneously.
* **MU-MIMO (Multi-User MIMO):** Allows an Access Point (AP) to communicate with multiple clients at the same time, reducing "wait times" for devices.
* **Channel Bonding:** Combining two 20 MHz channels into a single 40 MHz (or larger) channel to double the throughput.
* **OFDMA (Orthogonal Frequency-Division Multiple Access):** Used in Wi-Fi 6/7 to divide a channel into smaller sub-channels, allowing the AP to talk to many low-bandwidth devices at once.

---

## 4. Short-Range Wireless Technologies
Beyond Wi-Fi, the exam covers protocols used for peripherals and mobile payments.

* **Bluetooth:** A Personal Area Network (PAN) technology operating on the 2.4 GHz band. Used for headsets, mice, and keyboards. 
    * *Note:* Range is typically ~10 meters for Class 2 devices.
* **RFID (Radio Frequency Identification):** Uses electromagnetic fields to identify and track tags.
    * **Passive Tags:** No battery; powered by the radio energy from the reader.
    * **Active Tags:** Battery-powered; can be read from much further distances.
* **NFC (Near Field Communication):** A subset of RFID designed for secure, very short-range communication (centimeters).
    * *Primary Uses:* Contactless payments (Apple Pay/Google Pay), quick device pairing, and identity badges.

---

## 5. Wireless Troubleshooting Concepts
* **Interference:** Caused by other devices on the same frequency (common on 2.4 GHz).
* **Attenuation:** The natural weakening of a signal as it travels through distance or through obstacles.
* **Overlapping Channels:** Occurs when APs are set to channels that bleed into each other (e.g., using channel 2 instead of 1 or 6).
