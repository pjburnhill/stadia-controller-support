Hopefully a comprehensive list of Stadia Controller-supported devices and platforms.

GitHub Page: [https://pjburnhill.github.io/stadia-controller-support/](https://pjburnhill.github.io/stadia-controller-support/)

Discussion and testing results can be found here: [https://www.reddit.com/r/Stadia/comments/ziz1kj/stadia_controller_connectivity_guide/](https://www.reddit.com/r/Stadia/comments/ziz1kj/stadia_controller_connectivity_guide/)

Jack ✅ means the 3.5mm port on the Stadia controller works as a headset port (audio in & out).

Rumble✅ means controller rumble/vibration is supported and/or enabled.

# Wireless

| Platform                 	| Works 	| Notes                                                       	|
|--------------------------	|-------	|-------------------------------------------------------------	|
| Stadia (All platforms)   	|   ✅   	| Native support                                              	|
| Others - True wireless   	|   ❌   	| TBC                                                         	|
| Others - Pseudo-wireless 	|   ✅   	| [StadiaWireless](https://github.com/helloparthshah/StadiaWireless) - Uses your phone as a bridge. Windows only. 	|

# Wired

[Desktop - Windows](https://pjburnhill.github.io/stadia-controller-support/#desktop---windows)

[Desktop - MacOS](https://pjburnhill.github.io/stadia-controller-support/#desktop---macos)

[Desktop - Other](https://pjburnhill.github.io/stadia-controller-support/#desktop---other)

[Portables](https://pjburnhill.github.io/stadia-controller-support/#portables)

[Consoles](https://pjburnhill.github.io/stadia-controller-support/#consoles)

[Media Streaming Devices](https://pjburnhill.github.io/stadia-controller-support/#media-streaming-devices)

[Browsers](https://pjburnhill.github.io/stadia-controller-support/#browsers)

## Desktop - Windows

|Platform|App/Software|Works|Jack|Rumble|Notes|
|:-|:-|:-|:-|:-|:-|
|Windows|Native support|❌|✅||No native OS-level controller support.|
||Steam|✅||✅||
||Chromium (see below)|✅||✅||
||GeforceNow App|✅||❌||
||Moonlight|✅||?|[URL](https://moonlight-stream.org/)|
||Amazon Luna App|✅||?||
||Xbox Console Companion|❌|||[URL](https://www.microsoft.com/store/apps/9wzdncrfjbd8) | [Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/iztdbbl/?utm_source=share&utm_medium=web2x&context=3)|
||Xbox Remote Play|❌|||[URL](https://www.xbox.com/en-US/consoles/remote-play) | [Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/iztdbbl/?utm_source=share&utm_medium=web2x&context=3) Works on Android.|
||Parsec|❌|||Buttons trigger multiple inputs|
||||||Xbox/DS controller emulation via 3rd party apps. See below:|
||Stadiem|✅||?|[URL](https://github.com/RexSonic/StadiEm)|
||x360ce|✅||?|[URL](https://www.x360ce.com/)|
||ReWasd|✅||?|[URL](https://www.rewasd.com/)|

&#x200B;

## Desktop - MacOS

|Platform|App/Software|Works|Jack|Rumble|Notes|
|:-|:-|:-|:-|:-|:-|
|MacOS|Native Support|❌|✅||No native OS-level controller support.|
||Steam|✅||?||
||Chromium (see below)|✅||✅|Rumble verification needed|
||Moonlight|✅||?||
||OpenEmu|✅||?|Requires manual button mapping|
||Safari|❌||||
||GeForce Now App|❌||||
||Parsec|❌|||Incorrect default mapping. Some buttons not producing input (triggers, thumb down)|

&#x200B;

## Desktop - Other

|Platform|App/Software|Works|Jack|Rumble|Notes|
|:-|:-|:-|:-|:-|:-|
|Linux|Native Support|✅|?|✅|Enable rumble with [udev rule](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/iztc1tk/?utm_source=share&utm_medium=web2x&context=3)|
|ChromeOS (Chromebooks)|Native Support|✅|✅|✅|Rumble verification needed|
||GeforceNow|✅||✅||
||xCloud|✅||✅|How to [enable rumble](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izworqw/?utm_source=share&utm_medium=web2x&context=3)|
||Moonlight|✅||?|Android app tested|

&#x200B;

## Portables

|Platform|App|Works|Jack|Rumble|Notes|
|:-|:-|:-|:-|:-|:-|
|Android||✅|✅|❌||
||Parsec|❌|||Some buttons not producing input (triggers)|
|Steam Deck||✅|?|?|Tested on SteamOS|
|iPadOS||✅|✅|❌|[Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izuahjg/?utm_source=share&utm_medium=web2x&context=3) | iPad Pro USB-C to C tested.|
|Nintendo Switch||❌|||[Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izszwp3/?utm_source=share&utm_medium=web2x&context=3)|

&#x200B;

## Consoles

|Platform|Works|Notes|
|:-|:-|:-|
|PS5|❓ Info missing|Untested|
|PS4|❌|Apparently not ([source](https://www.reddit.com/r/Stadia/comments/ripnnu/comment/hp1g6ms/?utm_source=share&utm_medium=web2x&context=3))|
|PS3|✅|[Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izxmjg4/?utm_source=share&utm_medium=web2x&context=3) | Some buttons need remapping.|
|Xbox Series X/S|❌|[Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izu9kfv/?utm_source=share&utm_medium=web2x&context=3) | Possible [remotely](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/iztdbbl/?utm_source=share&utm_medium=web2x&context=3)|
|Xbox One|❌|[Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izua017/?utm_source=share&utm_medium=web2x&context=3) | Possible [remotely](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/iztdbbl/?utm_source=share&utm_medium=web2x&context=3)|

&#x200B;

## Media streaming devices

|Platform|Works|Jack|Rumble|Notes|
|:-|:-|:-|:-|:-|
|Nvidia ShieldTV|✅|?|||
|Chromecast with Google TV|✅|?|❌||
|FireTV|❓ Info missing||||

&#x200B;

## Browsers

|Browser|App|Working|Rumble|Notes|URL|
|:-|:-|:-|:-|:-|:-|
|Chromium (Chrome, MS Edge, etc)|Native Support|✅|✅|Win, Mac & Linux(?). Rumble implementation depends on site (see below).||
||GeForce Now|✅|✅||[https://play.geforcenow.com/](https://play.geforcenow.com/)|
||xCloud|✅|✅|[how to enable](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izworqw/?utm_source=share&utm_medium=web2x&context=3) rumble|[http://xbox.com/play](http://xbox.com/play)|
|Safari (MacOS)||❌||||
|Safari (iOS/iPadOS)||✅|?|[Source](https://www.reddit.com/r/Stadia/comments/ziz1kj/comment/izuahjg/?utm_source=share&utm_medium=web2x&context=3)||
|Firefox||❌||Wrong mapping||

&#x200B;
