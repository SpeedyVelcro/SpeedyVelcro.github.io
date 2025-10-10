---
title: Back in Business (Musically Speaking)
date: 2025-10-10 15:08:30 +0100
---
Alright strap in folks because I'm giving you an update on what I'm
doing and what's coming up, specifically in terms of MIDIs.

You may have noticed that I've done very little in the way of making
MIDIs lately, and that's because like most people, I'm getting sick
and tired of Windows.

My previous workflow used Roland Sound Canvas VA - an official emulator
for several SoundCanvas devices in VST form - which only worked on
macOS and Windows. I've moved most other stuff I'm doing onto Linux,
but getting Windows VSTs running on Linux is still a bit of a pain in
the ass. I'm sure it's possible, but I still haven't cracked that nut
yet.

So my music workflow had to remain on Windows, with me switching over
to my Windows partition every time I want to write some music. Which
I didn't really end up doing because that felt like a bit of a
headache. It's a bit of a first-world problem, but ideally when
inspiration strikes you want to be able to just fire up your music
tools and go.

This problem was coupled with the fact that Roland has
[discontinued](https://rolandcloud.com/news/sound-canvas-va-is-being-discontinued)
Sound Canvas VA. The music industry will not be satisfied until every
software tool is a nightmare to use, it seems. Luckily, I bought
Sound Canvas VA back when you could still get a permanent license, but
it's still a bit nerve-wracking to be using deprecated software that
won't be updated anymore. Especially since there's a lot _to_ update,
seeing as it's - in my experience - buggy and annoying to use.

So I basically needed to migrate my workflow to something else. The
obvious answer would have been to use physical hardware instead, but
I was short on both money and time (due to studying, graduating, and
starting a new job) so that had to wait.

Anyway, since then my circumstance have stabilised quite significantly,
so I've been able to order some physical hardware. Behold, the
SC-88 Pro:

![SC-88 Pro](/assets/images/blog/2025-10-10-back-in-business/sc-88-pro.png)

Well, that's the second one I bought, because the first one
unfortunately died in transit. The ebay seller assured me that they
had tested it so I guess we can chalk this up to a freak accident of
nature that happened in the cargo hold of a plane.

I don't have a recording of the first one not making any sound (for
fairly obvious reasons - there's nothing to record), but here's a nice
view of a failed memory test:

![SC-88 Pro displaying failed memory test](/assets/images/blog/2025-10-10-back-in-business/failed-memory-test.jpg)

(I assume the NG stands for "Not Good" or something)

Anyway, I had to settle for a partial refund from the seller, so I
still have the first unit. Audio technicians in the area are generally
reluctant to touch synthesizers, so I cracked it open to figure out
if I could find the problem myself:

![Capacitors leaking brown fluid](/assets/images/blog/2025-10-10-back-in-business/leaky-capacitors.jpg)

So it seems I have a few leaky capacitors (two of the three are
pictured above). These are on the audio board, so I'm not sure if that
explains the memory failure, but it definitely explains the lack of
audio output. It could be some king of glue, of course, but the colour
makes it suspicious enough that it's probably worth just replacing them
and seeing what happens.

I have all the supplies now, so I just need to find the time to have
a crack at the repair. Although it might take me a while to get around
to it; seeing as I now have a working SoundCanvas there's not much
urgency to it.

Speaking of that working SoundCanvas, I've been playing around with it
and testing all my old MIDIs on it to see if they sound the same. If
you've been following my [socials](/social), you've probably already
seen me posting about this. I'll probably be uploading a few more
renders of my old MIDIs with a camera pointed at the LCD panel in the
coming weeks.

There
are some subtle differences, of course, but it's hard to say whether
they're caused by poor emulation by Sound Canvas VA, or by me
forgetting or otherwise failing to export some of the automation
correctly to the MIDI files.

It's also made me realise - because I'm now using just the one external
synth instead of a VST that resets every time I load a new project -
that I completely forgot to add reset messages to the beginning of
all my MIDIs. So that's something I'll have to keep an eye on in the
future.

I've also been setting up REAPER on my Fedora Linux install, and
faffing about with the audio drivers to get it actually working. Long
story short, as of today I can now properly make music on my daily
driver operating system. This means I'll be getting back into making
music again, although I imagine I'm a bit rusty (Was I ever not rusy?)

But watch this space anyway!

In the meantime I've also been doing some game dev stuff, which you
might have seen on my [GitHub](https://github.com/SpeedyVelcro), but
I think that's best saved for another blog post.

Until next time!

