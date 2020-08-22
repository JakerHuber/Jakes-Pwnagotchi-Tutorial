# How to Build a Pwnagotchi Step-By-Step
###### Date: 8/22/2020 | Project title: Fake B*tch

![Image of Pwnagotchi](1_pwnagotchi.jpg)

## What is Pwnagotchi?
Pwnagotchi is a handheld digital pet for hacking Wi-Fi that gets smarter as it visits more Wi-Fi networks. Pwnagotchi learns by capturing Wi-Fi messages while their owner takes them for walks. Pwnagotchi is a fun hacking project that can be built with a simple Raspberry Pi Zero. 

## How does it work?
Pwnagotchi is an A2C-based “AI” powered by bettercap that learns from its surrounding WiFi environment in order to maximize the crackable WPA key material it captures (either through passive sniffing or by performing deauthentication and association attacks). This material is collected on disk as PCAP files containing any form of crackable handshake supported by hashcat, including full and half WPA handshakes as well as PMKIDs.

![Image of Materials](2_materials.jpg)

# Materials

- [ ] *OS: Windows 7/8/10 (64 bit)*

- [ ] *Memory: 4 GB RAM*

- [ ] *Storage: 50 GB available space*

- [ ] *Hardware virtualization support (Intel-VT or AMD-V)*
