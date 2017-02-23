---
layout: post
title:  "MacBook Pro and multiple monitors"
date:   2017-02-21 16:43:47 -0500
categories: apple
---

I've been using a Retina MacBook Pro 15-inch (early-2013) for several years now and I love
it. A lesser known fact about this MacBook is that it is capable of driving four displays
using the discrete graphics card. That's right: three simultaneous, non-mirrored
external monitors, plus the MacBook's display.

My home office has three monitors, all mounted on monitor arms. The key for this
setup is to match the monitors' vertical resolution. If you don't, a window
will "change size" or get "trapped" as you drag it from one monitor
to another. If you're not picky, it doesn't have to be expensive.
I bought a 42-inch widescreen monitor for my central display and matched the resolution with
two 19-inch monitors from the local surplus computer store.
Because of this setup, I tend to put the MacBook Pro in "clam-shell mode",
which just means the power is plugged in, the lid is down, and the MacBook
screen is not used.

The 2013 MacBook Pro has two Thunderbolt ports and one HDMI port. Through
the use of an OWC Thunderbolt 2 dock and 2 adapters, I'm able to connect
to three independent monitors.

![MacBook Pro 2013]({{ site.url }}/assets/macbook-2013.png)

I recently bought a MacBook Pro 15-inch (2016) thinking it would be a drop-in
replacement in terms of my monitor setup. My initial thought was to
buy two Thunderbolt 3 (USB-C) to Thunderbolt 2 adapters and a USB-C Digital
Multiport adapter. Unfortunately, I didn't read the fine print. Thunderbolt 3 (USB-C)
is not compatible with Mini DisplayPort. The best I could do is two external
monitors.

![MacBook Pro 2016]({{ site.url }}/assets/macbook-2016-failed.png)

I ran out to the Apple Store to do an exchange: I returned one Thunderbolt 3 (USB-C)
to Thunderbolt 2 adapter and bought the USB-C VGA Multiport adapter. Still no
luck; again, only two external monitors were detected.

![MacBook Pro 2016]({{ site.url }}/assets/macbook-2016-failed-2.png)

After some experimentation, I finally found a solution that worked.
I threw in an HDMI-to-DVI adapter, rearranged the cables, and achieved
success thusly:

![MacBook Pro 2016]({{ site.url }}/assets/macbook-2016.png)

I hope my article here will help someone who has had similar difficulties.
It is rather unfortunate that there is so much confusion around a USB port
that is supposed to be universal. I still don't understand the nuances
of this new standard, so feel free to leave me a comment below if you have
insights.

But, honestly, if I have to spend time to research how to plug in my monitors,
this isn't anywhere close to being the plug-and-play computing model that
we've (nearly) achieved all these years with the USB standard.
It seems like a backwards step to me.
