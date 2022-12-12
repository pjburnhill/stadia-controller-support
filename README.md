Hopefully a comprehensive list of Stadia Controller-supported devices and platforms.

A more readable version: [https://pjburnhill.github.io/stadia-controller-support/](https://pjburnhill.github.io/stadia-controller-support/)

Jack ✅ means the 3.5mm port on the Stadia controller works as a headset port (audio in & out).

Rumble✅ means controller rumble/vibration is supported and/or enabled.

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

| Platform 	| App/Software           	| Works 	| Jack 	| Rumble 	| Notes                                                                    	|
|----------	|------------------------	|:-----:	|:----:	|:------:	|--------------------------------------------------------------------------	|
| Windows  	| Native support         	|   ❌   	|   ✅  	|        	| No native OS-level support.                                              	|
|          	| Steam                  	|   ✅   	|      	|    ✅   	|                                                                          	|
|          	| Chromium (see below)   	|   ✅   	|      	|    ✅   	|                                                                          	|
|          	| GeforceNow App         	|   ✅   	|      	|    ❌   	|                                                                          	|
|          	| Moonlight              	|   ✅   	|      	|    ?   	| [URL](https://moonlight-stream.org/)                                     	|
|          	| Amazon Luna App        	|   ✅   	|      	|    ?   	|                                                                          	|
|          	| Xbox Console Companion 	|   ❌   	|      	|        	| [URL](https://www.microsoft.com/store/apps/9wzdncrfjbd8)                 	|
|          	| Xbox Remote Play       	|   ❌   	|      	|        	| [URL](https://www.xbox.com/en-US/consoles/remote-play) Works on Android. 	|
|          	| Parsec                 	|   ❌   	|      	|        	| Buttons trigger multiple inputs                                          	|
|          	|                        	|       	|      	|        	| Xbox/DS controller emulation via 3rd party apps. See below:              	|
|          	| Stadiem                	|   ✅   	|      	|    ?   	| [URL](https://github.com/RexSonic/StadiEm)                               	|
|          	| x360ce                 	|   ✅   	|      	|    ?   	| [URL](https://www.x360ce.com/)                                           	|
|          	| ReWasd                 	|   ✅   	|      	|    ?   	| [URL](https://www.rewasd.com/)                                           	|

### Desktop - MacOS

| Platform 	| App/Software         	| Works 	| Jack 	| Rumble 	| Notes                                                                              	|
|----------	|----------------------	|:-----:	|:----:	|:------:	|------------------------------------------------------------------------------------	|
| MacOS    	| Native Support       	|   ❌   	|   ✅  	|        	| No native OS-level support.                                                        	|
|          	| Steam                	|   ✅   	|      	|    ?   	|                                                                                    	|
|          	| Chromium (see below) 	|   ✅   	|      	|    ✅   	| Rumble verification needed                                                         	|
|          	| Moonlight            	|   ✅   	|      	|    ?   	|                                                                                    	|
|          	| OpenEmu              	|   ✅   	|      	|    ?   	| Requires manual button mapping                                                     	|
|          	| Safari               	|   ❌   	|      	|        	|                                                                                    	|
|          	| GeForce Now App      	|   ❌   	|      	|        	|                                                                                    	|
|          	| Parsec               	|   ❌   	|      	|        	| Incorrect default mapping. Some buttons not producing input (triggers, thumb down) 	|

### Desktop - Other

| Platform               	| App/Software   	| Works 	| Jack 	| Rumble 	| Notes                        	|
|------------------------	|----------------	|:-----:	|:----:	|:------:	|------------------------------	|
| Linux                  	| Native Support 	|   ✅   	|   ?  	|    ✅   	| Enable rumble with udev rule 	|
| ChromeOS (Chromebooks) 	| Native Support 	|   ✅   	|   ✅  	|    ✅   	| Rumble verification needed   	|
|                        	| GeforceNow     	|   ✅   	|      	|    ✅   	|                              	|
|                        	| xCloud         	|   ✅   	|      	|    ✅   	| how to enable rumble         	|
|                        	| Moonlight      	|   ✅   	|      	|    ?   	| Android app tested           	|

### Portables

| Platform        	| App    	| Works 	| Jack 	| Rumble 	| Notes                                       	|
|-----------------	|--------	|:-----:	|:----:	|:------:	|---------------------------------------------	|
| Android         	|        	|   ✅   	|   ✅  	|    ❌   	|                                             	|
|                 	| Parsec 	|   ❌   	|      	|        	| Some buttons not producing input (triggers) 	|
| Steam Deck      	|        	|   ✅   	|   ?  	|    ?   	| Tested on SteamOS                           	|
| iPadOS          	|        	|   ✅   	|   ✅  	|    ❌   	| Source. iPad Pro USB-C to C tested.         	|
| Nintendo Switch 	|        	|   ❌   	|      	|        	| Source                                      	|

### Consoles

| Platform        	|      Works     	| Notes                     	|
|-----------------	|:--------------:	|---------------------------	|
| PS5             	| ❓ Info missing 	| Untested                  	|
| PS4             	|        ❌       	| Apparently not (source)   	|
| Xbox Series X/S 	|        ❌       	| Source. Possible remotely 	|
| Xbox One        	|        ❌       	| Source. Possible remotely 	|

### Media streaming devices

|          Platform         	|      Works     	| Jack 	| Rumble 	| Notes 	|
|:-------------------------:	|:--------------:	|:----:	|:------:	|-------	|
|      Nvidia ShieldTV      	|        ✅       	|   ?  	|        	|       	|
| Chromecast with Google TV 	|        ✅       	|   ?  	|    ❌   	|       	|
|           FireTV          	| ❓ Info missing 	|      	|        	|       	|

### Browsers

| Browser                         	| App            	| Working 	| Rumble 	| Notes                                                                   	| URL                          	|
|---------------------------------	|----------------	|:-------:	|:------:	|-------------------------------------------------------------------------	|------------------------------	|
| Chromium (Chrome, MS Edge, etc) 	| Native Support 	|    ✅    	|    ✅   	| Win, Mac & Linux(?). Rumble implementation depends on site (see below). 	|                              	|
|                                 	| GeForce Now    	|    ✅    	|    ✅   	|                                                                         	| https://play.geforcenow.com/ 	|
|                                 	| xCloud         	|    ✅    	|    ✅   	| how to enable rumble                                                    	| http://xbox.com/play         	|
| Safari (MacOS)                  	|                	|    ❌    	|        	|                                                                         	|                              	|
| Safari (iOS/iPadOS)             	|                	|    ✅    	|    ?   	| Source.                                                                 	|                              	|
| Firefox                         	|                	|    ❌    	|        	| Wrong mapping                                                           	|                              	|
