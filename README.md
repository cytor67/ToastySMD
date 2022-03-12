# ToastySMD
Open Source Reflow Oven Controller 


An all in one STM32 based reflow controller powered by STM32F103C8T6. A moden Reflow Oven Controller that has a built in thermocouple sensor IC MAX6675 from Maxim, I have used as many SMD parts as I could to keep the cost low (manual soldering is time consuming) and leaving only the terminal block,Boot,SWDIO and the TFT I2C Display connector to solder. The board is powered from a 5V USB and is stepped down to 3.3V . All you need is an external Solid State Relay (SSR) (rated accordingly to your oven), K type thermocouple ,an oven
and a TFT I2C 3.5" Display (they are around £30 on ebay). I have also included a  built-in USB-serial interface.  and a  optional transistor output drive fan.




PS put the BOM.CSV into LSCS Bom Tool to make component ordering quick and easy Total component cost is £24.15 plus when you order your Toasty SMD PCB please select ENIG-RoHs 


I should mention this my first time doing a PCB design so please check everything before ordering and please help me make this project even better :) 
