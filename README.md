<div align="center">

# hello, friend. 👋

*"You are being watched."* — but don't worry, it's just me running nmap on my own lab.

</div>

```bash
tahito@kali:~$ whoami
taha benkacem // 2nd year CS engineering @ UIR, Rabat 🇲🇦
tahito@kali:~$ cat /etc/motd
breaking things to see how they work. writing it down so I remember next time.
tahito@kali:~$ echo $STATUS
looking for a cybersecurity internship for summer 2027 (pentest / appsec / iot)
```

---

### 🕵️ stuff I've been up to

- **CTFs.** Web, reversing, stego, crypto. Every flag gets a write-up, including the dumb rabbit holes → [ctf-writeups](https://github.com/TahaXploit/ctf-writeups)
- **Pwning a 50 dh camera.** Bought a cheap "A9" Wi-Fi cam to self-host it, ended up investigating it instead. Zero open ports, lwIP stack, and it happily shouts its UID, serial number and admin username across the LAN in cleartext UDP. Opened it up next to hunt for UART. *Write-up loading...*
- **Bug bounty.** subfinder → httpx → nuclei → ffuf → Burp, then a lot of staring. Building my own human-in-the-loop workflow for YesWeHack: scope notes, findings journal, report templates. No bounties yet, just vibes and recon.
- **Homelab.** An old HP laptop running Debian and a pile of Docker containers, reachable only through Tailscale. It's where I self-host my own apps and where ARP spoofing / MITM experiments are legally allowed (it's my network, I asked myself).
- **Building random things.** "Hub", a SwiftUI iPhone app for all my self-hosted services. An ESP8266 + DHT22 dashboard that pipes data to the server over USB. A solar-powered ESP8266 node reading soil sensors over RS485, on a PCB I designed myself.

### 📚 what uni is throwing at me (semester 3)

- **Networks:** TCP/IP, subnetting, routing & switching
- **Operating systems:** processes, scheduling, syscalls, `fork()`/`exec()`/`wait()` in C, rewrote my own `ls`, `grep`/`sed` regex pain
- **Databases:** ER modeling, relational algebra, joins, MySQL. Yes, I know what `' OR 1=1 --` does. No, not on your site.
- **Analog electronics:** diodes, PN junctions, transistors. Somehow harder than reversing.

### 🧰 the toolbox

```
offense    burp · nmap · metasploit · ffuf · nuclei · hydra · john · bettercap · ghidra
packets    wireshark · tcpdump · scapy · binwalk · zsteg
code       python · c/c++ · bash · sql · js/ts · swift
systems    kali · debian · docker · tailscale · git
hardware   esp8266/esp32 · arduino · lora · rs485 · uart · i2c · nrf24 · easyeda
```

### 🎯 leveling up

- [x] TryHackMe Pre-Security & Cyber Security 101 → [profile](https://tryhackme.com/p/tahito)
- [ ] TryHackMe Jr Penetration Tester (almost there)
- [ ] Cisco **CCNA** (in progress)
- [ ] HTB Academy grind
- [ ] **HTB CPTS** (next boss)

---

<div align="center">

📫 [LinkedIn](https://www.linkedin.com/in/taha-benkacem-18665b279/) · taha.benkacem@uir.ac.ma

*"Control is an illusion."* — still trying to prove that wrong with a root shell.

</div>
