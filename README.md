# MT6260A Stuff

this repo just contains stuff for the mt6260a (and by this im assuming anything that works on my devices works for the chip)

### Device:
- Model: ["Kids Smartphone Model PH05"](https://www.globalsources.com/Smart-watch/Children-Phone-1198178861p.htm)
- CPU: MT6260A (mono-core 533Mhz ARM7EJ-S)
- RAM: 64MB/128MB (same model just some came with twice the memory also 128mb is the max supported by the chip)
- Storage: 128MB w/ 8GB SD Card (expandable up to 32GB)
- Display: 240x320 2.8" IPS Display (not upgradable because this chip only supports up to 240x320 output)
- Battery: 600mAh

### Firmware:
- Well its completely unmodified kids smartphone firmware, its not very good
- restore it using the scatter file in the repo using MTK FlashTool (no SP Flash Tool does not work)
- also things dont seem to work properly without an sd card with the system data on it so here are links to the sd card tars, [newer_sdcard.tar.gz](https://www.mediafire.com/file/2qn9d3fq96o2za1/newer_sdcard.tar.gz/file), [older_sdcard.tar.gz](https://www.mediafire.com/file/4vrtu9x39f6n3pa/old_sdcard.tar.gz/file)
- the two sdcard data tars are different bcuz the newer one is from the version of the model with 128mb of ram and the old one is from the version of the model with 64mb of ram

ill be adding to this repo soon