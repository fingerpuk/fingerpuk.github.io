---
title:  "Don't worry if nothing works."
date:   2015-11-17 16:29:00
description: Technology Hacking
---

# Don’t worry if nothing works.

When I was 11 I figured out how to modify the control board on my dad’s VCR so that we could use an old fashioned clock to set up when it should start and stop recording. This was my first exposure to electronics and computer systems.

5-ish years later I was poking around a serial modem card and discovered that just like the VCR it could be modified - in this case through a series of audio tones which would allow control from outside of the host PC. This was my first exposure to hacking.

5-ish years later I was poking around a few networks when I discovered a vulnerability which would allow me to take control of network cards in remote systems. I wrote a script and set it loose, not to be malicious, but to see what would happen.

A few hours later I discovered I was now in control of more systems than I was comfortable with. And I was scared. I killed all the files associated with the script, removed the hard drive and my network adaptor, put them all in a canvas bag and smashed the shit out of them with a lump hammer. I then walked a mile down the road and dumped that bag in a random bin. The paranoia lasted for months.

Speak to anyone who started to code from an early age and most of them will have similar stories. These stories happen because computer technology doesn’t work.

When Ed blew the whistle on the CIA and NSA nobody in the security scene was surprised. None of us were bothered either.  We’d spent the first bits of our lives looking for and finding countless bugs and holes in technology and now we are developers ourselves we spend our lives building bugs and holes into technology. The spy people aren’t able to get at all our stuff because they are beholders of godly powers - they are able to get at our stuff because we leave all the doors open.

## Building the holes.

Here’s the thing - technology gets more complex every time it iterates. Moore’s law should be re-written to say ‘the security within computer systems will half in capability every two years’. Think about what is happening inside your computer for a second. There are thousands of components talking to each other in ways so complex your brain cannot comprehend them. The reason Microsoft got so big so quick is because to write a basic operating system needs hundreds of people building the thousands of bits of stuff that users demand. Take the simple example of sending an email - your computer needs code to make the keyboard function, it needs to code to interpret the keyboard input and store it in memory somewhere, it needs code to make the memory work and the code to let that storage happen. It needs code to make the screen work, and to take the keyboard stuff now in memory and convert it to fonts on the screen. And yes it needs code to make fonts work, code to give the fonts a window, and code to give that window a thing that can accept text. The list of stuff needed goes on and on, I have no idea how many individual chunks of code are needed to work a modern operating system and I’d bet that not one person on this planet could tell me. The complexity of modern software is impossible to grasp so is it any surprise that code is full of holes, bugs, insecurities, and general mess? No.

Code is written by people and people screw things up. Instead of focussing on writing clean and secured code we think about going to the pub or the girl in the next office. We think about the time and how long before we can bugger off or work on something more fun and so we write stuff that’s not very good. And because no piece of code stands alone the bit I wrote that is not very good is reliant on another bit that’s not very good. Layers upon layers of bad code, full of holes that let people in, built to arbitrary deadlines.

## Release the rampant wildebeest

Now take the above and multiply it by about (insert big number here). Welcome to the world.

What was bad when constrained to a single PC becomes laughable when you apply it to the modern world. Your computer has to talk to other computers all the time and they all speak different languages and dialects. Your phone, your car, your thermostat, your watch, your lightbulbs. If it’s not possible to know how complex a lone operating system is imagine how impossible it is to understand the entire digital estate of the world. How could this *ever* be secure? It can’t, give up the dream.

## You are the problem.

You demand instant access to everything, you demand security on everything, then you demand that you don’t have to remember complex passwords. You bought your last iPhone less than two years ago and yet you demand a new one that is more connected. You demand bio sensors, you demand cross device connectivity, you demand real-time everything, and you demand that it all happens now. More and more developers sat in bigger and bigger companies are pumping out more and more code riddled with more and more bugs so that you can play Ninja Rockstar 9000 on a device with a slightly bigger screen whilst monitoring your glucose levels on your iLust watch. Your demands make my life as a hacker much easier.

## I am the problem.

The more you demand the more I build. My deadlines are tight and - let’s be honest here - all I care about is meeting those deadlines so you don’t throw a strop. This means I re-use code that I know is bad and I build on top of code I assume is ok. Deep down I know it’s not ok though, it’ll be broken because everything is. But I don’t worry because I’ll fix these things in ‘Phase 2’ - but then there you go demanding more new stuff.

## But is there a problem?

I don’t think so. If your code is running a life support machine you need to make sure it’s capable of not breaking before you go plugging it into someone. That is important. Is making our email more secure than we make a life support machine safe something we should aspire to? No.

Nobody cares about your emails. You are not important.

If you ask anybody who understands technology they’ll tell you that digital security has never, and will never, exist. The existence of Unicorns is more likely than us ever having a secure digital world which is a crazy and dangerous idea. If people believe they are safe they’ll do stupid things - Norton or Kapersky are not going to stop me grabbing your bank account details but they make you feel a bit more secure. Our last best hope is that everyone embraces the lack of security and starts to behave a bit more sensibly when it matters and relaxing a little when it doesn’t.

## Do this.

If you are a developer you owe it to yourself and your client to take the time to write the code as cleanly as possible, to write it knowing that it’s broken, and write it knowing that you or someone else will have to patch it in the future. You are obliged to do this and more, you are responsible for consulting with the client and telling them ’no you cannot have this shiny button until the broken thing is less broken’.

If you are a client you must listen to your development team because they know more than you about digital. You must not promise your managers thing X will be delivered on day Y before the team that are building it have given you that date. If you must deliver something super quick accept that the thing you deliver will be much less than you had in your head. If you keep making your demands, if you keep desiring shiny wonder pillows what you’ll actually be buying is itchy stabby nightmares dressed as wonder pillows.

## Take homes.

We must all care when we can make a difference and not care when we can’t.
Digital security is nonsense.




