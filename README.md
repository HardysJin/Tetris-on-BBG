# Tetris

## Description

Tetris is a tile-matching puzzle game.
The project implements a Tetris game on a [BeagleBone](https://beagleboard.org/bone) with a 16*32 LED display.

## Setup

1. Connect LED matrix and BeagleBone

https://www.cs.sfu.ca/CourseCentral/433/bfraser/other/2015-student-howtos/Adafruit16x32LEDMatrixGuideForBBB.pdf

2. Enable audio

https://www.cs.sfu.ca/CourseCentral/433/bfraser/other/ZenLEDGuide.pdf

3. Connect Buttons to Beagble

https://cdn-learn.adafruit.com/downloads/pdf/connecting-a-push-button-to-beaglebone-black.pdf

4. Download/Clone Project

```bash
git clone https://github.com/HardysJin/Tetris-on-BBG.git
```

5. Go Tetris Folder

```bash
cd Tetris-on-BBG/Tetris
```

6. Make

```bash
make
```

7. Go shared folder on target #

```bash
cd /mnt/remote/myApps/Tetris
```

8. Run

```
./tetris
```
