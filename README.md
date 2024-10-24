# Crenshaw
1.5" SSD1351 RGB OLED [VIK](https://github.com/sadekbaroudi/vik) module.

## Disclaimer
This board is licensed under CERN-OHL-S-2.0.

## VIK module certification card

| Category                | Classification          | Response           |
| ----------------------- | ----------------------- | ------------------ |
| FPC connector           | Required                | :heavy_check_mark: |
| Breakout pins           | Recommended             | :x:                |
| Uses: SPI               | Optional                | :heavy_check_mark: |
| SPI used for SPI only   | Strongly recommended    | :heavy_check_mark: |
| Uses: I2C               | Optional                | :x:                |
| I2C used for I2C only   | Strongly Recommended    | N/A                |
| I2C pull ups            | Required                | N/A                |
| Uses: RGB               | Optional                | :x:                |
| Uses: Extra GPIO 1      | Optional                | :heavy_check_mark: |
| Uses: Extra GPIO 2      | Optional                | :heavy_check_mark: |
| Standard PCB Size/Mount | Strongly Recommended    | :x:                |

![Render](Showcase/Render.png)

## Changelog
 * 22/10/2024: License updated to CERN-OHL-S-2.0.
* 04/08/2023: Changed VIK and OLED FFC to FH12. Stitched ground planes together. Fixed VIK footprint. Moved production files to easier to access location.
* 28/07/2023: Added pin labels. Added VIK size row to certification card.
* 27/07/2023: Added voltage regulator, SSD1351 supporting circuitry and [VIK](https://github.com/sadekbaroudi/vik) connector. Added license. Added metadata to schematic and board files. Added VIK module certification card.
* 26/07/2023: Updated to V2.0.
* 11/11/2020: Updated to V1.2. Slightly increased size. Moved ribbon cable connector away from center of board as it was causing issues where it was. Spread components apart to allow for easier soldering.
* 30/09/2020: Updated to V1.1. Fixed orientation of I2C headers, increased silkscreen text size, moved ribbon cable connector further towards center of board.
* 29/09/2020: D1 SOD323 switched to SOD123.
* 27/09/2020: Initial commit.