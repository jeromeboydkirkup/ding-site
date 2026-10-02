---
title: Ding - Support
layout: default
---

Ding is a call bell for iPhone and iPad: tap the big bell and it rings,
loudly and instantly. Hold it to keep ringing. Swipe the strip at the
bottom to choose between twelve bells.

## Frequently asked questions

**The bell rings even when my phone is on silent. Is that a bug?**
No — it's the point. A call bell that can be accidentally muted fails at
its one job, so Ding plays through the silent switch by default, like an
alarm app. If you'd rather it respect the switch, turn off
*Settings → Ring on silent switch* inside the app.

**It's not loud enough.**
Turn the hardware volume all the way up (the app shows a banner with a
volume bar until you do) and check *Settings → Volume boost* is on. The
iPhone's speaker is loudest with the phone lying on a hard surface,
speaker edge facing you.

**Sound comes out of my Bluetooth speaker / AirPods.**
By default Ding forces the built-in speaker. If you *want* it on a
connected speaker, enable *Settings → Play through connected speaker*.

**Does it keep ringing if the screen locks?**
A ring you started (including press-and-hold) finishes even if the screen
locks mid-ring. The app never makes sound on its own.

**Can I make my own bells?**
Yes — scroll the picker to *My Bells* and tap **+**. Pick any look and
colour, then choose a sound: tweak a built-in bell (pitch, decay,
brightness, strike), record up to 5 seconds with the microphone, or import
an audio file. Recordings and imports are trimmed, normalised and get the
same per-tap variation as the built-in bells. You can keep up to 20.

**Why does Ding ask for microphone access?**
Only because you tapped Record for a custom bell. The recording is
processed and stored on your device and is never uploaded — Ding makes no
network requests at all. Decline the permission and everything else still
works.

**Can I use my own bell recording for a built-in bell?**
Also yes, when building from source: place a WAV named after a bell (for
example `hotel.wav`) in `Documents/Samples/` or `Ring/Samples/` — see the
project README for accepted names.

**Which devices are supported?**
iPhone and iPad running iOS 17 or later. No account, no network; the only
(optional) permission is the microphone, for recording custom bells.

## Privacy

Ding collects nothing. The full (short) policy is on the
[privacy policy page](privacy-policy.html).

## Contact

**hello@gomycro.com**
