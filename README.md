# HyuGram

![AyuGram Logo](.github/AyuGram.png)

## What the hell nah bro

**HGram** is a fork of [AyuGram](https://github.com/ayugram/ayugram4a) with broken scripts. 



*And, well, it's an Iranian Telegram fork with floating TV or something.*

## Features list
todo: make this asshole readme
- Message filters (e.g. hide ads)
- Customizable edited/deleted marks
- Local Telegram Premium
- Sync read states and message history with AyuSync
- Up to stream Telegram version (*snidely*)

Note that we use **Crashlytics**.
If you don't want to send crash reports, you can disable it in **exteraGram Preferences**.

**AyuGram4A** does **NOT** include proprietary **exteraGram** features.

## Preview

💖 **Made with extera's Monet theme.**

<img src='.github/demos/demo1.png' width='210'> <img src='.github/demos/demo2.png' width='210'>

<img src='.github/demos/demo3.png' width='210'> <img src='.github/demos/demo4.png' width='210'>

<img src='.github/demos/demo5.png' width='210'> <img src='.github/demos/demo6.png' width='210'>

## Downloads?

Follow our **[Telegram channel](https://t.me/ayugram1338)** and join our [chat](https://t.me/ayugramchat)!

Preview versions can be downloaded
from the **[dedicated topic](https://t.me/ayugramchat/1238)**.

## Want to throw some money?

Developing AyuGram is not such a simple task.
**We'd be grateful for any donation <3**

All available methods can be found **[here](https://ayusync.cloud/ui/donate)**.

## AyuSync? What is it?

**AyuSync** is our synchronization service.
You can either use official server or host your own.
It can sync read states and message history.

Server backend can be found **[here](https://github.com/AyuGram/AyuSyncBackend)**.

## Want to contribute?

I'd be grateful for any contribution, since I don't really like Java. :)

**Work on any feature you want.**

## Want to fork?

Well, just fork it.

**But please, don't forget to mention us in your README.**

## How to build

1. Clone source code using `git clone https://github.com/AyuGram/AyuGram4A.git`
2. Open the project in Android Studio. It should be opened, **not imported**
3. Implement the `AyuMessageUtils` & `AyuHistoryHook` classes. It's not that hard, but if you're
   making your **very** own fork, then you should take some time to write this part of code. Or you can search for a reversed version :)
4. Replace `google-services.json` (we don't want to see crash reports from your app...)
5. Generate application certificate and fill API_KEYS:
   ```
   APP_ID = 6
   APP_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
   MAPS_V2_API = abcdef12345678
   
   SIGNING_KEY_PASSWORD = password
   SIGNING_KEY_ALIAS = alias
   SIGNING_KEY_STORE_PASSWORD = password
   ```
6. You are ready to compile `AyuGram`

- **AyuGram** can be built with **Android Studio** or from the command line with **Gradle**:

```
./gradlew assembleAfatRelease
```

## AyuGram Localization

[![Crowdin](https://badges.crowdin.net/ayugram/localized.svg)](https://crowdin.com/project/ayugram)
[![Crowdin](https://badges.crowdin.net/exteralocales/localized.svg)](https://crowdin.com/project/exteralocales)

We have our own **[Crowdin](https://crowdin.com/project/ayugram)**.

But since **AyuGram** is based on **exteraGram**, also join their project
at **[Crowdin](https://crowdin.com/project/exteralocales)**!

## Credits

- **[exteraGram](https://github.com/exteraSquad/exteraGram)**
- [Telegraher](https://github.com/nikitasius/Telegraher)
- [Cherrygram](https://github.com/arsLan4k1390/Cherrygram)
- [Nagram](https://github.com/NextAlone/Nagram)
- [Telegram FOSS](https://github.com/Telegram-FOSS-Team/Telegram-FOSS)
