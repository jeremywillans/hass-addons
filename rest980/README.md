# Willans Hass.io Add-on: rest980 Docker Image

Build and run the rest980 Docker Image on Hass.io

![Supports amd64 Architecture][amd64-shield] ![Supports armv7 Architecture][armv7-shield]

## About

[rest980][rest980] exposes [dorita980][dorita980] which is an Unofficial iRobot Roomba (i7/i7+, 980, 960, e5, 690, 675, etc) node.js library (SDK).

Credit to [Facu Zak][facuzak] for providing this solution!

## Installation

Follow these steps to get the add-on installed on your system:

1. Navigate in your Home Assistant frontend to **Hass.io** -> **Add-on Store**.
2. Find the "rest980 Docker Image" add-on and click it.
3. Click on the "INSTALL" button - this will build the image locally.

## How to use

This add-on requires configuration options to be set.

BLID/Password - refer [here][blid] for help in obtaining these details, alternatively you can use my other Add-on: **roombapw**

1. Set the required configuration attributes.
2. Start the add-on.
3. Check the add-on log output to see the result.

## Support

Got questions? Please post them [here][forum].

In case you've found a bug, please [open an issue on GitHub][issue].

[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[forum]: https://community.home-assistant.io/t/irobot-roomba-i7-configuration-using-rest980/161175
[issue]: https://github.com/jeremywillans/hass-addons/issues
[blid]: https://github.com/koalazak/dorita980#how-to-get-your-usernameblid-and-password
[rest980]: https://github.com/koalazak/rest980
[dorita980]: https://github.com/koalazak/rest980
[facuzak]: https://github.com/koalazak
