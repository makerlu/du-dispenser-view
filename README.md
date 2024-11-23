PLEASE NOTE: This script will no longer be maintained.
======================================================

# du-dispenser-view
LUA script for dual universe - Dispenser View script

An easy to use script for making your shop more shiny and vital.

![image](https://github.com/makerlu/du-dispenser-view/blob/main/pictures/dispenser-view1.jpg)

![image](https://github.com/makerlu/du-dispenser-view/blob/main/pictures/dispenser-view-updated-optionlist.jpg)

![image](https://github.com/makerlu/du-dispenser-view/blob/main/pictures/dispenser-view2.jpg)

## Installation
1. Place Programming board, Dispenser, Container and a Screen (fits all screen sizes - programmed on S size screen)
2. Link first the container, then second the screen
3. copy the json file (select raw view) and paste it to the PB
4. Upload a custom picture of your sales object to dual universe
4. Adjust the sales, picture and color options, by changing the LUA parameters (No lua programming needed)
5. Set up your dispenser to be ready for sale. (Dispensers cannot be triggered through LUA, so you must insert batch size and price on PB and Dispenser)

## Activation of the programming board
You can use "detection zones", pressure plates or laser emitter to activate the PB.
Currently take care, that the PB is activated for more than 35 seconds - DU only allow update of the container every 30 seconds.
If not it could happen, that the quantity is not updated correct.
### Note
If you have multiple dispenser in a small area, it is best to use xs detection zones, because the container update command only update one container script a time.
If you use pressure plates, sometimes a quick run-over the plate is not deactivating the last PB and the next PB cannot update in the "chunk"


### Tip
If you like my work, i would be happy if you buy me a coffee
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/I2I0THFNL)
