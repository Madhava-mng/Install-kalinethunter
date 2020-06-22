Small script to install nethunter
# kali nethunter:
	
```Kali NetHunter is a free and open-source mobile penetration testing platform for Android devices, based on Kali Linux. Kali NetHunter is available for un-rooted devices (NetHunter Rootless), for rooted devices that have a custom recovery (NetHunter Lite), and for rooted devices with custom recovery for which a NetHunter specific kernel is available (NetHunter). Official images are published by Offensive Security on their download page and are updated every quarter. NetHunter images with custom kernels are published for the most popular supported devices, such as Google Nexus, Samsung Galaxy and OnePlus. Many more models are supported, and images not published by Offensive Security can be generated using NetHunter build scripts. Kali NetHunter is maintained by a community of volunteers, and is funded by Offensive Security.```
# Requirment:

* Android phone
* Termux (Apk) https://play.google.com/store/apps/details?id=com.termux
* vnc (Apk) https://play.google.com/store/apps/details?id=com.realvnc.viewer.android
* Hacker's keyboard (Apk) for easy navigation https://play.google.com/store/apps/details?id=com.termux

# Installation:

       pkg update && pkg upgrade && pkg install git && git clone https://github.com/Madhava-mng/Install-kalinethunter.git && cd Install-kalinethunter && ./start

***

# Run:


|        Command       |                  destination                            |
|----------------------|---------------------------------------------------------|
| nethunter            | start Kali NetHunter command line interface             |
| nethunter -r         | start Kali NetHunter command line interface (root)      |
| nethunter kex passwd | Configure the KeX password (only needed before 1st use) |
| nethunter kex &      | start Kali NetHunter Desktop Experience                 |
| nethunter kex stop   | stop Kali NetHunter Desktop Experiencce                 |


# More Info:

## Background and history:
* Version 1.1 was released in January 2015 and added support for Oneplus devices & non-english keyboard layouts for HID attacks.

* Version 1.2 was released in May 2015 and added support for Nexus 9 Android tablets.

* Version 3.0 was released in January 2016 after a major rewrite of the application, installer, and kernel building framework. This version also introduced support for devices running Android Marshmallow.

* Version 2019.2 was released in May 2019 and switched to kali-rolling as its Kali Linux container. It adopted the Kali Linux versioning and release cycle to reflect that change. With this release, the number of supported Android devices grew to over 50.

* Version 2019.3 was released in September 2019 and introduced the NetHunter App Store as the default mechanism for deploying and updating apps.

* Version 2019.4 was released in December 2019 and premiered the "Kali NetHunter Desktop Experience."

* Before December 2019, Kali NetHunter was only available for selected Android devices. Installing Kali NetHunter required a device that:

1 is rooted
2 has a custom recovery
3 had a kernel built especially for Kali NetHunter

* In December 2019, "Kali NetHunter Lite" and "Kali NetHunter Rootless" editions were released to allow users of devices for which no NetHunter specific kernels were available, and users of devices that are not rooted, to install Kali NetHunter with a reduced set of functionality.

## Features
* In addition to the penetration testing tools included with desktop Kali Linux, NetHunter also enables Wireless 802.11 frame injection, one-click MANA Evil Access Points, HID keyboard functionality (for Teensy-like attacks), as well as BadUSB man-in-the-middle /(MitM) attacks.

## Documentation:
https://www.kali.org/docs/nethunter/nethunter-rootless/
