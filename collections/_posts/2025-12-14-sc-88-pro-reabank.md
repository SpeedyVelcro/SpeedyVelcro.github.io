---
title: SC-88 Pro reabank
date: 2025-12-14 08:51:00 +0000
---
I've been noodling around with my SC-88 Pro for a while. Haven't made
anything worth sharing yet, but one by-product that's come out of this
is a reabank file, which is available for download on my GitHub now.

If you want to skip the spiel and just download it, you can get it
on the GitHub page
[here](https://github.com/SpeedyVelcro/sc-88-pro-reabank) (scroll down
to the usage section).

<!-- more -->

As you may know I make MIDIs in REAPER, and you can make this process
a little easier by loading in a reabank file. It's basically a
specification of all the instruments that your synth (or VST) supports.
This allows you to select the right bank/program CCs a little easier
without having to flip back and forth between your DAW and the manual.

Currently this reabank contains pretty much everything you should need
for a normal MIDI, i.e. all capital instruments and variation
instruments are represented, which means you should be covered for
everything in the Roland GS standard as it existed when the SC-88 Pro
came out.

I also added support for the default, SC-55 and SC-88 maps. I don't use
this, but I felt like adding them for completeness. Unfortunately I
realised towards the end that I missed the native map (the default map,
LSB 0, uses whatever map your device is set to, while the native map,
LSB 3, overrides the device to force the native map). I'm not quite
sure yet whether this is an issue. Would you typically wnat to use the
default map or the native map when making a MIDI for the SC-88 Pro? You
could argue both ways, since the default map allows the user to
override the map if they so choose, but the native map allows you to
force the MIDI to sound as intended. I checked just now and sending
a GS reset doesn't override whatever you've done with the map buttons
on the front of your SC-88 Pro, so this is actually quite a
consequential question for MIDI design.

Either way, adding the native maps is the next thing I'm doing when I
get the chance. If only for completeness sake. Shouldn't take too long
since it's mostly just a copy-paste job.

There's also a few more features I want to add:
- CM-64 Map
- User Instruments
- Adding "(legato)" to the names of instruments that support it, to
  differentiate them from identically-named non-legato instruments.

Also, here's a fun (or depressing) fact: I wrote out pretty much the
entire reabank file by hand. I'm sure you could automate it, but given
that I'm sourcing the instruments from a manual which is *already*
littered with formatting errors - not to mention I'm not even sure
how consistent the construction of the PDF is - I don't think an
automated process would necessarily be any less error-prone. And, of
course, may I direct your attention to the
[relevant xkcd](https://xkcd.com/1319/). It was pretty educational
working through the instrument table manually (I got a feel for how the
GS standard is laid out) and I don't mind this kind of detailed work
anyway (maybe that's autism or something idk).

Anyway that's pretty much it; check out the reabank file on GitHub
[here](https://github.com/SpeedyVelcro/sc-88-pro-reabank), or if you
just want to go straight to the download go to the latest release page
[here](https://github.com/SpeedyVelcro/sc-88-pro-reabank/releases/latest).

PS: this is a blog post, so it's liable to be out of date if I make
updates to the reabank file. Go to the GitHub for info on the latest
version. I'm currently deciding whether I want permanent pages for
literally all my projects, or just blog posts for the small ones, but
for now I'm just going for blog posts because it's quicker than
figuring out how I want to fit them into the layout of my website.
