# Willans Hass.io Add-on: rest980 Docker Image

Build and run the rest980 Docker Image on Hass.io

![Supports amd64 Architecture][amd64-shield] ![Supports armv7 Architecture][armv7-shield]

## About

[rest980][rest980] exposes [dorita980][dorita980] which is an Unofficial iRobot Roomba (i7/i7+, 980, 960, e5, 690, 675, etc) node.js library (SDK).

Please head over to [this repo](https://github.com/jeremywillans/ha-rest980-roomba) for usage instructions!

## Installation

Follow these steps to get the add-on installed on your system:

1. Navigate in your Home Assistant frontend to **Supervisor** -> **Add-on Store**.
2. Ensure you have added the custom repository - ```https://github.com/jeremywillans/hass-addons```
3. Find the "rest980 Docker Image" add-on and click it.
4. Click on the "INSTALL" button - this will build the image locally.

## How to use

This add-on requires configuration options to be set.

BLID/Password - refer [here][blid] for help in obtaining these details, alternatively you can use my other Add-on: **roombapw**

1. Set the required configuration attributes.

    **NOTE** Firmware option 2 implies 2+ (inclusive of 3.x)

2. Start the add-on.
3. Check the add-on log output to see the result.

## Support

Got questions? Please post them [here][forum].

In case you've found a bug, please [open an issue on GitHub][issue].

## Credits

- [Facu ZAK](https://github.com/koalazak) for creating dorita980 and rest980 !

## My Repos

[ha-rest980-roomba] | 
[roomba-vacuum-card] | 
[hass-addons] | 
[event-emitter]

[![BMC]](https://www.buymeacoffee.com/jeremywillans)

[![BMC](https://www.buymeacoffee.com/assets/img/custom_images/white_img.png)](https://www.buymeacoffee.com/jeremywillans)

[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg?style=for-the-badge
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg?style=for-the-badge
[forum]: https://community.home-assistant.io/t/irobot-roomba-i7-configuration-using-rest980/161175
[issue]: https://github.com/jeremywillans/hass-addons/issues
[blid]: https://github.com/koalazak/dorita980#how-to-get-your-usernameblid-and-password
[rest980]: https://github.com/koalazak/rest980
[dorita980]: https://github.com/koalazak/rest980
[facuzak]: https://github.com/koalazak

[ha-rest980-roomba]: https://github.com/jeremywillans/ha-rest980-roomba
[roomba-vacuum-card]: https://github.com/jeremywillans/lovelace-roomba-vacuum-card
[hass-addons]: https://github.com/jeremywillans/hass-addons
[event-emitter]: https://github.com/jeremywillans/event-emitter
[BMC]: https://www.buymeacoffee.com/assets/img/custom_images/white_img.png