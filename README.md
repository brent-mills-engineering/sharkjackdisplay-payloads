# Payload Library for the [Shark Jack Display](https://hak5.org/products/shark-jack-display) by [Hak5](https://hak5.org)

This repository contains payloads for the Hak5 Shark Jack Display.  Community developed payloads are listed and developers are encouraged to create pull requests to make changes to or submit new payloads.

<div align="center">
<img src="https://img.shields.io/github/forks/hak5/sharkjackdisplay-payloads?style=for-the-badge"/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/github/stars/hak5/sharkjackdisplay-payloads?style=for-the-badge"/>
<br/>
<img src="https://img.shields.io/github/commit-activity/y/hak5/sharkjackdisplay-payloads?style=for-the-badge">
<img src="https://img.shields.io/github/contributors/hak5/sharkjackdisplay-payloads?style=for-the-badge">
</div>
<br/>
<p align="center">
<a href="https://payloadhub.com"><img src="https://cdn.shopify.com/s/files/1/0068/2142/files/payloadhub.png?v=1652474600"></a>
<br/>
<a href="https://payloadhub.com/blogs/payloads/tagged/shark-jack">View Featured Shark Jack Payloads and Leaderboard</a>
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

# Shark Jack Versions 

There are currently three versions of the Shark Jack.  The original Shark Jack and Shark Jack Cable do not feature an OLED screen, while the Shark Jack Display does.

Please make sure you select payloads for the device you have!

