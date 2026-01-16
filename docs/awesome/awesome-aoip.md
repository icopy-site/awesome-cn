<div class="github-widget" data-repo="Mo-way/awesome-aoip"></div>
## Awesome Audio Over IP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/Mo-way/awesome-aoip/master/./resources/aes67-logo.png" alt="AES67 Logo" align="centre">](https://wikipedia.org/wiki/AES67)

> A curated list of awesome [Audio over IP](https://www.avid.com/resource-center/audio-over-ip-avb-and-dante-what-todays-music-producer-should-know) and AES67 tools and resources.

In the professional audio sector, Audio over IP (AoIP) is about transmitting uncompressed, low-latency audio over an IP (layer 3) network. Popular examples of protocols are [Dante](https://en.wikipedia.org/wiki/Dante_(networking)), [AES67](https://en.wikipedia.org/wiki/AES67) and [Ravenna](https://en.wikipedia.org/wiki/Ravenna_(networking)).

This list is short, partly due to excluding unmaintained projects. Check out the [Footnotes](https://github.com/Mo-way/awesome-aoip/blob/master/#footnotes) section at the bottom and [awesome-but-inactive](https://github.com/Mo-way/awesome-aoip/blob/master/awesome-but-inactive.md), if you prefer a more lenient approach. In General, the AoIP ecosystem is still growing and there is rather sparse tooling available at the moment. Hence, if you find anything missing, it would delight me if you open a PR to add it.

Contributions welcome! Read the [contribution guidelines](https://github.com/Mo-way/awesome-aoip/blob/master/contributing.md) first.

---



## Tools

- [Network Audio Controller](https://github.com/chris-ritsen/network-audio-controller) - Reverse engineered Dante Controller on the command line.
- [Pipewire AES67](https://gitlab.freedesktop.org/pipewire/pipewire/-/wikis/AES67) - Show AES67 streams as native audio devices on Linux.
- [Merging ALSA RAVENNA/AES67 Driver](https://bitbucket.org/MergingTechnologies/ravenna-alsa-lkm/src/master/) - Open source driver that doesn't accept contributions.
- [AES67 Linux Daemon](https://github.com/bondagit/aes67-linux-daemon) - Fork of Merging's driver with an open source web server.
- [AES67 Monitor](https://github.com/philhartung/aes67-monitor) - Cross platform AES67 monitoring app.
- [JackTrip](https://jacktrip.github.io/jacktrip/) - An open source tool for transmitting real-time audio over LAN and WAN.
- [LinuxPTP](https://linuxptp.sourceforge.net/) - PTP IEEE 1588 for Linux. Provides various tools, e.g. `ptp4l` and `phc2sys`.
- [PAM](https://github.com/martim01/pam) - FOSS AES67 capable audio monitor.
- [Snapcast](https://github.com/badaix/snapcast/tree/develop) - FOSS project for a Sonos-like multiroom solution, using a custom TCP-based protocol.
- [Ravennakit SDK](https://github.com/soundondigital/ravennakit) - Provides a cross-platform C++ SDK for professional networked audio using AES67, RAVENNA, and ST2110-30.
- [Inferno](https://gitlab.com/lumifaza/inferno) - Open source implementation of Dante AoIP in Rust ([GitHub mirror](https://github.com/teodly/inferno/)).

### Closed Source

- [Aneman](https://www.merging.com/aneman/) - **A**udio **NE**twork **MAN**ager, the Ravenna equivalent for Dante controller.
- [PTP Track Hound](https://www.ptptrackhound.com/) - PTP network traffic analysis tool (cross-platform, basic free version available).

## Organizations

- [IPMX](https://ipmx.io/about/) - A proposed set of open standards and specifications for control, copy protection, connection management and security.
- [Audinate](https://audinate.com) - Its proprietary Dante technology is the most popular AoIP solution by far.
- [Ravenna](https://www.ravenna-network.com/) - Second most popular AoIP solution, which is more open than Dante.

## Education

- [Networked Audio Products](https://rhconsulting.uk/blog/) - A census of AoIP products, conducted every year (current: [2025](https://rhconsulting.uk/blog/networked-audio-products-2025/)).
- [Dante Certification](https://www.getdante.com/resources/training/dante-certification-program/) - Understanding Dante helps to understand AoIP. The training requires an account. I recommend lv 1 and lv 2.
- [Ravenna Resources](https://www.ravenna-network.com/resources/) - Webinars and slides by Andreas Hildebrand about Ravenna, AES67, SMPTE 2110, PTP and IPMX.
- [Connecting Dante with AES67](https://download.yamaha.com/files/tcm:39-868466/) - Setting up AES67 from a Dante device isn't very straight forward, here's a guide from Yamaha as an example.

## Standards

- [AES67](https://www.aes.org/publications/standards/search.cfm?docID=96), public [draft](https://aes2.org/standards-blog/call-for-comment-on-draft-revised-aes67-xxxx-high-performance-streaming-audio-over-ip-interoperability/) - The open standard for Audio over IP.
- [NMOS](https://github.com/AMWA-TV/nmos) - REST APIs for controlling network media devices.
- [SMPTE ST 2110-30](https://www.smpte.org/standards/st2110), public [version](https://pub.smpte.org/latest/st2110-30/st2110-30-2017.pdf) - AES67 based audio transport in a video stream. Adds some contains to AES67.

## Footnotes

- [AES67 Wishlist](https://gist.github.com/njh/c9196c465ea33ae9f97db782870464ef) - Popular wishlist for AES67 software, which inspired this list.
- [Curated Web Page](https://aes67.app/resources) - Read-only "curated list of AES67 resources" by Philipp Hartung.
- [Awesome Audiovisual](https://github.com/stingalleman/awesome-audiovisual) - AV list containing a little AoIP.
- [Awesome Broadcasting](https://github.com/ebu/awesome-broadcasting) - EBU list containing a little AoIP.
