# Willans Hass.io Add-on: roombapw Docker Image

Build and run the roombapw Docker Image on Hass.io

![Supports amd64 Architecture][amd64-shield] ![Supports armv7 Architecture][armv7-shield]

## About

This image is a modified version of [dorita980][dorita980] allowing retrival of the BLID and Password from your iRobot Roomba (i7/i7+, 980, 960, e5, 690, 675, etc) from within Hass.io

Credit to [Facu Zak][facuzak] for providing this solution!

## Installation

Follow these steps to get the add-on installed on your system:

1. Navigate in your Home Assistant frontend to **Hass.io** -> **Add-on Store**.
2. Find the "roombapw Docker Image" add-on and click it.
3. Click on the "INSTALL" button - this will build the image locally.

## How to use

This add-on requires configuration options to be set.

1. Set the required ROBOT_IP configuration attribute, optionally update the verion (unlikely).
2. On your **docked** iRobot Roomba, press and hold the Home button util it plays a series of tones (about 2 seconds)
3. Start the add-on.
4. Check the add-on log output to see the credentials.
5. Stop and remove this addon, it is no longer needed.

## Support

Got questions? Please post them [here][forum].

In case you've found a bug, please [open an issue on GitHub][issue].

[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[forum]: https://community.home-assistant.io/t/irobot-roomba-i7-configuration-using-rest980/161175
[issue]: https://github.com/jeremywillans/hass-addons/issues
[dorita980]: https://github.com/koalazak/rest980
[facuzak]: https://github.com/koalazak
