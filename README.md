# Nixie Clock

![Nixie Clock](https://raw.githubusercontent.com/PZZ97/NixieClock/main/nixie.jpg)
There's no technically tough poitns, the difference of my clock is that I added one **mp3 module** so it could play customized sounds hourly. 

Esp8266 nodemcu board was directly soldered on my pcb and third party boost module was applied so this pcb is very simple.


## Function

* NTP time 
* press button shows time
* Anti-cathode poisoning function, (but I have forgetten if it works)
* Sounds playing(needs to record and save in sd card. I stored about 100 voice files,including hour,minutes,special messsages and numbers used for showing ip addressing )
* set alarm time (iphone Shortcuts)
* ask for time with clock voice response (iphone Shortcuts)
* set LED color (iphone Shortcuts)

## Notices
* MCU Board is esp8266 nodemcu, you may find two different shapes of that, choose the smaller and rounded one. Otherwise you may look like the poor man in below figure.
* Button, speakers and DC source plug are fixed on the 3D printed shell. 

![downside](https://raw.githubusercontent.com/PZZ97/NixieClock/main/downside.jpg)

![topside-w10](https://raw.githubusercontent.com/PZZ97/NixieClock/main/topside.jpg)
## License
WTFPL
