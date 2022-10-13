# 🎹 Krypton

Krypton is an audio player library primarily meant for Discord Bots.
It is heavily based off the amazing [**Lavaplayer**](https://github.com/sedmelluq/lavaplayer)

- [**Support Server #krypton**](https://discord.gg/Vkbmb8kuH4)

## ❓ Why?

While developing my bot, [**Mixtape**](https://mixtape.systems), I ran into a lot of issues where lavaplayer 
just wasn't flexible enough for me.

I went on to convert almost everything to Kotlin ([my fork](https://github.com/mixtape-oss/lavaplayer)),
but it still had some limitations, and I wasn't very confident that I could successfully rewrite parts 
of lavaplayer without breaking it.

So, I'm planning out a [**coroutine**](https://github.com/kotlin/kotlinx.coroutines)-driven API that will hopefully
be more efficient than lavaplayer when it has matured.

> **Discord is stripping verification from music bots, so why work on this?**   
> I want to improve my Kotlin skills and learn how to use coroutines more efficiently, so what better way to do that 
> than writing an asynchronous audio streaming library!

## 📦 Features

- Lavaplayer Feature Parity
  - Audio Filters
  - Custom Source Managers
  - Wide range of supported formats (WAV, Mp3, Flac, Matroska / WebM, MP4 / M4A, etc...)
  - Precise track seeking
- Krypton-specific stuff
  - Asynchronous API via Coroutines
  - A new [experimental frame pipeline]
  - Kotlin Multiplatform, see [#1](https://github.com/krypton-lib/krypton/issues/1)
  - _we're still flushing out this library, stay tuned!_

> **Is this Kotlin-only?**    
> Unfortunately, we depend on Kotlin-specific features such as suspending features which are basically 
> unusable in Java, we recommend using lavaplayer if Java-interop is a must.

## 🚀 Any examples?

I don't have any examples of how to use Krypton for now!
Make sure to stay tuned in our **Support Server**

---

[melike2d](https://www.dimensional.fun) &bull; Licensed under Apache 2.0
