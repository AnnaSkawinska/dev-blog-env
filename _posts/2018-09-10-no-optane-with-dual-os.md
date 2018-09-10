---
layout: post
section-type: post
title: No DualOS with Intel Optane
category: os
tags: [ 'hardware', 'linux', 'intel' ]
---

Intel Optane is a great caching solution for HDD. It lets you have a fast and huge disk space. In some stores, it is sold in a cheap package with CPU or/and motherboard.

# BUT! it works only on Windows
No Dual-OS booting! It's just not supported. Not even on completely separated drives!

# Walkaround 
For a long time, I've used Optane with two drives and two OS. To change the OS always I needed to change an additional setting in the BIOS and reboot to be able to choose the second drive. Probably the alternative bootloader won't work on one drive for very long.

You were warned.

PS: AMD has their caching system too since the Ryzen 2 release.

![Optane explanation by an image](https://techreport.com/r.x/2017_03_27_Intel_Optane_Memory_promises_the_best_of_hard_drives_and_SSDs/FAQ.png)