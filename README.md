# Homelab

The current state of my home compute and network environment is shocking. It consists of fibre
running from outside of the flat to a router provided by my ISP that supplies connectivity via
Wi-Fi to all of the connected devices that we own. I also make use of instances via AWS for 
any machines that I want to run, which is conventient, until you consider that a 4 vCPU / 
16GB RAM / 30GB `t3.xlarge` instance costs £142.00 per month.

The objective then is to build a proper network, deploy some computers and start working on
my craft from the comfort of a secure(ish) home network.

## Network

The following is a list of the kit that I want to obtain for a decent home network:

- [ ] 1 x UniFi Dream Router 7
- [ ] 1 x UniFi U7 Light
- [ ] 1 x 3m Cat6 RJ45 network cable
- [ ] 1 x 15m Cat6 RJ45 network cable

## Desktop

I wanted something that would work as a desktop and as a 1440p gaming set up. The overall
objective is to run Windows 11 Pro as the base OS, with VirtualBox enabling access to Linux/BSD
machines for the purpose of running tools native to that OS. What I came up with is:

- [ ] AMD Ryzen 7 9800X3D CPU (excellent for games, robust day-to-day CPU)
- [ ] EK Water Blocks EK-Nucleus AIO CR360 AIO (no fucking RGB)
- [ ] MSI MPG X870E Carbon WiFi motherboard (good power delivery, dual LAN, plenty M.2 interfaces)
- [ ] WD Black SN8100 2TB M.2 2280 NVME PCIe 5.0 SSD (Windows, page file, games)
- [ ] WD Black SN850X 2TB M.2 2280 NVME PCIe 4.0 SSD (VirtualBox, VMs)
- [ ] Sapphire Nitro + Radeon RX 9070 XT 16GB DDR6 GPU
- [ ] Asus ROG Strix 1200w Platinum 80 Plus ATX 3.1 PSU (future expandability)
- [ ] MSI MAG 274QRFW 2560x1440 180Mhz IPS monitor
- [ ] Wooting 60HE+ keyboard
- [ ] Another office desk

As AM5 reaches deprecation in 2027, I'd look to plop a more powerful CPU and potentially double the
RAM to extend things legs well into AMD's new socket format, and focus future upgrades on a GPU for
future gaming support.

## Servers

Jury is out whether these would be SBCs or MiniPCs based off of Ryzen's AI chips to permanently run
Kubernetes clusters, or whether the spin up/spin down mechanism on a desktop would be Good Enough™
for my needs.