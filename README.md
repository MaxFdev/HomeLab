# HomeLab

![Cover](HomeLab.png)

## Overview HW

My home lab is comprised of 2 primary hardware components:

1. ARM-based SBC
    - CPU: Cortex A53
    - RAM: 2GB
    - NET: 1Gbit
    - OS: Ubuntu
2. PC Server
    - CPU: Ryzen 2700
    - RAM: 16GB
    - NET: 1Gbit
    - OS: Proxmox

## Overview SW

The software varies depending on what I am working on, here are some of the parts:

1. Cloudflare
    - DNS
    - Site Hosting
    - Security
    - Auth (Through Google)
    - VPN / Tunnels
2. Ubuntu
    - Cloudflared (Local Tunnel)
    - Bash Control Script (For WOL)
3. Proxmox
    - VMs
        - Kali Linux
        - Ubuntu (School)
    - LXC
        - Nextcloud
        - Coding Server (Remote VSC & Cloudflared)
        - Ubuntu (Ngrok routing & game control panel)
        - Turnkey Game Server
    - ZFS (Storage pool)

---

WIP...
