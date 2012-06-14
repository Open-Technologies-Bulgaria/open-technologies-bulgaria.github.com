---
layout: post
title: "ThinkPad Mini Dock design flaw"
date: 2012-06-14 21:55
comments: true
categories: ['QA', 'hardware', 'Lenovo', 'ThinkPad']
author: Alexander Todorov
---

I've got my hands onto a `ThinkPad Mini Dock Series 3` docking station which is
compatible with my newest laptop. Being a QA engineer for so long I immediately
noticed something that wasn't quite right. The buttons on the left and the mechanism
next to them are blocking the hot air exhaust from the CPU fan. This model of docking
station is made to fit several models of laptops and those which dock in position 2 are
less affected from those which dock in possition 1. Mine was not a lucky one.

![docking station in position 2](/images/dock/alone.jpg "docking station in position 2")

On the pictures below it is clearly visible that most of the hot air coming out of the CPU
fan is blocked.

![top view](/images/dock/top.jpg "top view")
![back view](/images/dock/back.jpg "back view")
![side view](/images/dock/side.jpg "side view")


In order to reduce laptop heating and provide better cooling I decided to remove the
1/2 position switch mechanism. To do that you have to unscrew all screws from the docking
station and carefully split the top and bottom halves. The offending piece of plastic is
screwed with two tiny screws at the bottom. Once they are removed everything comes off.

![blocking part removed](/images/dock/removed.jpg "blocking part removed")

Because QA is not only about finding bugs but making sure people are aware of them so bugs
get fixed I've sent an email to `Lenovo`. I'd be glad if they take this into account and
do a better test job for their next models. I don't want to switch to another laptop brand :(.

--------------------------

[Alexander Todorov](http://about.me/atodorov) is a QA engineer with 5+ years of experience and
founder of `Open Technologies Bulgaria, Ltd`.
