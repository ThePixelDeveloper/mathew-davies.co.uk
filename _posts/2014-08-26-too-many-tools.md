---
layout: post

title: We live in a world of too many tools
subtitle: ""

excerpt: "In the search of simplicity, we've ended up with tedious development setups"

author:
  name: Mathew Davies
  twitter: ColonelRosa
  bio: Mathew is a developer for DueDil
---

Development tools are supposed to make our lives "easier", but I feel like they're making it harder. 

When I first started developing it was as simple as downloading XAMPP, dumping some PHP into a directory and ... that was it. Lets compare that with what I assume most of us do now.

Install Vagrant (and any of its plugins), Ruby, Node, NPM, Grunt, Compass, run Vagrant, wait 30 minutes for it to provision (if it does at all) and then start programming. 

_You might ask why I don't install Grunt and Compass in the VM._
 
 _Unfortunately NFS doesn't send FS events so unless I want to cook my CPU polling the HDD it's easier to run it on the host. The other file sync methods are just as bad in their own special way. It annoys me because I really want it to work, but I can't help be put off by the incredible amount of time it's wasted._

There's a lot more to go wrong and having to make sure all these tools are in working order is a pain, especially when breaking changes occur. Not having Vagrant isn't an option either. 

What's the way forward? Or am I just using the wrong tools? 
