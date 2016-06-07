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

### VTTx
https://edms.cern.ch/ui/file/1140665/1/VTRx_Spec_v2.1.pdf
* Address = 0x7E

## QIE Card
https://cms-docdb.cern.ch/cgi-bin/DocDB/RetrieveFile?docid=12782&filename=CMS_HE_FE_Production_Schematic_18MAR2016.pdf&version=2

### U48 = Silicon Serial Number Device (UniqueID)
http://datasheets.maximintegrated.com/en/ds/DS28CM00.pdf
* Address = 0x50
* DS28CM00R-A00+T

### U96 = Bridge FPGA
http://www.microsemi.com/products/fpga-soc/fpga/proasic3-e#documents
* Address = {0x19, 0x1a, 0x1b, 0x1c}
* Actel
* ProASIC 3
* A3P1000
* FG256 1517
* QMC6N

### U38 = Igloo2
http://www.microsemi.com/document-portal/doc_view/131877-pb0121-igloo2-fpga-product-brief
http://www.microsemi.com/document-portal/doc_view/132014-ug0451-igloo2-and-smartfusion2-programming-user-guide
* Address = 0x09
* Microsemi
* M2GL050
* FGG896
* SKHHK
