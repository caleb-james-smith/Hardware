# Hardware
* This repository outlines the hardware used in testing QIE11 cards for the HE upgrade of HCal, 2016-2017. The primary components are the Fanout Board, ngCCM Emulator, and QIE cards.
* You may fork this repository, add relevant info, and submit a pull request as desired.

## Fanout

### Primary MUX
* Address = 0x72

## ngCCM Emulator

### U10 = Primary MUX
* Address = 0x74

### U18 = Secondary MUX
* Address = 0x70

## QIE Card
* Address = {0x19, 0x1a, 0x1b, 0x1c}

### U48 = UniqueID Chip
* DS28CM00R-A00+T

### U96 = Bridge FPGA
http://www.microsemi.com/products/fpga-soc/fpga/proasic3-e#documents
* Actel
* ProASIC 3
* A3P1000
* FG256 1517
* QMC6N

### U38 = Igloo2
* Microsemi
* M2GL050
* FGG896
* SKHHK
