# Homelab

## Introduction
This repository is the central hub for the documentation of my homelab.

At first attracted by this as a hobby experiment and a way of better protecting my privacy, now it has turned into a place to learn new technologies and develop my sysadmin and DevOps skills. Here I can tinker with Docker, VMs, Kubernetes, and the like freely, always trying to increase the security and the ease of maintenance of the whole infrastructure.
## Architecture
Currently, I use a bare metal installation of [Ubuntu Server 24.04 LTS](https://ubuntu.com/server) to host my containers. I first choose this set up because it had great community support, but I will be moving everything over to various VMs in [Proxmox](https://proxmox.com/en/) very soon. This new environment will give me more flexibility and a greater ability to separate tests from stable deployments.
## Hardware
At the moment, my homelab equipment consists only of a single Samsung laptop. It's enough for now, but I'm looking to expand when I can.
- Samsung Galaxy Book 3, i7-1355U/16GB RAM/512GB SSD
## Self-hosted Apps
#### Second Brain

| Logo                                                                                        | Name                                              | Description                                   |
| ------------------------------------------------------------------------------------------- | ------------------------------------------------- | --------------------------------------------- |
| ![](./images/37freshrss.png) | [FreshRSS](https://freshrss.org/)                 | Feature-rich RSS feed reader                  |
| ![](./images/35karakeep.png) | [Karakeep](https://karakeep.app/)                 | Bookmarking solution for hoarding information |
| ![](./images/37yamtrack.png) | [Yamtrack](https://github.com/FuzzyGrim/Yamtrack) | Media tracking platform                       |

#### Tools

| Logo                                                                                        | Name                                 | Description                      |
| ------------------------------------------------------------------------------------------- | ------------------------------------ | -------------------------------- |
| ![](./images/33homepage.png) | [Homepage](https://gethomepage.dev/) | General dashboard for my homelab |

## Infrastructure
The digital structure that sustains my homelab.
### Networking

| Logo                      | Name                                   | Description                                                                                                                                                      |
| ------------------------- | -------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](./images/pi-hole.png) | [Pi-Hole](https://pi-hole.net/)        | DNS server for internal domain resolution                                                                                                                        |
| ![](./images/traefik.png) | [Traefik](https://traefik.io/traefik/) | Reverse proxy with dynamic and static configurations that secure the traffic of my internal networks with [Let’s Encrypt](https://letsencrypt.org/) certificates |

### Blog

| Logo | Name | Description |
| ---- | ---- | ----------- |
|      |      |             |
|      |      |             |

