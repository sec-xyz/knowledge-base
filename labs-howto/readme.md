# Use Virtual Machines (VMs) to connect to labs, CTFs and trainings

## Hypervisor options
1. VirtualBox
2. VMware

## Networking notes
If your guest uses a bridged interface with host wifi card, it may not work.
Solutions
- choose NAT interface instead.
- or use a LAN/USB card on the Host and keep bridge mode

## Advanced scenarios
To connect to HTB, TryHackMe, CTFs or training you can use a diferent setup.
1. Create a VM with a firewall (FW) distro such as IPFire or pfSense
2. Add 3 interfaces on the FW distro (WAN, LAN, Host only)
3. Create another VM (aka attack box) with [Parrot OS](https://www.parrotsec.org/) or [Kali Linux](https://www.kali.org/)
4. Add one interface connected internal network (LAN)


WAN - connected to outside world
LAN - connected internal network
Host only - interface connected with Host where VMWare and VirtualBox runs
