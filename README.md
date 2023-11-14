# 🎹 Krypton

Krypton is an audio player library primarily meant for Discord Bots.
It is heavily based off the amazing [**Lavaplayer**](https://github.com/sedmelluq/lavaplayer)

- [**Support Server #krypton**](https://discord.gg/Vkbmb8kuH4)

## ❓ Why?

Lavaplayer is a great library, and it's been heavily battle-tested, so why not just use it?

While developing my bot, I ran into a lot of issues developing features that required me to push the boundaries of what
Lavaplayer could do, often leading me to come up with sketchy hacks that weren't very consistent.

I thought if I could port Lavaplayer to Kotlin and rewrite some parts to use coroutines, I could achieve some of my
goals. Obviously, it was a much bigger undertaking than I imagined and I ended up just not going forward with it.

> **Discord is stripping verification from music bots, so why work on this?**   
> I want to improve my Kotlin skills and learn how to use coroutines more efficiently, so what better way to do that
> than writing an asynchronous audio streaming library!

## 🤔 What's Different?

Obviously, if I just rewrote Lavaplayer but in Kotlin, there wouldn't be much of a point to this library. But instead,
this library will be focused on using Kotlin multi-platform, coroutines, and other Kotlin-specific features to hopefully
make it more efficient and easier to use.

This does mean it will be unusable in Java, so if you need java-interop then you must use Lavaplayer.

## 📦 Features

I hope to have complete feature parity with Lavaplayer but with obviously a little extra to make it a worthy alternative.

- Lavaplayer Feature Parity
    - Audio Filters
    - Custom Item Sources
    - Wide range of supported formats (WAV, Mp3, Flac, Matroska / WebM, MP4 / M4A, etc...)
    - Precise track seeking
- Krypton-specific stuff
  - Asynchronous API via Coroutines
  - Kotlin Multiplatform, see [#1](https://github.com/krypton-lib/krypton/issues/1)
  - _we're still focussing on getting everything working! hang tight!_

### 📦 Supported Formats

Although Lavaplayer supports a good number of formats, it only implements the bare minimum for playback of the default sources,
often leading to issues where a file with a very specific configuration will not be playable.

Krypton will support all formats that Lavaplayer supports, but will attempt to implement as much of the formats as possible to
support as many different file variants.

## 🚀 Any examples?

You'll have to stay tuned for the open-source release ;)

<!--
We do have two demo projects, one using [Kord](https://kord.dev) and another using [JDA](https://jda.wiki).

> [!WARNING]
> The Kord demo is still being used as a playground & debug area, I recommend looking at the JDA demo for now.

- [JDA](demo-jda)
- [Kord](demo-kord) 
-->

---

[viztea](https://vzt.gay) &bull; Licensed under Apache 2.0
