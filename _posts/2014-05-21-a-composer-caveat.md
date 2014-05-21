---
layout: post

title: A Composer Caveat
subtitle: ""

excerpt: "Requires you to be able to connect to all git hosting providers, even if you only want to update from one. 
This makes for brittle composer updates."

author:
  name: Mathew Davies
  twitter: ColonelRosa
  bio: Mathew is a developer for DueDil
---

This critical bug hit me when BitBucket (a git hosting provider) went down. I was working on a project and tried to update a
Github dependency

    composer update github/dependency
     
and realised Composer is still trying to connect to Bitbucket. This makes it *extremely* brittle as you're relying on all hosting 
providers to be online at the time of an update. Just a caveat to watch out for.  
