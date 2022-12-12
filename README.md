Hopefully a comprehensive list of Stadia Controller-supported devices and platforms.

A more readable version: [https://pjburnhill.github.io/stadia-controller-support/](https://pjburnhill.github.io/stadia-controller-support/)

## Wireless

| Platform                 	| Works 	| Notes                                                       	|
|--------------------------	|-------	|-------------------------------------------------------------	|
| Stadia (All platforms)   	|   ✅   	| Native support                                              	|
| Others - True wireless   	|   ❌   	| TBC                                                         	|
| Others - Pseudo-wireless 	|   ✅   	| [StadiaWireless](https://github.com/helloparthshah/StadiaWireless) - Uses your phone as a bridge. Windows only. 	|

## Wired

[Desktop - Windows](https://pjburnhill.github.io/stadia-controller-support/#desktop---windows)

[Desktop - MacOS](https://pjburnhill.github.io/stadia-controller-support/#desktop---macos)

[Desktop - Other](https://pjburnhill.github.io/stadia-controller-support/#desktop---other)

[Portables](https://pjburnhill.github.io/stadia-controller-support/#portables)

[Consoles](https://pjburnhill.github.io/stadia-controller-support/#consoles)

[Media Streaming Devices](https://pjburnhill.github.io/stadia-controller-support/#media-streaming-devices)

[Browsers](https://pjburnhill.github.io/stadia-controller-support/#browsers)

### Desktop - Windows

| Platform                                        	| App/Software           	| Works 	| Features 	| Notes                           	|
|-------------------------------------------------	|------------------------	|:-----:	|:--------:	|---------------------------------	|
| Windows                                         	| Native support         	|   ❌   	|  Jack ✅  	| No native OS-level support.     	|
|                                                 	| Steam                  	|   ✅   	|  Rumble✅ 	|                                 	|
|                                                 	| Chromium (see below)   	|   ✅   	|  Rumble✅ 	|                                 	|
|                                                 	| GeforceNow App         	|   ✅   	|  Rumble❌ 	|                                 	|
|                                                 	| Moonlight              	|   ✅   	| Rumble ? 	| [URL](https://moonlight-stream.org/)|
|                                                 	| Amazon Luna App        	|   ✅   	| Rumble ? 	|                                 	|
|                                                 	| Xbox Console Companion 	|   ❌   	|          	| URL                             	|
|                                                 	| Xbox Remote Play       	|   ❌   	|          	| URL. Works on Android.          	|
|                                                 	| Parsec                 	|   ❌   	|          	| Buttons trigger multiple inputs 	|
| Xbox/DS controller emulation via 3rd party apps 	|                        	|       	|          	|                                 	|
|                                                 	| Stadiem                	|   ✅   	| Rumble ? 	| URL                             	|
|                                                 	| x360ce                 	|   ✅   	| Rumble ? 	| URL                             	|
|                                                 	| ReWasd                 	|   ✅   	| Rumble ? 	| URL                             	|

### Desktop - MacOS

| Platform 	| App/Software         	| Works 	|           Features           	| Notes                                                                              	|
|----------	|----------------------	|:-----:	|:----------------------------:	|------------------------------------------------------------------------------------	|
| MacOS    	| Native Support       	|   ❌   	|            Jack ✅            	| No native OS-level support. Jack ✅ Rumble❌                                         	|
|          	| Steam                	|   ✅   	|           Rumble ?           	|                                                                                    	|
|          	| Chromium (see below) 	|   ✅   	| Rumble✅(verification needed) 	|                                                                                    	|
|          	| Moonlight            	|   ✅   	|           Rumble ?           	|                                                                                    	|
|          	| OpenEmu              	|   ✅   	|           Rumble ?           	| Requires manual button mapping                                                     	|
|          	| Safari               	|   ❌   	|                              	|                                                                                    	|
|          	| GeForce Now App      	|   ❌   	|                              	|                                                                                    	|
|          	| Parsec               	|   ❌   	|                              	| Incorrect default mapping. Some buttons not producing input (triggers, thumb down) 	|

### Desktop - Other

| Platform               	| App/Software   	| Works 	|                Features               	| Notes                        	|
|------------------------	|----------------	|:-----:	|:-------------------------------------:	|------------------------------	|
| Linux                  	| Native Support 	|   ✅   	|            Jack ? Rumble ✅            	| Enable rumble with udev rule 	|
| ChromeOS (Chromebooks) 	| Native Support 	|   ✅   	| Jack ✅ Rumble ✅ (verification needed) 	|                              	|
|                        	| GeforceNow     	|   ✅   	|                Rumble ✅               	|                              	|
|                        	| xCloud         	|   ✅   	|                Rumble ✅               	| how to enable rumble         	|
|                        	| Moonlight      	|   ✅   	|                Rumble ?               	| Android app tested           	|

### Portables

| Platform        	| App    	| Works 	|     Features    	| Notes                                       	|
|-----------------	|--------	|:-----:	|:---------------:	|---------------------------------------------	|
| Android         	|        	|   ✅   	|  Jack ✅ Rumble❌ 	|                                             	|
|                 	| Parsec 	|   ❌   	|                 	| Some buttons not producing input (triggers) 	|
| Steam Deck      	|        	|   ✅   	| Jack ? Rumble ? 	| Tested on SteamOS                           	|
| iPadOS          	|        	|   ✅   	|  Jack ✅ Rumble❌ 	| Source. iPad Pro USB-C to C tested.         	|
| Nintendo Switch 	|        	|   ❌   	|                 	| Source                                      	|

### Consoles

| Platform        	|      Works     	| Notes                     	|
|-----------------	|:--------------:	|---------------------------	|
| PS5             	| ❓ Info missing 	| Untested                  	|
| PS4             	|        ❌       	| Apparently not (source)   	|
| Xbox Series X/S 	|        ❌       	| Source. Possible remotely 	|
| Xbox One        	|        ❌       	| Source. Possible remotely 	|

### Media streaming devices

|          Platform         	|      Works     	|     Features    	|
|:-------------------------:	|:--------------:	|:---------------:	|
| Nvidia ShieldTV           	| ✅              	| Jack ? Rumble ? 	|
| Chromecast with Google TV 	| ✅              	| Jack ? Rumble ❌ 	|
| FireTV                    	| ❓ Info missing 	|                 	|

### Browsers

| Browser                         	| App            	| Working 	| Features 	| Notes                                                                   	|
|---------------------------------	|----------------	|:-------:	|:--------:	|-------------------------------------------------------------------------	|
| Chromium (Chrome, MS Edge, etc) 	| Native Support 	|    ✅    	| Rumble ✅ 	| Win, Mac & Linux(?). Rumble implementation depends on site (see below). 	|
|                                 	| GeForce Now    	|    ✅    	| Rumble ✅ 	|                                                                         	|
|                                 	| xCloud         	|    ✅    	| Rumble ✅ 	| how to enable rumble                                                    	|
| Safari (MacOS)                  	|                	|    ❌    	|          	|                                                                         	|
| Safari (iOS/iPadOS)             	|                	|    ✅    	| Rumble ? 	| Source.                                                                 	|
| Firefox                         	|                	|    ❌    	|          	| Wrong mapping                                                           	|
