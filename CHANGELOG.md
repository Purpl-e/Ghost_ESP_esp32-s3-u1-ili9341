// changelog.md 

# 1.4.5

## 🛠️ Core Improvements

- Added starting logs to capture commands - @jaylikesbunda
- Improved WiFi connection logic - @jaylikesbunda
- Added support for variable display timeout on TWatch S3 - @jaylikesbunda
- Revise stop command callbacks to be more consistent - @jaylikesbunda, @Spooks4576

## 🌐 Network Features

- Enhanced Deauth Attack with bidirectional frames, proper 802.11 sequencing, and rate limiting (thank you @SpacehuhnTech for amazing reference code) - @jaylikesbunda  
- Added BLE Packet Capture support - @jaylikesbunda  
- Added BLE Wardriving - @jaylikesbunda  
- Added support for detecting and capturing packets from card skimmers - @jaylikesbunda  
- Added "gpsinfo" command to retrieve and display GPS information - @jaylikesbunda

## 🖥️ Interface & UI

- Added more terminal view logs - @jaylikesbunda, @Spooks4576  
- Better access for shared lvgl thread for panels where other work needs to be performed - @i-am-shodan
- Revised the WebUI styling to be more consistent with GhostESP.net - @jaylikesbunda
- Terminal View scrolling improvements - @jaylikesbunda
- Terminal_View_Add_Text queue system for adding text to the terminal view - @jaylikesbunda
- Revise options screen styling - @jaylikesbunda

## 🐛 Bug Fixes

- Fix GhostNet not coming back after stopping beacon - @Spooks4576
- Fixed GPS buffer overflow issue that could cause logging to stop - @jaylikesbunda
- Improved UART buffer handling to prevent task crashes in terminal view - @jaylikesbunda
- Terminal View trunication and cleanup to prevent overflow - @jaylikesbunda
- Fix and revise station scan command - @Spooks4576

## 🔧 Other Improvements

- Pulse LEDs Orange when Flipper is detected - @jaylikesbunda
- Refine DNS handling to more consistently handle redirects - @jaylikesbunda
- Removed Wi-Fi warnings and color codes for cleaner logs - @jaylikesbunda
- Miscellaneous fixes and improvements - @jaylikesbunda, @Spooks4576  
- WebUI fixes for better functionality - @Spooks4576

## 📦 External Updates

- New <https://ghostesp.net> website! - @jaylikesbunda
- Ghost ESP Flipper App v1.1.8 - @jaylikesbunda
- Cleanup README.md - @jaylikesbunda

...changelog starts here...