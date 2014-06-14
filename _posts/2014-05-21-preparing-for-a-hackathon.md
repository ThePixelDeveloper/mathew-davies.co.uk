---
layout: post
draft: false

title: Preparing for a Hackathon as a Developer
subtitle: ""

excerpt: "Making sure you're ready to work offline, or at least with a slow internet connection. Here's what you need to know."

author:
  name: Mathew Davies
  twitter: ColonelRosa
  bio: Mathew is a developer for DueDil
---

Here's how I prepared for an internal hackathon at DueDil. My goal here was to be able to work with a 
slow internet connection or be completely offline. It's rare this would happen, but if I plan for it then
I should have some advantage over the competition should it occur.

Documentation
-----

All of the following provide offline documentation.

* [DevDocs.io](http://devdocs.io/) supports most of the web programming languages, but misses out on some of the big ones 
, ie Objective C, C, C++, Scala and Clojure. 

* [Dash](http://kapeli.com/dash) for Mac does the same as DevDocs.io, but within a desktop app. It comes with a lot more 
languages, but it comes at a cost of $20.

* [Zeal](http://zealdocs.org/) is the open-source equivalent of Dash and works with Linux and Windows. Supports what Dash
does and integrates into emacs and vim.

Programming Environment
-----

I'm a Vagrant user and so what I did was pre-provision a box with a wide variety of 
databases, web servers and job queuing daemons. This means I can switch software without wasting time during the event.
The path of least resistance for this is to use one of the following services:

* [PuPHPet](https://puphpet.com) - Provisions a Vagrant env with Puppet
* [Rove](http://rove.io/) - Provisions a Vagrant env with Chef

and select all the options.

A hackathon is not the place to start playing with the latest tools. I remember wasting a fair bit of time playing with 
Volo (javascript packager manager) during the COSMIC hack. Stick to what you know.

The Idea
-----

Ensure you come up with something you can finish off within the time frame. Remember you're not going to be working the 
full period and will spend a few hours eating, drinking and socialising. Make sure you plan for it.
