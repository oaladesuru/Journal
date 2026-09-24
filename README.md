# Journal

## Week 1
### Tutorial Tasks Completed
- Created GitHub account
- Created GitHub Repository
### Screenshots / Command Outputs
-![GitHub account creation](https://github.com/oaladesuru/Journal/blob/main/Screenshot%202026-09-09%20164747.png?raw=true)
### Notes & Explanations
- Created GitHub account for journal entries as well as other projects and assignments. Proof ^^
### Project Contributions
- N/A, group for project has not been formed yet.

## Week 2
### Tutorial Tasks Completed
## 09/09/2026:
- Tutorial 1 - Powershell
### Screenshots / Command Outputs
- ![Tutorial1](https://github.com/oaladesuru/Journal/blob/main/Screenshot%202026-09-09%20151702.png?raw=true)
-![VirtualBox Installation](https://github.com/oaladesuru/Journal/blob/main/Screenshot%202026-09-09%20164144.png?raw=true)
### Notes & Explanations
- The boot manager is the small program that runs before the operating system and decides wgicg OS or kernal to load. In OpenWRT running inside VirtualBox, the boot manager is GRUB.
- I found this by starting the VM, watching the first screen that appeared, and checking the text at the top which showed "GRUB" during startup. I installed everything through Windows CMD rather than [...]
- Kernal is the part of the operating system that manages hardware, memory, processes, and networking. OpenWRT uses a Linux Kernel, and I found the kernel version by running the command "uname -a" wit[...]
### Project Contributions
- N/A, group for project has not been formed yet.

## Week 3
### Tutorial Tasks Completed
09/14/2026
- Task 1
-   I ran an Internet speed test check my internet performance. The results depend on things like my ISP, network congestion, Wi-Fi strength, distance to the server, and time of day.
- Task 2
-   I looked at many network maps to understand how global internet is connected and how traffic moves between countries and ISPs.
- Task 3
-   I used certain Get-NetAdapter to view my network adapter details.
- Task 4
-   I used Get-NetIPConfiguration and Get-NetIPAddress to see my computer's IP settings and my router's gateway address.
- Task 5
-   I found my router's IP address and pinged it to measure minimum, average, and maximum delay. I noticed how things like Wi-fi interference, distance, and network load could affect the delay.
- Task 6
-   I picked a website and used DNS tools to get its addressing information.
### Screenshots / Command Outputs
- ![SpeedTest](https://github.com/oaladesuru/Journal/blob/main/images/Screenshot%202026-09-14%20151956.png?raw=true)
- ![NetworkMaps](https://github.com/oaladesuru/Journal/blob/main/Screenshot%202026-09-14%20163434.png?raw=true)
- ![AdapterDetails](https://github.com/oaladesuru/Journal/blob/main/Screenshot%202026-09-14%20163036.png?raw=true)
- ![IPSettings](https://github.com/oaladesuru/Journal/blob/main/Screenshot%202026-09-14%20152315.png?raw=true)
- ![Ping](https://github.com/oaladesuru/Journal/blob/main/Screenshot%202026-09-14%20164607.png?raw=true)
- ![Website](https://github.com/oaladesuru/Journal/blob/main/Screenshot%202026-09-14%20163043.png?raw=true)

### Notes & Explanations
...
### Project Contributions
- N/A, group for project has not been formed yet.

## Week 4–10 (Final Journal)
### Tutorial Tasks Completed
## 09/21/2026
- Used PowerShell to view ARP Table

### Diagram / Network Topology
- [blank.drawio](https://github.com/oaladesuru/Journal/blob/main/blank.drawio)
- [Open diagram in diagrams.net](https://app.diagrams.net/?splash=0&url=https://raw.githubusercontent.com/oaladesuru/Journal/main/blank.drawio)

### Screenshots / Command Outputs
![GetNetNeighbor](https://github.com/oaladesuru/Journal/blob/main/Screenshot%202026-09-21%20153200.png?raw=true)
![Diagram](https://github.com/oaladesuru/Journal/blob/main/Screenshot%202026-09-24%20113540.png?raw=true)
### Notes & Explanations
- The purpose of ARP packets are to map an IPv4 address to a MAC address so devices on the same LAN can deliver frams to the correct machine.
- From the screenshot of the ARP table, only one entry is reachable: 00-00-5E-00-01-09. It is not a single computer, it is a multicast group.
- The network diagram shows two switched LAN designs. The first design connects four PCs to one central switch, while the second uses a star topology with eight PCs connected through three switches. This demonstrates how switches allow devices on the same LAN to communicate efficiently.
### Project Contributions
