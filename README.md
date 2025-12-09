# LLAMBO OS  
**Status: Pre-Alpha — Under Active Development**

**LLAMBO OS** is a modern FreeBSD-based operating system designed for self-hosting, privacy, and sovereign computing.

Built for both casual users and power operators, LLAMBO OS aims to make it effortless to deploy blockchain nodes and self-hosted services on secure, stable hardware — all managed from the upcoming **Llambo Dashboard**.

This repository is the early development fork of FreeBSD that will become the LLAMBO OS foundation.  
Features described below represent our **roadmap**, not the current state.

---

## 🚀 Core Mission

LLAMBO OS aims to:

- Provide a **plug-and-play alternative** to Linux-based platforms like Umbrel, Start9, and YunoHost  
- Enable users to **run full blockchain nodes** and related services with no command-line interaction  
- Deliver a **modular App Store** powered by FreeBSD jails for isolation and security  
- Offer an experience that feels **Apple-simple**, while staying fully self-hosted and auditable  
- Ship with the **Llambo Dashboard**, accessible at `https://llambo.local` on first boot  
- Provide a stable, hardened operating system suitable for consumer devices and professional node operators  

---

## 🧱 Built for Node Operators, Builders, and Homelabbers

LLAMBO OS is being designed to support:

### 🧩 Blockchain & Web3 Nodes (Planned)

- Bitcoin Core  
- Lightning Network (LND / Core Lightning)  
- Monero  
- Ethereum (Geth, Erigon, Nethermind)  
- IPFS / Filecoin  
- Nostr relays  
- Electrs / Fulcrum / Specter  
- BTCPay Server  
- Additional ecosystem RPC and indexing apps  

### ⚙️ Core Self-Hosting Apps (Planned)

- Nextcloud  
- Home Assistant  
- Pi-hole  
- Gitea  
- WireGuard  
- Jellyfin  
- Syncthing  
- SearxNG, Invidious, and more  

All apps will run in **FreeBSD jails**, with ZFS datasets, sandboxed networks, and per-app firewall rules.

---

## 💡 Why LLAMBO OS?

| Feature                     | LLAMBO OS (planned)                    
|-----------------------------|---------------------------------------
| Base OS                     | **FreeBSD** (ZFS, PF, jails)          
| Isolation model             | Native jails                          
| Filesystem                  | **ZFS snapshots, rollback**           
| Security                    | PF firewall + jail isolation          
| HTTPS out of the box        | Caddy w/ internal CA                  
| UI                          | Llambo Dashboard                      
| App system                  | YAML-based jail apps                  
| Blockchain focus            | **Core mission**                      

Our goal is to offer a **more stable**, **more secure**, and **more flexible** platform for running blockchain nodes and sovereign services.

---

## 🖥️ Hardware Targets (Initial Goals)

- Raspberry Pi 4 / ARM SBCs  
- x86 mini-PCs (NUC, Protectli, LibreBox, etc.)  
- Dedicated LLAMBO hardware (future product line)  
- Virtual machines and cloud environments  

---

## 📦 Planned Features

- Preinstalled **Llambo Dashboard** served by Caddy  
- Local HTTPS with automatic certificates  
- App Store for installing blockchain nodes and self-hosted apps  
- PF firewall hardening  
- mDNS discovery (`llambo.local`)  
- Built-in jail manager  
- OTA updates through LLAMBO Update Service  
- Fully reproducible builds via FreeBSD source tree  

As a pre-alpha project, these components are in active design and development.

---

## 🧠 Philosophy

LLAMBO OS is about **sovereign computing made simple**.

You own the hardware.  
You run the software.  
You choose the apps.  
You keep control of your data and your money.

---

## 🧪 Project Status

LLAMBO OS is currently in **pre-alpha**.  
We are:

- Forking and preparing the FreeBSD base system  
- Designing the Llambo Dashboard  
- Building the App Store architecture  
- Preparing build tooling and image pipelines  
- Developing node templates and jail orchestration  

Early contributors and testers are welcome.

---

## 🛠️ Development

To sync with upstream FreeBSD:

```sh
git remote add upstream https://git.freebsd.org/src.git
git fetch upstream
git rebase upstream/main
````

Build instructions will be added as components become functional.

---

## 📫 Follow Development

Repository: [https://github.com/TheVoice-dev/llambo-os-src](https://github.com/TheVoice-dev/llambo-os-src)
More documentation, images, and tools will be published as the project matures.
