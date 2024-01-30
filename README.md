# icub-firmware-updater-pixi-example

Example of the use of pixi to run the FirmwareUpdater used to manage firmware on boards used on iCub and ergoCub.

## Requirements

Unless you already have it, install [pixi](https://pixi.sh/):
* On Linux or macOS: `curl -fsSL https://pixi.sh/install.sh | bash`
* On Windows: `winget install --id=prefix-dev.pixi  -e`

Just on Windows, if you want to use the `ecan` YARP can driver, install the ESD CAN SDK (https://esd.eu/en/products/can-sdk). Only the 6.3.0 is currently tested.

## Run

Clone the repo, then open it in a terminal and run:

~~~
pixi run FirmwareUpdater
~~~

if you want to edit the options passed to the `FirmwareUpdater`, edit the `firmwareupdater.ini`, that by default is configured to talk with `ETH` devices.

For more info on FirmwareUpdater, check FirmwareUpdater documentation at [https://icub-tech-iit.github.io/documentation/icub_firmware/firmware/firmware/](https://icub-tech-iit.github.io/documentation/icub_firmware/firmware/firmware/).

The version of FirmwareUpdater installed the one of icub-main 2.4.0 (i.e. [robotology-distro 2023.11.0](https://icub-tech-iit.github.io/documentation/sw_versioning_table/2023.11.0/)). 
