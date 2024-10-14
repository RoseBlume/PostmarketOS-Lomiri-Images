# Postmarket OS Builds with the Lomiri Mobile Desktop Environment
Username: `user`

Password: `123456`
If there are any applications you wish to include please open an issue and explain why you wish to have this application included.
All images are located in the "releases" folder. Please note that I am not responsible for any issues that may occur. Use these images at your own risk.

**Built Device Images**

1. Pinephone
2. Pinephone Pro
3. Pinebook Pro
4. Rock64
5. RockPro64
6. RaspberryPi4
7. RaspberryPi3

| Device        | Tested | Starts Up | App Menu | Calls   | Camera   | Quick Menu |
| ------------- | :----: | :-------: | :------: | :-----: | :------: | :--------: |
| Pinephone Pro | Y      | Y         | Working  | Untested| Untested | Buggy      |
| Pinephone     | Y      | Y         | Y        | Untested| Untested | Y          |
| PineBook Pro  | N      | Untested  | Untested | Untested| Untested | Untested   |
| Rock64        | N      | Untested  | Untested | Untested| Untested | Untested   |
| RockPro64     | N      | Untested  | Untested | Untested| Untested | Untested   |
| RaspberryPi4  | N      | Untested  | Untested | Untested| Untested | Untested   |
| RaspberryPi3  | N      | Untested  | Untested | Untested| Untested | Untested   |

TODO:
1. Pinetab2 with wifi drivers out of the box
2. Pinenote - May be dropped due to lack of manufacturing
3. Pinetab1
4. Pine64-Quartz64
5. SteamDeck-Jupiter
6. JollaPhone
7. Librem

To contribute, please fork this repository and add devices to the `main.yml` file. If you have a device that requires special configuration, create a new job (preferably) or an entirely new workflow and add the necessary build commands.
