ArchiSteamFarm
===================

[![Gitter](https://img.shields.io/gitter/room/JustArchi/ArchiSteamFarm.svg?label=Chat&maxAge=60)](https://gitter.im/JustArchi/ArchiSteamFarm)
[![Build Status (Windows)](https://img.shields.io/appveyor/ci/JustArchi/ArchiSteamFarm.svg?label=Windows&maxAge=60)](https://ci.appveyor.com/project/JustArchi/ArchiSteamFarm)
[![Build Status (Mono)](https://img.shields.io/travis/JustArchi/ArchiSteamFarm.svg?label=Mono&maxAge=60)](https://travis-ci.org/JustArchi/ArchiSteamFarm)
[![GitHub Release](https://img.shields.io/github/release/JustArchi/ArchiSteamFarm.svg?label=Latest&maxAge=60)](https://github.com/JustArchi/ArchiSteamFarm/releases/latest)
[![Github All Releases](https://img.shields.io/github/downloads/JustArchi/ArchiSteamFarm/total.svg?label=Downloads&maxAge=60)](https://github.com/JustArchi/ArchiSteamFarm/releases)
[![Paypal Donate](https://img.shields.io/badge/Paypal-donate-yellow.svg)](https://www.paypal.me/JustArchi/1usd)
[![Steam Donate](https://img.shields.io/badge/Steam-donate-yellow.svg)](https://steamcommunity.com/tradeoffer/new/?partner=46697991&token=0ix2Ruv_)

---

ASF is a C# application that allows you to farm steam cards using multiple steam accounts simultaneously. Unlike Idle Master which works only for one account at given time, requires steam client running in background, and launches additional processes imitiating "game playing" status, ASF doesn't require any steam client running in the background, doesn't launch any additional processes and is made to handle unlimited steam accounts at once. In addition to that, it's meant to be run on servers or other desktop-less machines, and features full Mono support, which makes it possible to launch on any Mono-supported operating system, such as Windows, Linux or OS X. ASF is based on, and possible, thanks to [SteamKit2](https://github.com/SteamRE/SteamKit).

ASF doesn't require and doesn't interfere in any way with Steam client. In addition to that, it no longer requires exclusive access to given account, which means that you can use your main account in Steam client, and use ASF for farming the same account at the same time. If you decide to launch a game, ASF will get disconnected, and resume farming once you finish playing your game, being as transparent as possible.

**Core features**

- Automatic farming of available games with card drops using any number of active accounts
- No requirement of running or even having official Steam client installed
- Guarantee of being VAC-free
- Complex error-reporting mechanism, allowing ASF to be smart and resume farming even in case of Steam or networking problems
- Customizable cards farming algorithm which will push performance of cards farming to the maximum
- Offline farming, allowing you to skip in-game status and not confuse your friends anymore
- Advanced support for alt accounts, including ability to redeem keys, redeem gifts, accept trades and more through a simple Steam chat
- Support for latest Steam security features, including SteamGuard, SteamParental and Two-Factor authentication
- Unique ASF 2FA mechanism allowing ASF to act as a mobile authenticator (if needed)
- StreamTradeMatcher integration allowing ASF to help you in completing your steam badges by accepting dupe trades
- Full Mono support, cross-OS compatibility, official support for Windows, Linux and OS X
- ...and many more!

**Setting up / Help**

Detailed guide regarding setting up and using ASF is available on **[our wiki](https://github.com/JustArchi/ArchiSteamFarm/wiki)**.

**Supported / Tested operating systems:**

ASF officially supports Windows, Linux and OS X operating systems, including following tested variants:

 - Windows 10 (Native)
 - Windows 8.1 (Native)
 - Windows 7 (Native)
 - Windows Vista (Native)
 - Debian 9 Stretch (Mono)
 - Debian 8 Jessie (Mono)
 - Ubuntu 16.04 (Mono)
 - OS X 10.11 (Mono)
 - OS X 10.7 (Mono)
 
However, any **[currently supported Windows](http://windows.microsoft.com/en-us/windows/lifecycle)** should run ASF flawlessly (with latest .NET framework), as well as any **[Mono-powered OS](http://www.mono-project.com/docs/about-mono/supported-platforms/)** (with latest Mono).
