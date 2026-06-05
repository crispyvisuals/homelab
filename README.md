# Homelab Server Rack Project

A hands-on infrastructure project where I built a compact homelab server from a used Dell OptiPlex 5070 Micro, upgraded the storage, installed a Linux server environment, designed custom 3D-printed rack components, and added live system monitoring through an external LCD display.

This project helped me practice hardware troubleshooting, Linux server setup, basic networking, 3D design, documentation, and iterative problem-solving.

---

## Project Summary

The goal of this project was to build a small, organized, and functional homelab that I could use for future self-hosted services, AI tools, networking experiments, and server administration practice.

Instead of only setting up software, I also designed and assembled a physical rack-style enclosure using 3D-printed parts. The build required me to source hardware, troubleshoot compatibility issues, install server software, create mounts, and document the full progression from planning to completion.

---

## Why I Built This

I wanted a real environment where I could learn by doing. A homelab gives me a place to experiment with Linux, networking, virtualization, self-hosted applications, AI tools, monitoring dashboards, and automation without relying on cloud services.

This project also gave me experience working through real technical problems, such as incorrect parts, failed print dimensions, hardware fitting issues, and software setup challenges.

---

## Skills Demonstrated

- Linux server installation and configuration
- Hardware upgrades and troubleshooting
- Storage installation using SSD and HDD drives
- Basic networking with an Ethernet switch
- 3D modeling and iterative prototyping
- Rack/enclosure design and assembly
- System monitoring with Glances
- Project planning and documentation
- Problem-solving through build mistakes and design revisions

---

## Hardware

| Component | Details |
|---|---|
| Server | Dell OptiPlex 5070 Micro |
| CPU | Intel Core i7-9700T |
| Memory | 8GB RAM |
| Primary Storage | Western Digital WD_BLACK 500GB M.2 NVMe SSD |
| Secondary Storage | Western Digital 640GB 2.5-inch SATA HDD |
| Network | TP-Link 5-Port Gigabit Ethernet Switch |
| Display | 7-inch LCD monitor for live monitoring |
| Enclosure | Custom 3D-printed rack, mounts, handles, and Ethernet port mount |

---

## Software

### Installed

| Software | Purpose |
|---|---|
| Ubuntu Server | Main operating system for the homelab |
| CasaOS | Web-based dashboard for managing self-hosted apps |
| Glances | System monitoring for CPU, memory, disk, and network activity |

### Planned / Future Services

| Tool | Planned Use |
|---|---|
| Proxmox | Virtualization and container management |
| Ollama | Local AI model hosting |
| Pi-hole | Network-wide ad blocking and DNS filtering |

---

## Completed Goals

- [x] Acquired Dell OptiPlex 5070 Micro
- [x] Installed HDD storage
- [x] Installed M.2 NVMe SSD storage
- [x] Installed Ubuntu Server
- [x] Installed CasaOS
- [x] Designed and printed computer mount
- [x] Designed and printed Ethernet switch mount
- [x] Designed and printed handles
- [x] Created custom 3D rack enclosure
- [x] Created LCD monitor mount
- [x] Mounted hardware onto the rack
- [x] Installed monitoring tools
- [x] Displayed live system monitoring on LCD screen

---

## Build Timeline

### Week 1 — Planning and Hardware Sourcing  
**February 9, 2026**

- Acquired a Dell OptiPlex 5070 Micro with no storage.
- Searched Facebook Marketplace for affordable storage options.
- Purchased a used 640GB HDD for about $10.
- Installed the HDD into the OptiPlex.
- Ordered a TP-Link Ethernet switch, 7-inch LCD display, and SSD.
- Started sketching the layout for the rack-style enclosure.

**What I learned:** Budget hardware sourcing is useful, but compatibility must be checked carefully before ordering parts.

---

### Week 2 — 3D Modeling and First Prints  
**February 16, 2026**

- Learned the basics of creating 3D models for physical mounts.
- Began printing parts through campus/library 3D printing resources.
- Completed the first computer mount and Ethernet switch mount.
- Received the LCD screen and SSD.
- Realized the SSD I ordered was the wrong type.
- Ordered the correct SSD and continued improving the rack design.
- Printed the rack handles.

**What I learned:** Designing physical parts requires accurate measurements and patience. Small measurement errors can affect the entire build.

---

