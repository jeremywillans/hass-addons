# Willans Hass.io Add-on: roombapw Docker Image

Build and run the roombapw Docker Image on Hass.io

![Supports amd64 Architecture][amd64-shield] ![Supports armv7 Architecture][armv7-shield]

## About

This image is a modified version of [dorita980][dorita980] allowing retrival of the BLID and Password from your iRobot Roomba (i7/i7+, 980, 960, e5, 690, 675, etc) from within Hass.io

Essentially this addon attempts to "pair" with your Roomba which allows it to capture the credentials

## Installation

Follow these steps to get the add-on installed on your system:

1. Navigate in your Home Assistant frontend to **Supervisor** -> **Add-on Store**.
2. Ensure you have added the custom repository - ```https://github.com/jeremywillans/hass-addons```
3. Find the "roombapw Docker Image" add-on and click it.
4. Click on the "INSTALL" button - this will build the image locally.

## How to use

**NOTE:** Do **NOT** have the iRobot App open when performing these steps!

This add-on requires configuration options to be set.

1. Set the required ROBOT_IP configuration attribute, optionally update the verion (unlikely).
2. On your **docked** iRobot Roomba, press and hold the Home button util it plays a series of tones/flashes (about 2 seconds)
3. Start the add-on, it will pause for 10 seconds before attempting to pair with the Roomba
4. Check the add-on log output to see the credentials.
5. Stop and remove this addon, it is no longer needed.

If you find that your roomba exits pairing mode (stops flashing) before you can capture the credentials, start the Add-on first and then **quickly** head to your roomba to initiate pairing mode (by holding the Home button)

## Support

Got questions? Please post them [here][forum].

In case you've found a bug, please [open an issue on GitHub][issue].

## Credits

- [Facu ZAK](https://github.com/koalazak) for creating dorita980 and rest980 !

## My Repos

[ha-rest980-roomba](https://github.com/jeremywillans/ha-rest980-roomba) | 
[roomba-vacuum-card](https://github.com/jeremywillans/lovelace-roomba-vacuum-card) | 
[hass-addons](https://github.com/jeremywillans/hass-addons)

[![BMC](https://www.buymeacoffee.com/assets/img/custom_images/white_img.png)](https://www.buymeacoffee.com/jeremywillans)

[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg?style=for-the-badge
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg?style=for-the-badge
[forum]: https://community.home-assistant.io/t/irobot-roomba-i7-configuration-using-rest980/161175
[issue]: https://github.com/jeremywillans/hass-addons/issues
[dorita980]: https://github.com/koalazak/rest980
[facuzak]: https://github.com/koalazak
