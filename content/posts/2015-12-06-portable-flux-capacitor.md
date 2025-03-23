---
title: Portable Flux Capacitor
date: 2015-12-06
tags: [projects]
tags:
- projects
---

This year's work holiday party was Back to the Future themed. I didn't have any good costume ideas, so with a week to go, I decided to build a portable flux capacitor to bring instead.

<div align="center"><iframe width="640" height="360" src="https://www.youtube.com/embed/MZ-XaeUl97o" frameborder="0" allowfullscreen></iframe></div> 

<br />

The first thing I did was to order some [addressable RGB LED strips][0] online. 

![First prototype](/images/fluxcapacitor/FluxCapacitor%20-%201.jpg)

I bought some clear tubing at the hardware store and cut the LED strips to size. I then used a [Teensy LC][1] that I got at the [Hackaday Superconference][2] with the FastLED library to start playing with the LEDs.

![Teensy-LC](/images/fluxcapacitor/FluxCapacitor%20-%207.jpg)

My first attempt used cardboard for the front plate, but the clear tubing was stronger than I expected and did not like being bent that much. The tube would either pop out of its place or bend the cardboard.

![Behind the LED strips](/images/fluxcapacitor/FluxCapacitor%20-%208.jpg)

I had some leftover alder wood boards from other projects, so I decided to use that instead. It was just large enough to fit the tubes, about the right size for the box I had, and strong enough to hold everything in place.

![Full board from behind](/images/fluxcapacitor/FluxCapacitor%20-%209.jpg)

After making sure everything fit, I spray painted the board silver (because that's the only color I had.)

![Full board from up front](/images/fluxcapacitor/FluxCapacitor%20-%2010.jpg)

I cut a box I had to get the board to fit and glued the rest of it together. I painted that silver as well.

![Partial box](/images/fluxcapacitor/FluxCapacitor%20-%2012.jpg)

Everything fit in place, but was loose. Thankfully, I have lots of hot glue, so I used that.

![Board in box](/images/fluxcapacitor/FluxCapacitor%20-%2016.jpg)

I cut another piece of cardboard to make a 'window', glued a piece of clear plastic onto it, and then hot glued that onto the box.

![Final setup - dark](/images/fluxcapacitor/FluxCapacitor%20-%2018.jpg)

It's nowhere near close to what it looked like in the movie, but this was more of a rushed job for a party than an actual movie prop replica. (And it's portable!) I used a USB battery pack to power it with no issues.

![Final setup - lit up](/images/fluxcapacitor/FluxCapacitor%20-%2022.jpg)

If you're interested, take a look at the Teensy [code on github][3].

![Controls](/images/fluxcapacitor/FluxCapacitor%20-%205.jpg)

The controls on the side consist of two potentiometers and a button all connected to the Teensy. They are used to adjust speed, brightness, and color changes.

<div align="center"><iframe width="640" height="360" src="https://www.youtube.com/embed/k18zvcvC6wI" frameborder="0" allowfullscreen></iframe></div>

[0]: http://www.amazon.com/gp/product/B00VQ0D2TY
[1]: https://www.pjrc.com/teensy/teensyLC.html
[2]: https://hackaday.com/tag/hackaday-superconference/
[3]: https://github.com/alvarop/flux/blob/master/fluxCapacitor/fluxCapacitor.ino
