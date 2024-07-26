# 🎹 Krypton

Krypton is an audio player library primarily meant for Discord Bots.
[**Lavaplayer**](https://github.com/sedmelluq/lavaplayer) was a large driving force for this project.

- [**Support Server #krypton**](https://discord.gg/Vkbmb8kuH4)

## 📦 Features

- Audio Stuff
  - Filters
  - WAV, MP3, FLAC, MKV, and MP4 formats
  - AAC, MP3, FLAC, and OPUS codecs
  - Precise track seeking
- Krypton-specific stuff
  - Asynchronous & Idiomatic Kotlin API
  - Kotlin Multiplatform, see [#1](https://github.com/krypton-lib/krypton/issues/1)
  - _and more with time._

### ☕ Java Interop

Krypton will likely never be able to interop with Java due to our extensive use of `suspend`ing functions. 

I am not against a thin future-based wrapper like [Lavalink.kt](https://github.com/kordlib/lavalink.kt)'s 
compatiblity layer but this will not be a priority. If you need java-interop then just use lavaplayer.

### 📦 Format Support

Lavaplayer supports quite a few container formats but it only attempts to implement the bare minimum to enable playback. 

This will often lead to issues where an exotic configuration format is likely to raise an error, though it is usually a 
simple fix after studying the spec and running the file through ffprobe a couple times.

Krypton will support the same formats as Lavaplayer (hopefully more with time) but will focus on implementing the majority, 
if not the entire spec, as a standalone library apart of [saisei](https://github.com/krypton-lib/saisei).

<!--Although Lavaplayer supports a good number of formats, it only implements the bare minimum for playback of the default sources,
often leading to issues where a file with a very specific configuration will not be playable.

Krypton will support all formats that Lavaplayer supports, but will attempt to implement as much of the formats as possible to
support as many different file variants.-->

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
