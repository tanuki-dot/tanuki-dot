

![header](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&pause=1000&color=FABD2F&center=false&width=640&lines=firmware+tinkerer+%26+embedded+maker;libreboot+survivor%2C+SPI-flash+whisperer;low-level+recovery%2C+networks%2C+:3)

### Hi, I'm Tanuki

Student and hardware maker, happiest close to the metal: firmware, embedded, networks, and Linux I've taken apart more times than is reasonable. Everything here is self-driven. If it has an SPI flash or a config file I can ruin at 2am, I'm interested.

---

### What I do

- **Firmware / boot**: Libreboot / coreboot, Intel ME neutralization, SPI flashing, Qualcomm EDL
- **Security / networks**: firewalld / nftables, VLAN segmentation, MAC randomization, incident analysis, home-lab honeypot
- **Embedded**: ESP32, Arduino, Raspberry Pi, soldering, 3D printing
- **Linux**: Void & Debian, LUKS, sysadmin, and too much ricing

---

### Tech

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Void](https://img.shields.io/badge/Void-478061?style=flat&logo=linux&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/RPi-A22846?style=flat&logo=raspberry-pi&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat&logo=kicad&logoColor=white)

---

### Selected work

<sub>Self-driven. Repos and writeups in progress; happy to walk through any of these.</sub>

- **Libreboot on a ThinkPad T60** internal bucts flash, then external SPI rescue over a Pi Pico after root-causing an ICH7M bus-contention failure.
- **Qualcomm EDL recovery (Xiaomi POCO M3)**  forced EDL via testpoints, flashed the boot chain with a firehose programmer; traced the remaining failure to a dying UFS chip.
- **Discord token-stealer incident**  analyzed a real infection end to end; showed how a stolen session token bypasses 2FA, then rotated, invalidated and cleaned up.
- **Monolith microSD recovery**  worked from kernel logs down to decapping the card; ruled it unrecoverable at the controller level.
- **Debian network hardening**  firewalld DROP zone, SSH vector removed, per-network MAC randomization.
- **Earlier builds**  microcontroller temp/humidity monitor; older laptop revived with SSD, RAM, Linux and LUKS.


![profile views](https://komarev.com/ghpvc/?username=tanuki-dot&color=fabd2f&style=flat&label=profile+views)


