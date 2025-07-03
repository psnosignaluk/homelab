# Homelab

The current state of my home compute and network environment is shocking. It consists of fibre
running from outside of the flat to a router provided by my ISP that supplies connectivity via
Wi-Fi to all of the connected devices that we own. I also make use of instances via AWS for 
any machines that I want to run, which is conventient, until you consider that a 4 vCPU / 
16GB RAM / 30GB `t3.xlarge` instance costs £142.00 per month.

The objective then is to build a proper network, deploy some computers and start working on
my craft from the comfort of a secure(ish) home network.

## Kit

The following is a list of the kit that I want to obtain for this:

- [ ] 1 x UniFi Cloud Gateway Ultra
- [ ] 1 x UniFi Lite 8 PoE 8 port switch
- [ ] 2 x UniFi U6 Mesh
- [ ] 3 x GEEKOM A8 Max Mini PCs with AMD Ryzen 9 8945HS CPUs
- [ ] A KVM switch to meet my needs (dual monitor support across 2 x PCs)

## Network

UniFi gear isn't the cheapest, but it's easy enough to put own a small network that can grow
over time. I doubt that 2 x UniFi U6 Mesh APs are strictly needed, but the flat is a weird combo
of concrete and dry wall that separates the half of the flat where the UniFi kit and home office
are from the "living" area of the flat where the entertainment systems are. I'd rather eat
the cost and overprovision from the get go on this.

## Computers

I'll be buying the base GEEKOM A8 Max Mini PCs, so that'll be a grand total of 24 cores, 48 threads,
96GB RAM and 6TB worth of storage. One machine will go to my wife so that she can move back to
using Windows, and I'll run two of these for myself, one with Windows 11 Pro and the other as an
Ubuntu desktop. Another few would be added down the road to act as a small server cluster for
Kubernetes shenanigans.