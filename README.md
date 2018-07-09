# WINE Utils

These are shortcuts to use Microsoft Office on Linux from WINE, and Echolink on WINE.
Assumes you have already installed Microsoft Office on Linux WINE under `~/.wine-office/` directory.

## Usage

1. copy/clone this repo to your computer
2. add this repo directory to your `~/.bashrc` e.g.
   ```sh
   export PATH=$PATH:$HOME/code/wine-utils
   ```

### Install Microsoft Office on Linux WINE

It's easy to 
[install Microsoft Office 2010 in WINE](https://www.scivision.co/install-microsoft-office-linux-wine/)

-   [Office 2010](https://appdb.winehq.org/objectManager.php?sClass=version&iId=17336)
-   [Office 2016](https://appdb.winehq.org/objectManager.php?sClass=version&iId=34941)

We recommend installing major Windows programs on Linux using WINE each into their own
[WINEPREFIXes](https://www.scivision.co/making-wineprefix/)

 script   | purpose
----------|------------
 word     | Microsoft Office Word 2010 on Linux WINE
 excel    | Microsoft Office Excel 2010 on Linux WINE
 powerpnt | Microsoft Office Powerpoint 2010 on Linux WINE
 echolink | Amateur Radio Echolink program start


## Notes

Where's the unit test? 

* These scripts are so simple
* the scripts may need slight tweaks by the end user for their version of office or directory layout.
* WINE is rather too bulky to install in a fresh CI image each time without Docker
