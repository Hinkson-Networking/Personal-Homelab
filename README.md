Welcome to my homelab documentation repo.
This repository is a living record of my homelab journey — from hardware builds and upgrades to networking diagrams, service deployments, and personal notes.

The homelab serves both as a sandbox for learning cybersecurity and networking and a playground for tinkering with hardware, virtualization, and storage.


---

Goals of This Repo

Document each node in the homelab with hardware specs, photos, and configurations

Keep history logs of upgrades, swaps, and experiments

Share wins, failures, and lessons learned (update journal)

Provide reproducible setups for anyone following along

Track the growth of the lab over months and years



---

Repo Structure

.
├── alpha/        # Workstation + VM testing
├── bravo/        # Firewall, security services
├── charlie/      # Storage server
├── delta/        # Entertainment server
├── echo/         # Test bench / emulation
├── foxtrot/      # Productivity laptop
├── gamma/        # Gaming laptop
├── network/      # Switches, patch panels, peripherals
├── journals/     # Update logs and history
└── README.md     # You are here


---

Current Nodes

Alpha – Ryzen 9 powerhouse for testing, dual-boot Arch + Windows

Bravo – Proxmox VM for firewall and network security

Charlie – Storage and backup server

Delta – Entertainment (Plex, Jellyfin, Minecraft, etc.)

Echo – AM4 test bench for experiments and emulation

Foxtrot – Productivity and college laptop

Gamma – Gaming workhorse laptop


Each node has its own folder with detailed specs, history, and photos.


---

Journals

The journals directory contains dated records of hardware changes, upgrades, and experiments.
This serves as a lab notebook documenting the evolution of the setup.


---

Technologies in Use

Virtualization: Proxmox, and VirtualBox

Storage: SMB/NFS shares, RAID configurations

Networking: VLANs, firewall rules, switch configs

Operating Systems: Arch Linux, Windows, Linux Mint, TrueNas Scale
