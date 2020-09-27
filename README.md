# Crenshaw
Breakout board for a 1.3" 128x64 pixel SSD1306-based OLED.

## Disclaimer
[This blog post](https://vivonomicon.com/2018/04/20/diy-oled-display-boards-ssd1306-and-ssd1331/) and [this datasheet](https://www.vishay.com/docs/37902/oled128o064dbpp3n00000.pdfwas) were heavily referenced during the creation of this breakout PCB.

## Key Features
* Bigger than your standard 0.91" OLED used in the CRKBD.
* Has M2 screw holes so you can secure it to the keyboard PCB.
* Comes with two I2C headers so it's fully reversible.
* There's a solder jumper on-board to bypass the LDO in case this board is being paired with a 3v3 microcontroller.
* The [Cantaloupe Split Ergo Keyboard](https://github.com/Ariamelon/Cantaloupe) and Hami Numberpad were specially designed to use this OLED board.