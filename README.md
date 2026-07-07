# Secure-Multi-Site-Campus-Area-Network-Cisco-Packet-Tracer-
<img width="3824" height="2818" alt="schm" src="https://github.com/user-attachments/assets/87aae7ed-deb0-4493-a459-6862a5e3c4ca" />


I recently designed and deployed a full enterprise-grade campus network connecting a Headquarters and a Branch site over a site-to-site IPSec VPN — built to reflect real-world NOC and network security engineering practices.
Key components:
🔹 Dual Cisco ASA firewalls with NAT, security-level zoning (INSIDE/OUTSIDE/DMZ), and ACL-based traffic inspection policies
🔹 Redundant Multilayer Switches with HSRP for gateway failover and LACP EtherChannel for link redundancy
🔹 OSPF dynamic routing across HQ, Branch, ISPs, and firewalls for full end-to-end connectivity
🔹 VLAN segmentation (Management, LAN, WLAN, Backbone) across five departments per site, with DHCP relay (helper-address) to centralized DHCP services
🔹 DMZ server farm (Web, DNS, Email, FTP) isolated from internal networks
🔹 Hardened switch/router access: SSH-only management, standard ACLs restricting VTY access, password encryption, and banner warnings
🔹 Spanning-Tree security (PortFast + BPDU Guard) to protect against Layer 2 attacks
This project let me apply core principles I'm building toward in cybersecurity and infrastructure engineering — secure design, redundancy, segmentation, and least-privilege access control — end to end, from Layer 2 up through routing and perimeter security.
Currently continuing my path toward NOC Engineering and cybersecurity, including ISC2 CC certification and hands-on PKI/HSM work.
