<div class="github-widget" data-repo="secdev/awesome-scapy"></div>
## Awesome Scapy [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<p align="center">
  <a href="https://scapy.net/"><img src="https://raw.githubusercontent.com/secdev/scapy/master/doc/scapy_logo.png" width="200" alt="Scapy" /></a>
</p>

A curated list of tools, add-ons, articles or cool exploits using **[Scapy](https://scapy.net)**, the Python-based interactive packet manipulation program & library. 
Feel free to [contribute](https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2Fsecdev%2Fawesome-scapy%2Fedit%2Fmain%2FREADME.md)!

You can also [explore Scapy topics](https://github.com/topics/scapy) on GitHub!



## Tools

*Tools that use Scapy (a lot) or extend it*

Fun
- [pwnagotchi](https://github.com/evilsocket/pwnagotchi) - Your AI pet that hacks WiFI to grow. It's super cute.

DDoS
- [ufonet](https://github.com/epsylon/ufonet) - Create your own botnet to send untraceable DDoS attacks.

Wi-Fi.
- [trackerjacker](https://github.com/calebmadrigal/trackerjacker) - Maps and tracks Wi-Fi networks and devices through raw 802.11 monitoring.
- [wifiphisher](https://github.com/wifiphisher/wifiphisher) - Create rogue access point.

IPv6
- [Chiron](https://github.com/aatlasis/Chiron) - An IPv6 security assessment framework.
- [mitm6](https://github.com/fox-it/mitm6) - Performs MiTM for IPv6.

Measurements
- [mtraceroute](https://github.com/rwhalb/mtraceroute) - Create cool graphs over multiple traceroute analysis.
- [Network Security Toolkit (NST)](https://wiki.networksecuritytoolkit.org/nstwiki/index.php?title=HowTo_Use_The_Scapy:_Multi-Traceroute_-_MTR) - Includes an enhanced version of `mtraceroute` with IP Geolocation and GUI management.
- [netprobify](https://github.com/criteo/netprobify) - Network probing tool crafted for datacenters (but not only). Probing using: TCP, UDP or ICMP.

Protocols
- [Cotopaxi](https://github.com/Samsung/cotopaxi) - Set of tools for security testing of Internet of Things devices using specific network IoT protocols (AMQP, CoAP, DTLS, HTCPCP, KNX, mDNS, MQTT, MQTT-SN, QUIC, RTSP, SSDP) .
- [project-memoria-detector](https://github.com/Forescout/project-memoria-detector) - Determine whether a network device runs a specific embedded TCP/IP stack.
- [routopsy](https://github.com/sensepost/routopsy) - Toolkit to attack DRP & FHRP.
- [TorPylle](https://github.com/cea-sec/TorPylle) - Implementation of the OR (TOR) protocol.

Unit Tests
- [Linux Kernel](https://github.com/torvalds/linux/blob/master/tools/testing/selftests/tc-testing/plugin-lib/scapyPlugin.py) - Linux Traffic Control (tc) testing suite.
- [OpenBSD](https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2Fsearch%3Fq%3Dscapy%2Brepo%253Aopenbsd%252Fsrc%2Bpath%253Aregress%252F%26type%3DCode%26ref%3Dadvsearch%26l%3D%26l%3D) - IPv6 stack testing suite.
- [RIOT-OS](https://github.com/RIOT-OS/RIOT/search?l=Python&q=scapy&type=Code) - RIOT OS networking testing suite.

Visualization
- [Scapy-Packet-Viewer](https://pypi.org/project/scapy-packet-viewer/) - Minimal packet viewer similar to tshark/mitmproxy. Based on urwid.

Misc
- [aioblescan](https://github.com/frawau/aioblescan) - Scan and decode advertised BLE info.
- [fenrir](https://github.com/Orange-Cyberdefense/fenrir-ocd) - Bypass wired 802.1x protection.
- [flowsynth](https://github.com/secureworks/flowsynth) - Tool for rapidly modeling network traffic.
- [Fragscapy](https://github.com/AMOSSYS/Fragscapy) - Fuzz network protocols by automating the modification of outgoing network packets.
- [Habu](https://github.com/fportantier/habu) - Toolkit with a lot of little hacking tools. Many of them use Scapy.
- [mirage](https://redmine.laas.fr/projects/mirage) - Powerful and modular framework dedicated to the security analysis of wireless communications.
- [netenum](https://github.com/redcode-labs/Netenum) - A tool to passively discover active hosts on a network.
- [net-creds](https://github.com/DanMcInerney/net-creds) - Sniff and catch all sensitive data on an interface.
- [packetweaver](https://github.com/ANSSI-FR/packetweaver) - A Python framework for script filing and task sequencing.
- [p0f3plus](https://github.com/FlUxIuS/p0f3plus) - An implementation of with extra analysis features.
- [pysap](https://github.com/SecureAuthCorp/pysap) - Interact with SAP using custom built frames & tools.
- [Responder](https://github.com/SpiderLabs/Responder) -  LLMNR, NBT-NS and MDNS poisoner.
- [scapy\_unroot](https://github.com/scapy-unroot/scapy_unroot) - Tooling to use Scapy without root permissions.
- [scapy-benchmarks](https://github.com/gpotter2/scapy-benchmarks) - A small test suite that tracks the evolution of Scapy's performance.
- [sshame](https://github.com/HynekPetrak/sshame) - Tool to brute force SSH public-key authentication.
- [TIDoS Framework](https://github.com/0xInfection/TIDoS-Framework) - The Offensive Manual Web Application Penetration Testing Framework.

## Exploits

*Exploits that use Scapy. This does not count the ones included by default*

2024

- [PPPwn (CVE-2006-4304)](https://github.com/TheOfficialFloW/PPPwn) - Playstation 4 PPPoE RCE.

2022

- [CVE-2021-28444](http://blog.champtar.fr/VLAN0_LLC_SNAP) - Windows Hyper-V Security Feature Bypass Vulnerability.

2021

- [CVE-2021-24086](https://blog.quarkslab.com/analysis-of-a-windows-ipv6-fragmentation-vulnerability-cve-2021-24086.html) - Analysis of a Windows IPv6 Fragmentation Vulnerability.
- [fragattacks](https://github.com/vanhoefm/fragattacks) - Fragmentation & Aggregation Attacks.

2020

- [CVE-2020-25577](https://blog.quarkslab.com/bad-neighbor-on-freebsd-ipv6-router-advertisement-vulnerabilities-in-rtsold-cve-2020-25577.html) - Bad Neighbor on FreeBSD: IPv6 Router Advertisement Vulnerabilities in rtsold.
- [CVE-2020-16898](https://blog.quarkslab.com/beware-the-bad-neighbor-analysis-and-poc-of-the-windows-ipv6-router-advertisement-vulnerability-cve-2020-16898.html) - Beware the Bad Neighbor: Analysis and PoC of the Windows IPv6 Router Advertisement Vulnerability.

2019
- [CVE-2019-5597](https://www.synacktiv.com/ressources/Synacktiv_OpenBSD_PacketFilter_CVE-2019-5597_ipv6_frag.pdf) - IPv6 fragmentation vulnerability in OpenBSD Packet Filter.

2018

- [CVE-2018-4407](https://github.com/r3dxpl0it/CVE-2018-4407) - A heap buffer overflow in the networking code in the XNU operating system kernel (iOS and macOS).

2017
- [krackattacks-scripts](https://github.com/vanhoefm/krackattacks-scripts) - Test if clients or access points (APs) are affected by the KRACK attack against WPA2.

2016
- [CVE-2016-6366](https://github.com/RiskSense-Ops/CVE-2016-6366) - The EXTRABACON exploit, a remote code execution for Cisco ASA written by the Equation Group (NSA) and leaked by the Shadow Brokers.

Misc
- [isf](https://github.com/dark-lbp/isf) - ISF (Industrial Control System Exploitation Framework). A suite that provides exploits various industrial protocols.
