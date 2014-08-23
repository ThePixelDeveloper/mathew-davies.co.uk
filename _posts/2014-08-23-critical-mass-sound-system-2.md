---
layout: post

title: Building a Critical Mass Sound System - Part 2
subtitle: "Remote sounds"

excerpt: "Remote sounds - How to get the music from your smart phone to the speaker, wirelessly"

author:
  name: Mathew Davies
  twitter: ColonelRosa
  bio: Mathew is a developer for DueDil
---

I'm going to assume you have some basic technical skill and will be able to install the Pi 
operating system, connect your monitor, mouse and keyboard without my help.

Parts List
=====

* **Raspberry Pi (Version B+) (£30):** This is a small computer that will automatically start our bluetooth network. [Raspberry Pi B+ on Amazon](http://www.amazon.co.uk/Raspberry-Pi-Desktop-700MHz-Processor/dp/B00LPESRUK/ref=sr_1_1?ie=UTF8&qid=1408823657&sr=8-1&keywords=raspberry+pi+b%2B).

* **Raspberry Pi Case (£6):** You can choose whatever you like, or entirely skip it. I
chose the fairly robust [ModMyPi RPi Model B+ Case](https://www.modmypi.com/modmypi-model-b-plus-raspberry-pi-case-black?filter_name=b+%20case).

* **Power supply: (£5)** You'll need a power supply as one isn't provided. I can't remember where I bought mine, but any [micro USB charger](http://www.amazon.co.uk/s/ref=nb_sb_noss_2?url=search-alias%3Daps&field-keywords=micro+usb+charger+pi&rh=i%3Aaps%2Ck%3Amicro+usb+charger+pi) should do.

* **NOOBS SD Card (£7):**  I'd recommend the [NOOBS SD Card](http://www.amazon.co.uk/Official-Raspberry-Pi-NOOBS-Card/dp/B00KAE1GHC/ref=sr_1_2?ie=UTF8&qid=1408823960&sr=8-2&keywords=noobs+sd+card).

* **Bluetooth Adapter (£10):** ASUS products are well regarded, compatible with the Raspberry Pi and are not _too_ expensive. The [Asus USB-BT400](http://www.amazon.co.uk/gp/product/B00CM83SC0/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B00CM83SC0&linkCode=as2&tag=mathdavi-21) fit the bill.

* **HDMI to DVI Cable (£5):** This is needed so we can connect the monitor to the Pi and see what we're doing. I went ahead and bought the [World of Data - 1m HDMI to DVI Cable ](http://www.amazon.co.uk/gp/product/B001NXOGQW/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B001NXOGQW&linkCode=as2&tag=mathdavi-21).
    
**Total**: £64 - Not too shabby for a system that you can remotely send audio to.

Operating System
====================

I used Arch Linux from the NOOBs setup. This operating system doesn't come with a user interface so having some experience 
with the terminal is required.

Installing Bluetooth
====================

I followed a guide by [delx](http://delx.net.au/blog/2014/01/bluetooth-audio-a2dp-receiver-raspberry-pi/) so in the interest of not
blogging about exactly the same thing I'll pass you over to them. 

If you do run into any problems, Please ping me on Twitter (handle below) and I'll try and aide you as best as I can and update this post with the answers.

_[Mirror of delx.net](/archive/delx.html)_

Conclusion
==========

So there you go! A device smaller than your hand, that has fantastic range and doesn't sound half bad. 

Part 3 is coming soon which is going to go over how to choose speaker drivers.
