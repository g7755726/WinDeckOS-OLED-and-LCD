# Changelog(s):
This changelog will no longer include the LTSC version of this OS as Home will be the primary version of this project!

## Version: v1.1.0
- Updated OS to 25H2
- Ran OS through Tiny11 25H2 builder script
- Improved performance
- Fixed an issue where sponsered apps would still be displayed even though the were disabled by group policy
- Improved UI responsiveness
- Enabled VRR by default
- In `About` changed valve name to `Valve Corporation`

## Version v1.0.9
- Improved GPU/UI Performance.
- Added gamepad configuration to ther OSK so you can use the Steam Deck's on-board gamepad controls with it (requires HC or Steam Deck Tools to work).
- Updated build with latest updates needed for windows update to install updates correctly.
- Added `Ultimate Performance Power Plan` and set it as default.
- Fixed an issue where OSK would feel sluggish when used or used for the first time.
- build can now install on both OLED & LCD models

## Version v1.0.8
- Touch Keyboard will now open when end user taps a field that requires user to use a keyboard to type works similar to the ROG Ally keyboard, you no longer need to manually enable to open when no keyboard is attached (This will interfere if you utilize steam input)
- Fixed an issue where mouse would feel not smooth enough this update fixes that.
- Disabled more services and disabled let apps work in the background to free up resources.
- AMD cpu processor core will now boot upon windows boot instead on windows login.
- Set mouse speed from 10% to 15% this should help with mouse to area ratio.
- In About system linked the support page to our issue tab instead of steams steam deck support.
- In About system added time we are available to respond to support requests.
- Set Compact OS to false this caused OS to load compressed system files slower then uncompressed system files.
- Fixed an issue with the touch keyboard on initial setup where it would feel there was no input register when user is setting up windows for the first time and had to press multiple times or press harder for input to register.


## Version v1.0.7
- Fixed an issue where window UI would look blurry.
- Disabled Event viewer entirely to free up resource usage
- Removed Recall from windows features.
- Disabled windows search indexing
- Added google drive to context menu this can help back up game saves or any docs to your google account insead of using onedrive (will not be added to navigation panel) if google drive is installed!
- Removed Onedrive from the navigation panel when it's installed by end user

NOTE: Steam Deck Tools seems to break the trackpad making it feel like its stuck, its recommended to use steam input or HC.

## Version v1.0.6
- Fixed a bug where Dolby Atomos would bug out and cause the speakers to sound terrible.
- Fixed a bug where users using a type c to hdmi dongle or dock would have issues displaying video out on a TV/Monitor setup.
- Fixed an issue when the steam deck is moved the video out connection would flicker off and on.
- Fixed an issue where the wallpaper looks bugged out (Home Only).
- Added `All Control Panel Items` to "This PC" could be useful when you need to change a setting but cannot access desktop when running a fullscreen game.
- Added user files folder to desktop.



