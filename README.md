Hopefully a comprehensive list of Stadia Controller-supported devices and platforms.

GitHub Page: [https://pjburnhill.github.io/stadia-controller-support/](https://pjburnhill.github.io/stadia-controller-support/)

Discussion and testing results can be found here: [https://www.reddit.com/r/Stadia/comments/ziz1kj/stadia_controller_connectivity_guide/](https://www.reddit.com/r/Stadia/comments/ziz1kj/stadia_controller_connectivity_guide/)

Jack Audio ✅ means the 3.5mm port on the Stadia controller works as a headset port (audio in & out).

Rumble✅ means controller rumble/vibration is supported and/or enabled.

# Wireless

|Platform|Wireless|Notes|
|:-|:-|:-|
|Stadia (All platforms)|✅|Native support|
|Others - True wireless|❌|TBC|
|Others - Pseudo-wireless|✅|[StadiaWireless](https://github.com/helloparthshah/StadiaWireless) \- Uses your phone as a bridge. Windows only.|

# Wired

## Desktop - Windows

|Platform|App/Software|Wired|Jack Audio|Rumble|Notes|
|:-|:-|:-|:-|:-|:-|
|Windows|Native support|❌|✅|❌|No native OS-level controller support / Jack working system-wide|
||Steam|✅||✅||
||Chromium (see below)|✅||✅||
||GeforceNow App|✅||❌||
||Moonlight|✅||?|[URL](https://moonlight-stream.org/)|
||Amazon Luna App|✅||?||
||Xbox Console Companion|❌|||[URL](https://www.microsoft.com/store/apps/9wzdncrfjbd8) / [Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/iztdbbl/?utm_source=share&utm_medium=web2x&context=3)|
||Xbox Remote Play|❌|||[URL](https://www.xbox.com/en-US/consoles/remote-play) / [Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/iztdbbl/?utm_source=share&utm_medium=web2x&context=3) / Works on Android.|
||PS Remote Play|❌||||
||Parsec|❌|||Buttons trigger multiple inputs|
||Controller emulation via:|||||
||Stadiem|✅||?|[URL](https://github.com/RexSonic/StadiEm)|
||x360ce|✅||?|[URL](https://www.x360ce.com/)|
||ReWasd|✅||?|[URL](https://www.rewasd.com/)|

&#x200B;

## Desktop - MacOS

|Platform|App/Software|Wired|Jack Audio|Rumble|Notes|
|:-|:-|:-|:-|:-|:-|
|MacOS|Native Support|❌|✅|❌|No native OS-level controller support / Jack working system-wide|
||Steam|✅||?||
||Chromium (see below)|✅||✅|Rumble verification needed|
||Moonlight|✅||?||
||OpenEmu|✅||?|Requires manual button mapping|
||Safari|❌||||
||GeForce Now App|❌||||
||Parsec|❌|||Some buttons not producing input (triggers, thumb down)|
||Controller emulation via:|❓ Info missing||||

&#x200B;

## Desktop - Other

|Platform|App/Software|Wired|Jack Audio|Rumble|Notes|
|:-|:-|:-|:-|:-|:-|
|Linux|Native Support|✅|✅|✅|Enable rumble with [udev rule](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/iztc1tk/?utm_source=share&utm_medium=web2x&context=3) / Jack confirmed for [Fedora 36 & 37](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/j044op8/?utm_source=share&utm_medium=web2x&context=3)|
|ChromeOS (Chromebooks)|Native Support|✅|✅|✅|Rumble verification needed|
||GeforceNow|✅||✅||
||xCloud|✅||✅|How to [enable rumble](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izworqw/?utm_source=share&utm_medium=web2x&context=3)|
||Moonlight|✅||?|Android app tested|

&#x200B;

## Portables

|Platform|App|Wired|Jack Audio|Rumble|Notes|
|:-|:-|:-|:-|:-|:-|
|Android||✅|✅|❌||
||Parsec|❌|||Some buttons not producing input (triggers)|
|Steam Deck||✅|?|?|Tested on SteamOS|
|iPadOS||✅|✅|❌|[Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izuahjg/?utm_source=share&utm_medium=web2x&context=3) / iPad Pro USB-C to C tested.|
|Nintendo Switch||❌|||[Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izszwp3/?utm_source=share&utm_medium=web2x&context=3)|

&#x200B;

## Consoles

|Platform|Wired|Notes|
|:-|:-|:-|
|PS5|❓ Info missing|Possible [remotely](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/j01whc3/?utm_source=share&utm_medium=web2x&context=3)|
|PS4|❌|Apparently not ([source](https://www.reddit.com/r/Stadia/comments/ripnnu/comment/hp1g6ms/?utm_source=share&utm_medium=web2x&context=3)) / Possible [remotely](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/j01whc3/?utm_source=share&utm_medium=web2x&context=3)|
|PS3|❌|Wrong mapping ([source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/j01b3y2/?utm_source=share&utm_medium=web2x&context=3))|
|Xbox Series X/S|❌|[Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izu9kfv/?utm_source=share&utm_medium=web2x&context=3) / Possible [remotely](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/iztdbbl/?utm_source=share&utm_medium=web2x&context=3)|
|Xbox One|❌|[Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izua017/?utm_source=share&utm_medium=web2x&context=3) / Possible [remotely](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/iztdbbl/?utm_source=share&utm_medium=web2x&context=3)|

&#x200B;

## Media streaming devices

|Platform|App|Wired|Jack Audio|Rumble|Notes|
|:-|:-|:-|:-|:-|:-|
|Nvidia ShieldTV|Native support|✅|✅\*|❌|\*Jack detection [temperamental](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izymgkp/?utm_source=share&utm_medium=web2x&context=3)|
||Nvidia Game Streaming|✅||❌||
||Steam Link|✅||✅||
||Parsec|✅||❌|No input on Guide/Back button|
||Moonlight|✅||❌||
||Native Apps|❓ Info missing||||
|Chromecast with Google TV||✅|?|❌||
|FireTV||❓ Info missing||||

&#x200B;

## Browsers

|Browser|App|Wired|Rumble|Notes|
|:-|:-|:-|:-|:-|
|Chromium (Chrome, MS Edge, etc)|Native Support|✅|✅|Win, Mac & Linux(?). Rumble implementation depends on site (see below).|
||GeForce Now|✅|✅||
||xCloud|✅|✅|[how to enable](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izworqw/?utm_source=share&utm_medium=web2x&context=3) rumble|
|Safari (MacOS)||❌|||
|Safari (iOS/iPadOS)||✅|?|[Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izuahjg/?utm_source=share&utm_medium=web2x&context=3)|
|Firefox||❌||Wrong mapping|

&#x200B;
