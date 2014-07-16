---
layout: post
draft: true

title: Building a Critical Mass Sound System - Part 2
subtitle: "Remote sounds"

excerpt: "Remote sounds - How to get the music from your smart phone to the speaker, wirelessly"

author:
  name: Mathew Davies
  twitter: ColonelRosa
  bio: Mathew is a developer for DueDil
---

This is one of the first things I wanted to sort out before I started work on anything else. It's easy to do, cheap and 
doesn't require many parts. 

_I'm going to assume you have some basic technical skill and will be able to install the Pi 
operating system, connect your monitor, mouse, keyboard, etc ... without my help._

Parts
=====

* **Raspberry Pi (Version B) (£24):** This is a small computer that will run the software to start our wireless network. A friend of mine gave me his as he didn't 
have a use of it, but they can be bought cheaply off [Amazon](http://www.amazon.co.uk/gp/product/B008PT4GGC/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B008PT4GGC&linkCode=as2&tag=mathdavi-21).

* **Raspberry Pi Case (£5):** You can choose whatever you want here, but remember it's not going to be seen so don't go wild on a nice looking case. I
chose the fairly robust [Cyntech Blackberry Case](http://www.amazon.co.uk/gp/product/B00BBXWX9Q/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B00BBXWX9Q&linkCode=as2&tag=mathdavi-21).

* **Power supply: (£5)** The Raspberry Pi doesn't come with any accessories so you'll need a PSU to power it. I can't remember where I bought mine, but something like [this](http://www.amazon.co.uk/gp/product/B00AUKR4EU/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B00AUKR4EU&linkCode=as2&tag=mathdavi-21)
will suffice.

* **NOOBS SD Card (£7):**  You can use any SD card for the Raspberry Pi, but if you haven't had experience with formatting and copying an operating system
to the card you might want to opt for the [NOOBS SD Card](http://www.amazon.co.uk/gp/product/B00KAE1GHC/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B00KAE1GHC&linkCode=as2&tag=mathdavi-21).

* **Bluetooth Adapter (£10):** ASUS products are well regarded, compatible with the Raspberry Pi and are not _too_ expensive. I went for the [Asus USB-BT400](http://www.amazon.co.uk/gp/product/B00CM83SC0/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B00CM83SC0&linkCode=as2&tag=mathdavi-21).

* **HDMI to DVI Cable (£5):** This is needed so we can connect monitor to the Pi and see what we're doing. I went ahead and bought [this](http://www.amazon.co.uk/gp/product/B001NXOGQW/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B001NXOGQW&linkCode=as2&tag=mathdavi-21).

* **USB Hub (£11):** At the current time of writing, the Pi only comes with two USB ports, so there's an issue if we need to connect more peripherals. I bought the [The Pi Hut 7 Port Powered Hub](http://www.amazon.co.uk/gp/product/B00B0ZOCPS/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1634&creative=6738&creativeASIN=B00B0ZOCPS&linkCode=as2&tag=mathdavi-21).  

   _Edit_ - Make sure it's a powered hub, the Pi might not be able to provide the current for all the peripherals if it isn't.
    
**Total**: £62 - Not too shabby for a system that you'll be able to remotely send music to.

Setting up Bluetooth
====================

For the most part I followed this guide on Instructables to get the BT working: [Turn your Raspberry Pi into a Wireless Portable Bluetooth Audio System A2DP](http://www.instructables.com/id/Turn-your-Raspberry-Pi-into-a-Portable-Bluetooth-A/?ALLSTEPS)

No sound unless you login?
--------------------------

Unfortunately I could only get sound output when I logged into the OS. I later found out that pulseaudio is not started as a system 
service, but only when you login. You can change how it's started as follows:

```
script
```

----

I'm still bumping into an issue where the sound wont come out of the headphone jack. A reboot or two normally fixes it, but it's
not ideal. I'll update the post when I find a reliable solution.

Conclusion
==========

So there you have it, you've got a small computer, with great range that you can send music to wirelessly. 


Part 3 is coming soon which is going to go over how to choose speaker drivers and box design.
