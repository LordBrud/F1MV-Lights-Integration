- Added Nanoleaf integration
- The values from the config file are now loaded in automatically when the settings page opens, so you don't have to click a button anymore.
- Fixed an issue where some integrations already started connecting to lights while the app was not fully launched yet.
- Fixed an issue where an error occurred while closing the application during an API check.
- Fixed an issue where some integrations did not start correctly.
- Fixed an issue where the NodeJS check did not work correctly on MacOS and Linux.
- Fixed an issue where the Ikea Tradfri server tried to stop when it was not started.
- Removed logging when the log field is not visible.
- Added detection for a already running Ikea Tradfri Server (when the other one did not stop correctly).
- Fixed an issue where the Ikea lights are controlled even if the Ikea server failed starting.
- Bump some dependencies.
- Update GitHub links
- Update the updater API check link.
- Some internal changes that make API check's faster.
- Add a message when there is no update found.