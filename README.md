# Payload Library for the [Packet Squirrel](https://hak5.org/products/packet-squirrel) by [Hak5](https://hak5.org)

This repository contains payloads and extensions for the Hak5 Packet Squirrel and Hak5 Packet Squirrel Mark II. Community-developed payloads are listed, and developers are encouraged to create pull requests to make changes or submit new payloads.

<div align="center">
  <img src="https://img.shields.io/github/forks/hak5/packetsquirrel-payloads?style=for-the-badge"/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://img.shields.io/github/stars/hak5/packetsquirrel-payloads?style=for-the-badge"/>
  <br/>
  <img src="https://img.shields.io/github/commit-activity/y/hak5/packetsquirrel-payloads?style=for-the-badge">
  <img src="https://img.shields.io/github/contributors/hak5/packetsquirrel-payloads?style=for-the-badge">
</div>
<br/>
<p align="center">
  <a href="https://payloadhub.com"><img src="https://cdn.shopify.com/s/files/1/0068/2142/files/payloadhub.png?v=1652474600"></a>
  <br/>
  <a href="https://payloadhub.com/blogs/payloads/tagged/packet-squirrel">View Featured Packet Squirrel Payloads and Leaderboard</a>
  <br/><i>Get your payload in front of thousands. Enter to win over $2,000 in prizes in the <a href="https://hak5.org/pages/payload-awards">Hak5 Payload Awards!</a></i>
</p>

<div align="center">
  <a href="https://hak5.org/discord"><img src="https://img.shields.io/discord/506629366659153951?label=Hak5%20Discord&style=for-the-badge"></a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://youtube.com/hak5"><img src="https://img.shields.io/youtube/channel/views/UC3s0BtrBJpwNDaflRSoiieQ?label=YouTube%20Views&style=for-the-badge"/></a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://youtube.com/hak5"><img src="https://img.shields.io/youtube/channel/subscribers/UC3s0BtrBJpwNDaflRSoiieQ?style=for-the-badge"/></a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://twitter.com/hak5"><img src="https://img.shields.io/badge/follow-%40hak5-1DA1F2?logo=twitter&style=for-the-badge"/></a>
  <br/><br/>
</div>

# Packet Squirrel Versions 

There are currently two versions of the Packet Squirrel. The original Packet Squirrel can be identified by the micro-USB power port, while the Packet Squirrel Mark II can be identified by the USB-C power port.

Please make sure you select payloads for the device you have!

Payloads for the original Packet Squirrel can be found in the `legacy-mk1/` directory.

The Packet Squirrel Mark II payloads can be found in the `payloads/` directory.

