
![Logo](https://raw.githubusercontent.com/oxxx1mif/oxxx1mif/main/bannerImp.jpg)


# ImperGram

based on [Telegram](https://github.com/DrKLO/Telegram)

## Description

This version of ImperGram is based on the official Telegram source code.

This version uses only the ImperGram features listed below:

- SoundCloud Player

If you need the full version of ImperGram, get the one based on the Cherrygram source code.
## License

[GNU General Public License v2.0](https://github.com/DrKLO/Telegram/blob/master/LICENSE)

## Creating your Telegram Application

We welcome all developers to use our API and source code to create applications on our platform.
There are several things we require from **all developers** for the moment.

1. [**Obtain your own api_id**](https://core.telegram.org/api/obtaining_api_id) for your application.
2. Please **do not** use the name Telegram for your app — or make sure your users understand that it is unofficial.
3. Kindly **do not** use our standard logo (white paper plane in a blue circle) as your app's logo.
3. Please study our [**security guidelines**](https://core.telegram.org/mtproto/security_guidelines) and take good care of your users' data and privacy.
4. Please remember to publish **your** code too in order to comply with the licences.

## API, Protocol documentation

Telegram API manuals: https://core.telegram.org/api

MTproto protocol manuals: https://core.telegram.org/mtproto

## Compilation Guide

**Note**: In order to support [reproducible builds](https://core.telegram.org/reproducible-builds), this repo contains dummy release.keystore,  google-services.json and filled variables inside BuildVars.java. Before publishing your own APKs please make sure to replace all these files with your own.

1. Download the ImperGram
```
git clone https://github.com/ImperGram/ImperGram.git 
```
2. Copy your release.keystore into TMessagesProj/config
3. Fill out RELEASE_KEY_PASSWORD, RELEASE_KEY_ALIAS, RELEASE_STORE_PASSWORD in gradle.properties to access your  release.keystore
4.  Go to https://console.firebase.google.com/, create two android apps with application IDs org.telegram.messenger , org.telegram.messenger.beta, tw.gua.impergramX, tw.gua.impergramX.beta turn on firebase messaging and download google-services.json, which should be copied to the same folder as TMessagesProj.
5. Open the project in the Studio (note that it should be opened, NOT imported).
6. Fill out values in TMessagesProj/src/main/java/org/telegram/messenger/BuildVars.java – there’s a link for each of the variables showing where and which data to obtain.
7. You are ready to compile ImperGram.

## Authors

- [@oxxximif](https://t.me/oxxximif)