### Week 3 — Storage Upgrade and Server Setup  
**February 23, 2026**

- Received the correct SSD.
- Sold the incorrect SSD.
- Installed the new SSD into the OptiPlex.
- Began setting up the server operating system.
- Installed Ubuntu Server and CasaOS.
- Started exploring ideas for a local AI assistant inspired by Jarvis from Iron Man.
- Discovered that the LCD monitor mount dimensions needed revision.

**What I learned:** Hardware and software setup often happen together. A build can be physically functional while still needing design improvements.

---

### Week 4 — Rack Redesign  
**March 2, 2026**

- Prepared the larger rack print.
- Learned that the rack needed to be separated into smaller parts before printing.
- Rebuilt the rack design after finding mistakes in the original model.
- Submitted the revised parts for printing.

**What I learned:** Large 3D prints need to be designed with printer limits, assembly, and structural support in mind.

---

### Week 5 — Assembly and Monitoring  
**March 9, 2026**

- Received the printed rack parts.
- Found that some connector pieces did not print correctly.
- Reprinted and adjusted connector pieces as needed.
- Assembled the rack using superglue and manual fitting.
- Installed Glances for live server monitoring.
- Connected the LCD monitor to display system statistics.
- Finished the first complete version of the homelab rack.

**What I learned:** A finished project does not always mean everything worked perfectly on the first try. I had to adapt, redesign, and find practical solutions to finish the build.

---

## Challenges and Solutions

| Challenge | Solution |
|---|---|
| Ordered the wrong SSD | Researched the correct storage type, purchased the right SSD, and resold the incorrect one |
| LCD mount did not fit correctly | Adjusted the physical setup and used the available space creatively to keep the display functional |
| Rack parts were too large to print as one piece | Split the rack into smaller printable sections and rebuilt the structure after printing |
| Connector pieces failed during printing | Reprinted parts and manually attached pieces during assembly |
| Needed live system visibility | Installed Glances and displayed server stats on the external LCD |

---

## Final Result

By the end of the project, I built a working mini homelab server with upgraded storage, Ubuntu Server, CasaOS, live monitoring, and a custom 3D-printed rack enclosure. The project is now ready for future services such as virtualization, local AI models, DNS filtering, and self-hosted applications.

This project shows my ability to take an idea from planning to completion, learn new tools independently, troubleshoot mistakes, and document technical work in a way that others can follow.

---

## Next Steps

- Install and configure Proxmox for virtualization.
- Set up Ollama for local AI experimentation.
- Deploy Pi-hole for DNS filtering.
- Add Docker-based self-hosted services.
- Improve cable management.
- Redesign the LCD mount for a cleaner final fit.
- Add diagrams showing the network and server layout.


## Progression Photos

### Week 1 — Initial Design Sketch

<img width="450" height="450" alt="Initial rack design sketch" src="https://github.com/user-attachments/assets/d763b0f3-a8a6-49f7-ba55-15189bd6d543" />

---

### Week 2 — Early 3D Prints and Mounts

<img src="https://github.com/user-attachments/assets/1608aca6-db3c-4377-8b76-fe718e11cb12" width="300" height="300" alt="3D printed mount progress" />
<img src="https://github.com/user-attachments/assets/e522143b-0464-4113-9231-724f28ae6e6e" width="300" height="300" alt="3D printed rack component" />

---

### Week 3 — Hardware Setup

<img src="https://github.com/user-attachments/assets/dca917a4-57e2-4575-91cc-37bc31fdc090" width="300" height="300" alt="OptiPlex hardware setup" />
<img src="https://github.com/user-attachments/assets/9769b069-3a25-4af2-bda9-8471900709f0" width="300" height="300" alt="Server setup progress" />

---

### Week 5 — Completed Build

<img src="https://github.com/user-attachments/assets/f8f1f3f5-dc6a-4965-a794-b5da36797ea8" width="300" height="300" alt="Completed homelab rack build" />

---

## Summary

Built a compact Linux homelab using a Dell OptiPlex 5070 Micro, upgraded it with SSD and HDD storage, installed Ubuntu Server and CasaOS, designed custom 3D-printed rack components, and configured live system monitoring through a 7-inch LCD display. The project demonstrates hands-on experience with Linux, hardware upgrades, networking, 3D printing, troubleshooting, and technical documentation.


  