The Packet Squirrel Mark II expands the DuckyScript for Packet Squirrel commands and adds many new commands and features. In general, payloads from the original Packet Squirrel can be adapted to run on the Packet Squirrel Mark II by adopting the new commands - check out the [Packet Squirrel Mark II Payload documentation](https://docs.hak5.org/packet-squirrel-mark-ii/payload-development/duckyscript-for-packet-squirrel) for more information!

The existing suite of original Packet Squirrel payloads remains available and functional on the original hardware in the `legacy-mk1/` directory!

# Shop
- [Purchase the Packet Squirrel](https://hak5.org/products/packet-squirrel "Purchase the Packet Squirrel")
- [PayloadStudio Pro](https://hak5.org/products/payload-studio-pro "Purchase PayloadStudio Pro")
- [Shop All Hak5 Tools](https://shop.hak5.org "Shop All Hak5 Tools")

## Getting Started
- [Build Payloads with PayloadStudio](#build-your-payloads-with-payloadstudio) | [QUICK START GUIDE](https://docs.hak5.org/packet-squirrel-mark-ii/payload-development/payload-development-basics "QUICK START GUIDE")

## Documentation / Learn More
-   [Documentation](https://docs.hak5.org/packet-squirrel-mark-ii "Documentation")

## Community
*Got Questions? Need some help? Reach out:*
-  [Discord](https://hak5.org/discord/ "Discord") | [Forums](https://forums.hak5.org/forum/94-packet-squirrel/ "Forums")

## Additional Links
<b>Follow the creators</b><br/>
<p >
	<a href="https://twitter.com/notkorben">Korben's Twitter</a> | 
	<a href="https://instagram.com/hak5korben">Korben's Instagram</a>
<br/>
	<a href="https://infosec.exchange/@kismetwireless">Dragorn's Mastodon</a> | 
<br/>
	<a href="https://twitter.com/hak5darren">Darren's Twitter</a> | 
	<a href="https://instagram.com/hak5darren">Darren's Instagram</a>
</p>

<br/>
<h1><a href="https://hak5.org/products/packet-squirrel">About the Packet Squirrel</a></h1>

The Packet Squirrel Mark II by Hak5 is a stealthy pocket-sized man-in-the-middle.

This Ethernet multi-tool is designed to give you covert remote access, painless packet captures, and secure VPN connections with the flip of a switch.

<b>
<div align="center">
<a href="https://www.youtube.com/watch?v=hN9tFx5N3uM">Launch Video</a>
<br/>
<br/>
</div>
</b>
<p align="center">
<a href="https://hak5.org/products/packet-squirrel"><img src="https://3076592524-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F520JUF2JxB2RMXztRVAV%2Fuploads%2F6gSNjJNnaht6yMo5AMCg%2Fsquirrel-setup.png?alt=media&token=382e30a0-10c0-4ab0-88b4-db27e9331a23"></a>
<br/><i>Hak5 Packet Squirrel Features</i>
</p>
<br/>

The Packet Squirrel Mark II is an Ethernet multi-tool for packet capture, man-in-the-middle network manipulation, stream filtering and redirection, remote VPN access, and more.

Use simplified DuckyScript for Packet Squirrel to create payloads, or unlock the full power of Bash script or Python 3 for complex payloads.

Edit payloads live in the Web UI editor with syntax highlighting, SSH, or [build your payloads with Payload Studio](https://payloadstudio.hak5.org).

Exfiltrate data or pentest from anywhere with [Hak5 Cloud C²](https://shop.hak5.org/products/c2 "Hak5 Cloud C²").

# About DuckyScript™

DuckyScript is the payload language of Hak5 gear.

Originating on the Hak5 USB Rubber Ducky as a standalone language, the Packet Squirrel uses DuckyScript commands to bring the ethos of easy-to-use actions to the payload language.

DuckyScript commands are always in all capital letters to distinguish them from other system or script language commands. Typically, they take a small number of options (or sometimes no options at all).

Payloads can be constructed of DuckyScript commands alone, or combined with the power of bash scripting and system commands to create fully custom, advanced actions.

The files in this repository are _the source code_ for your payloads and run _directly on the device_ **no compilation required** - simply place your payload.txt in the appropriate directory and you're ready to go!

<h1><a href="https://payloadstudio.hak5.org">Build your payloads with PayloadStudio</a></h1>
<p align="center">
Take your DuckyScript™ payloads to the next level with this full-featured, <b>web-based (entirely client-side)</b> development environment.
<br/>
<a href="https://payloadstudio.hak5.org"><img src="https://cdn.shopify.com/s/files/1/0068/2142/products/payload-studio-icon_180x.png?v=1659135374"></a>
<br/>
<i>Payload studio features all of the conveniences of a modern IDE, right from your browser. From syntax highlighting and auto-completion to live error-checking and repo synchronization - building payloads for Hak5 hotplug tools has never been easier!
<br/><br/>
Supports your favorite Hak5 gear - USB Rubber Ducky, Bash Bunny, Key Croc, Shark Jack, Packet Squirrel & LAN Turtle!
<br/><br/></i><br/>
<a href="https://hak5.org/products/payload-studio-pro">Become a PayloadStudio Pro</a> and <b>Unleash your hacking creativity!</b>
<br/>
OR
<br/>
<a href="https://payloadstudio.hak5.org/community/">Try Community Edition FREE</a> 
<br/><br/>
<img src="https://cdn.shopify.com/s/files/1/0068/2142/products/packetsquirrel-transparent-2_180x.png?v=1653799994">
</p>
<br/>

# Payloads
The `payloads/` directory contains a collection of scripts used for the Packet Squirrel Mark II. These are basic payloads written in DuckyScript™, Python, Bash, or a combination of all three. Each directory within the `payloads/` folder represents a separate payload. Payloads should be placed into the `payloads/` directory on your Packet Squirrel device.

---

This should provide a good starting point for anyone using or contributing to the repository. If you need further adjustments or additional sections, feel free to ask!
