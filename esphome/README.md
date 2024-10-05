# ESPhome

## flashen

https://web.esphome.io/

esptools examples
````bash
./esptool.py --port /dev/ttyACM0 write_flash --flash_mode dio --flash_size 16MB 0x0 '/home/tedsluis/Downloads/wt32-sc01-plus.factory.bin' 

./esptool.py --port /dev/ttyUSB0 write_flash --flash_mode dio --flash_size 4MB 0x0 /home/tedsluis/Downloads/nodemcu-display.bin
````