Payloads for the original Shark Jack and Shark Jack Cable can be found at [github.com/hak5/sharkjack-payloads](https://github.com/hak5/sharkjack-payloads)

The Shark Jack Display expands the DuckyScript for Shark Jack with many new commands and features for interactive payloads. In general, payloads from the original Shark Jack can be adapted to run on the Shark Jack Display by adopting the new commands - check out the [Shark Jack Display Payload documentation](https://docs.hak5.org/shark-jack-display/payload-dev-speedrun) for more information!

# Shop
- [Purchase the Shark Jack Display](https://hak5.org/products/shark-jack-display "Purchase the Shark Jack Display")
- [PayloadStudio Pro](https://hak5.org/products/payload-studio-pro "Purchase PayloadStudio Pro")
- [Shop All Hak5 Tools](https://shop.hak5.org "Shop All Hak5 Tools")

## Getting Started
- [Build Payloads with PayloadStudio](#build-your-payloads-with-payloadstudio) | [QUICK START GUIDE](https://docs.hak5.org/shark-jack-display/payload-dev-speedrun "QUICK START GUIDE") 

## Documentation / Learn More
-   [Documentation](https://docs.hak5.org/shark-jack-display "Documentation") 

## Community
*Got Questions? Need some help? Reach out:*
-  [Discord](https://hak5.org/discord/ "Discord") | [Forums](https://forums.hak5.org/forum/101-shark-jack/ "Forums")

## Additional Links
<b> Follow the creators </b><br/>
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
<h1><a href="https://hak5.org/products/shark-jack-display">About the Shark Jack Display</a></h1>

The Shark Jack Display by Hak5 is a portable network attack and automation tool for pentesters and systems administrators designed to enable social engineering engagements and opportunistic wired network auditing.

It features interactive DuckyScript™ with Bash that lets you leverage its Linux base, allowing you to automate attacks using payloads and familiar network tools.

You may [build your payloads with Payload Studio](https://payloadstudio.hak5.org) and exfiltrate data or pentest from anywhere with [Hak5 Cloud C²](https://shop.hak5.org/products/c2 "Hak5 Cloud C²").

# About DuckyScript™

DuckyScript is the payload language of Hak5 gear.

Originating on the Hak5 USB Rubber Ducky as a standalone language, the Shark Jack Display uses DuckyScript commands to bring the ethos of easy-to-use actions to the payload language.

DuckyScript commands are always in all capital letters to distinguish them from other system or script language commands.  Typically, they take a small number of options (or sometimes no options at all).

Payloads can be constructed of DuckyScript commands alone, or combined with the power of bash scripting and system commands to create fully custom, advanced actions.

The files in this repository are _the source code_ for your payloads and run _directly on the device_ **no compilation required** - simply place your `payload.txt` in the appropriate directory and you're ready to go!

<h1><a href="https://payloadstudio.hak5.org">Build your payloads with PayloadStudio</a></h1>
<p align="center">
Take your DuckyScript™ payloads to the next level with this full-featured,<b> web-based (entirely client side) </b> development environment.
<br/>
<a href="https://payloadstudio.hak5.org"><img src="https://cdn.shopify.com/s/files/1/0068/2142/products/payload-studio-icon_180x.png?v=1659135374"></a>
<br/>
<i>Payload studio features all of the conveniences of a modern IDE, right from your browser. From syntax highlighting and auto-completion to live error-checking and repo synchronization - building payloads for Hak5 hotplug tools has never been easier!
<br/><br/>
Supports your favorite Hak5 gear - USB Rubber Ducky, Bash Bunny, Key Croc, Shark Jack, Packet Squirrel & LAN Turtle!
<br/><br/></i><br/>
<a href="https://hak5.org/products/payload-studio-pro">Become a PayloadStudio Pro</a> and <b> Unleash your hacking creativity! </b>
<br/>
OR
<br/>
<a href="https://payloadstudio.hak5.org/community/"> Try Community Edition FREE</a> 
<br/><br/>
<img src="https://cdn.shopify.com/s/files/1/0068/2142/files/themes1_1_600x.gif?v=1659642557">
<br/>
<i> Payload Studio Themes Preview GIF </i>
<br/><br/>
<img src="https://cdn.shopify.com/s/files/1/0068/2142/files/AUTOCOMPLETE3_600x.gif?v=1659640513">
<br/>
<i> Payload Studio Autocomplete Preview GIF </i>
</p>


<h1><a href='https://shop.hak5.org/products/c2'>Hak5 Cloud C² </a></h1>
Cloud C² makes it easy for pen testers and IT security teams to deploy and manage fleets of Hak5 gear from a simple cloud dashboard. 

Cloud C² is available as an instant download. **A free license for Community Edition is available which is not for commercial use and comes with community support.**
The **Professional** and **Teams Editions** are for commercial use with standard support.
<p align="center">
<a href="https://shop.hak5.org/products/c2"><img src="https://cdn.shopify.com/s/files/1/0068/2142/files/teams1.png?v=1614035533"></a>
<br/>
<i> Hak5 Cloud C² Web Interface</i>
</p>

Cloud C² is a **self-hosted** web-based command and control suite for networked Hak5 gear that lets you **pentest from anywhere.**

Linux, Mac and Windows computers can host the Cloud C² server while Hak5 gear such as the WiFi Pineapple, LAN Turtle and Packet Squirrel can be provisioned as clients.

Once you have the Cloud C² server running on a public-facing machine (such as a VPS) and the Hak5 devices are provisioned and deployed, you can login to the Cloud C² web interface to manage these devices as if you were directly connected.

With multiple Hak5 devices deployed at a client site, aggregated data provides a big picture view of the wired and wireless environments.

<p align="center">
<a href="https://shop.hak5.org/products/c2"><img src="https://cdn.shopify.com/s/files/1/0068/2142/files/teams2.png?v=1614035564"/></a>
<br/>
<i> Hak5 Cloud C² Web Interface - Teams Edition - Sites </i>
</p>

Hak5 Cloud C² Teams edition comes full of features designed to help you manage **all** of your remote Hak5 devices with ease:
 - Multi-User
 - Multi-Site
 - Role-Based Access Control
 - Advanced Auditing
 - Tunneling Services including web Terminal and WiFi Pineapple web interface proxy

<a href="https://shop.hak5.org/products/c2">Learn More</a>

<h1><a href='https://payloadhub.com'>Contributing</a></h1>

<p align="center">
<a href="https://payloadhub.com"><img src="https://cdn.shopify.com/s/files/1/0068/2142/files/payloadhub.png?v=1652474600"></a>
<br/>
<a href="https://payloadhub.com">View Featured Payloads and Leaderboard </a>
</p>


Once you have developed your payload, you are encouraged to contribute to this repository by submitting a Pull Request. Reviewed and Approved pull requests will add your payload to this repository, where they may be publically available.

# Please adhere to the following best practices and style guides when submitting a payload.

### Purely destructive or invasive payloads will not be accepted. No, it's not "just a prank".

Payloads should be submitted to the most appropriate category directory, such as exfiltration, interception, recon, sniffing, etc.

Subject to change. Please ensure any submissions meet the [latest version](https://github.com/hak5/sharkjackdisplay-payloads/blob/master/README.md) of these standards before submitting a Pull Request.

## Naming Conventions

Please give your payload a unique, descriptive and appropriate name. Do not use spaces in payload, directory or file names. Each payload should be submit into its own directory, with  `_` used in place of spaces, to one of the categories such as exfiltration, general, util, or recon. Do not create your own category.

The payload itself should be named `payload.txt`.

Additional files and documentation can be included in the payload directory.  Documentation should be in `README.md` or `README.txt`.

## Payload Configuration

In many cases, payloads will require some level of configuration by the end payload user. Be sure to take the following into careful consideration to ensure your payload is easily tested, used and maintained. 

- Remember to use PLACEHOLDERS for configurable portions of your payload - do not share your personal URLs, API keys, Passphrases, etc...
- Do not leave defaults that point at live services
- Make note of both required and optional configuration(s) in your payload using comments at the top of your payload or "inline" where applicable

## Payload Format

Payloads should begin with comments specifying at the very least the name of the payload and author. Additional information such as a brief description, the target, any dependencies / prerequisites and the LED status used is helpful.

    # Title: Example payload
	# Description: Example payload with configuration options
	# Author: Hak5
	# Version: 1.0
	#
	# LED SETUP
	# ROUTE="example"
	# CREATE_SPINNER "Starting DHCP"
	#   NETMODE DHCP_CLIENT
	# STOP_SPINNER
	# WAIT_FOR_LINK

### Configuration Options

Configurable options should be specified in variables at the top of the payload file:

    # Options
    ROUTE="example"


### NETMODE

All payloads should include a `NETMODE` command to set the Shark Jack Display to a useful network mode. [Read the full NETMODE documentation](https://docs.hak5.org/shark-jack-display/netmode).

### LED

The payload should use common payload states rather than unique color/pattern combinations when possible with an LED command preceding the Stage or `NETMODE`.

	LED SETUP
	NETMODE DHCP_CLIENT

Common payload states include a `SETUP`, with may include a `FAIL` if certain conditions are not met. This is typically followed by either a single `ATTACK` or multiple `STAGEs`. More complex payloads may include a `SPECIAL` function to wait until certain conditions are met. Payloads commonly end with a `CLEANUP` phase, such as moving and deleting files or stopping services. A payload may `FINISH` when the objective is complete and the device is safe to eject or turn off. These common payload states correspond to `LED` states. [Read the full LED documentation](https://docs.hak5.org/shark-jack-display/led).


<h1><a href="https://hak5.org/pages/policy">Legal</a></h1>

Payloads from this repository are provided for educational purposes only.  Hak5 gear is intended for authorized auditing and security analysis purposes only where permitted subject to local and international laws where applicable. Users are solely responsible for compliance with all laws of their locality. Hak5 LLC and affiliates claim no responsibility for unauthorized or unlawful use.

DuckyScript is a trademark of Hak5 LLC. Copyright © 2010 Hak5 LLC. All rights reserved. No part of this work may be reproduced or transmitted in any form or by any means without prior written permission from the copyright owner.
Shark Jack, Shark Jack Display and DuckyScript are subject to the Hak5 license agreement (https://hak5.org/license)
DuckyScript is the intellectual property of Hak5 LLC for the sole benefit of Hak5 LLC and its licensees. To inquire about obtaining a license to use this material in your own project, contact us. Please report counterfeits and brand abuse to legal@hak5.org.
This material is for education, authorized auditing and analysis purposes where permitted subject to local and international laws. Users are solely responsible for compliance. Hak5 LLC claims no responsibility for unauthorized or unlawful use.
Hak5 LLC products and technology are only available to BIS recognized license exception ENC favorable treatment countries pursuant to US 15 CFR Supplement No 3 to Part 740.

# Disclaimer
Generally, payloads may execute commands on your device. As such, it is possible for a payload to damage your device. Payloads from this repository are provided AS-IS without warranty. While Hak5 makes a best effort to review payloads, there are no guarantees as to their effectiveness. As with any script, you are advised to proceed with caution.

