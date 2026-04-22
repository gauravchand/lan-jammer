# lan-jammer (Do not use for illegal work)
## Wanna try jamming LAN? This is your cue.

- Connect ESP-32 to your device (PC or Laptop)
- Configure the ESP-32 using Arduino IDE (or whichever works for you)
- Download the flash-tool and wifi-penetration-tool zips(attached with the repo)
- Extract the zips and open flash-download-tool (a dialogue box will appear)
- Select chiptype as esp32 (or as per your board) and click on 'OK'
- Another dialogue box will appear where you need to select the following files and input values respectively <br><br>
     >Choose file inside esp32-wifi-penetration-tool-master/build/ and input the value 0x8000 besides in the empty box.<br>
     >Do the same for /build/bootloader and input the value 0x1000 <br>
     >Now select the esp32-wifi-penetration-tool file and input the value 0x10000
- If ESP-32 is connected to PC/Laptop, it'll show option to select under the 'COM' option at bottom right and click start
- After processing, close the dialogue box and press RST button on the board
- Now, you'll find a new connection in the wifi option called ```ManagementAP```, put password as ```mgmtadmin```
- Open browser and type ```192.168.4.1```
- Now, feel free to mess around.
