# Crenshaw
Breakout board for a 1.3" 128x64 pixel SSD1306-based OLED.

## Disclaimer
[This blog post](https://vivonomicon.com/2018/04/20/diy-oled-display-boards-ssd1306-and-ssd1331/) and [this datasheet](https://www.vishay.com/docs/37902/oled128o064dbpp3n00000.pdfwas) were heavily referenced during the creation of this breakout PCB.

## Key Features
* Bigger than your standard 0.91" OLED used in the CRKBD.
* Has M2 screw holes so you can secure it to the keyboard PCB.
* Comes with two I2C headers so it's fully reversible.
* There's a solder jumper on-board to bypass the LDO in case this board is being paired with a 3v3 microcontroller.
* The [Galia](https://github.com/Ariamelon/Galia), [Cantaloupe](https://github.com/Ariamelon/Cantaloupe) and [Hami](https://github.com/Ariamelon/Hami) were specially designed to use this OLED board.

Video: https://youtu.be/gXqI3UjQNgo
![Crenshaw Photo1](Images/Photo1.jpg)
![Crenshaw Front Render](Images/Render_Front.png)

## Changelog
* 27/09/2020: Initial commit.
* 29/09/2020: D1 SOD323 switched to SOD123.
* 30/09/2020: Updated to V1.1. Fixed orientation of I2C headers, increased silkscreen text size, moved ribbon cable connector further towards center of board.
* 11/11/2020: Updated to V1.2. Slightly increased size. Moved ribbon cable connector away from center of board as it was causing issues where it was. Spread components apart to allow for easier soldering.