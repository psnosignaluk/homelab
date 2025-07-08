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
- [ ] 1 x 5m Cat6 RJ45 network cable
- [ ] 2 x 3m Cat6 RJ45 network cables

Given the size of our flat, running a 5m Cat6 cable from the ISP router downstairs to the
Dream Router upstairs should provide a 1Gbps connection to a router that only supports
512Mbps to the Internet. I can run cables to my Xbox and a Minisforum mini PC, and connect
our Macbooks to the Dream Router AP. Downstairs where the Apple TV lives and our phones
are typically used, getting anything over 100Mbps via the WiFi would be perfectly fine.

## Desktop + Gaming

I'd love an AM5 desktop and a shiny new GPU, but frankly shat myself when looking at the 
cost of bringing my AM4 machine up to AM5 spec. So instead:

- [ ] Minisforum AI X1 Pro AMD Ryzen AI 9 HX 370 w/ 32GB RAM and a 1TB SSD
- [ ] Asus ROG Strix XG32UQ 4K monitor
- [ ] Wooting 60HE+ keyboard
- [x] Logitech G Superlight Pro mouse
- [ ] Razer Kiara Pro headset
- [x] Xbox Series X
- [x] Xbox Elite Series 2 controller
- [ ] Ikea Trotten desk
- [ ] WD Black SN850X 2TB SSD M.2 2280 NVME PCI-E Gen4 Solid State Drive

The SN850X will be used to run Ubuntu Desktop which will be my development machine. No
games, so no need for Windows. The provided NVME can go in a box.

## Erm, the "homelab" part?

This **is** a *homelab*. The X1 Pro is 100% homelab, especially when LXD containers are
leveraged to run platforms such as MicroK8s, to experiment with databases, services such
as Nginx and more importantly, to test applications for their resilience.