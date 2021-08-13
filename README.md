# library-catalogue
A low cost Library catalogue server using esp8266 module. It can store upto 20000 books

How
1. Collect a esp8266 module   ($2)
2. Download all 4 files
3. Download ESP8266  Flash download tool 
  https://www.espressif.com/sites/default/files/tools/flash_download_tool_v3.8.8_0.zip

4.Flash all 4 files using Flash tool

Memmory Map

bootloader.bin  0x0000

partitions.bin  0x8000

program.bin     0x10000

spiff.img       0x110000

5. Connect your mobile to WiFi hotspot home.in
6. Start browser in your mobile and browse lib.in 
7. Main Screen will load
![Screenshot_2021-08-13 LIBRARY CATALOGUE](https://user-images.githubusercontent.com/47342428/129299211-808bd149-e378-4eef-82ff-8221e4ca0b9a.png)
