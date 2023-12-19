# NX729j-Convert-Global
Convert Nubia Red Magic 8 pro into Global version

Global ROM= https://help.redmagic.gg/hc/en-us/articles/15828163597593-REDMAGIC-8-Pro

all roms= https://romprovider.com/nubia-red-magic-8-pro-plus-firmware-stock-rom/

extract payload

**unlock bootloader**

<code>fastboot flashing unlock</code>

use fastboot enahnce tool to flash the global rom

V440: https://rom.download.nubia.com/Europe/NX729J/V440/NX729J-update.zip

V340: https://rom.download.nubia.com/Europe%26Asia/NX729J/V340/NX729J-update.zip

**QFIL Method:**

QFIL Global ROM

Extract File

open qfil

settings/firehose storage ufs

xmls= rawprogram0,1,1,2,3,4,5 patch01,1,2,3,4,5

plug edl mod, click download


**Root:**

select init_boot.img in magisk

flashing in fastbootd

fastboot flash init_boot init_boot.img
