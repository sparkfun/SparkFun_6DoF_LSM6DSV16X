###Accelerometer - LSM6DSV16X

<figure markdown>
[![LSM6DSV16X Accelerometer](assets/imgs/21636-XBeeDevBoard-XBeeSocket.jpg){ width="400" }](assets/imgs/21636-XBeeDevBoard-XBeeSocket.jpg "Click to enlarge")
<figcaption markdown>LSM6DSV16X Accelerometer</figcaption>
</figure>

The LSM6DSV16X Accelerometer has three modes: 

Mode 1: Periperhal only mode - I2C or SPI
Mode 2: Sensor hub mode - I2C or SPI with controller I2C port
Mode 3 and 4: AUX SPI mode I2C and SPI access multi-read

###Qwiic Connector

The Qwiic connector(s) on the SparkFun 6DoF - LSM6DSV16X (Qwiic) and SparkFun 6DoF Micro - LSM6DSV16X (Qwiic) provide power and I<sup>2</sup>C connectivity simultaneously.


###Power

Ideally, power to these boards will be provided by the Qwiic cables. However, should you wish to provide power separately, the 1" x 1" board has its pins broken out to PTH and you can wire up power via these. 



VDD Range: 1.71V - 3.6V
VDDIO range: 1.62V - 3.6V



###I<sup>2</sup>C Address

The SparkFun 6DoF - LSM6DSV16X (Qwiic) has a default I<sup>2</sup>C address of 0x6B, but by cutting the address jumper on the back of the board, you can select 0x6A (GND) or SPI (fully open). 

I2C Address (selectable): 0x6B (default)
GND 0x6A
OPEN SPI

###Jumpers 


####I2C

Like our other Qwiic boards, the Qwiic 6DoF - LSM6DSV16X boards come equipped with pull-up resistors on the clock and data pins. If you are daisy-chaining multiple Qwiic devices, you will want to cut this jumper; if multiple sensors are connected to the bus with the pull-up resistors enabled, the parallel equivalent resistance will create too strong of a pull-up for the bus to operate correctly. As a general rule of thumb, disable all but one pair of pull-up resistors if multiple devices are connected to the bus. To disable the pull up resistors, use an X-acto knife to cut the joint between the two jumper pads highlighted below.



####LED

Let there be light! 

###Board Outline

The SparkFun 6DoF - LSM6DSV16X (Qwiic) follows the standard 1" x 1" convention of most of our Qwiic breakout boards. 

<figure markdown>
[![SparkFun 6DoF - LSM6DSV16X (Qwiic) Board Outline](assets/BoardFiles/SparkFun_6DoF_LSM6DSV16X-BoardOutline.png){ width="400" }](assets/BoardFiles/SparkFun_6DoF_LSM6DSV16X-BoardOutline.png "Click to enlarge")
<figcaption markdown>SparkFun 6DoF - LSM6DSV16X (Qwiic)</figcaption>
</figure>




The SparkFun 6DoF Micro - LSM6DSV16X (Qwiic) measures 0.3" x 0.75". 

<figure markdown>
[![SparkFun 6DoF - LSM6DSV16X (Qwiic) Board Outline](assets/BoardFiles/SparkFun_Micro_6DoF_LSM6DSV16X-BoardOutline.png){ width="400" }](assets/BoardFiles/SparkFun_Micro_6DoF_LSM6DSV16X-BoardOutline.png "Click to enlarge")
<figcaption markdown>SparkFun 6DoF Micro - LSM6DSV16X (Qwiic)</figcaption>
</figure>






















###Power
USB-C Connectors
Input VCC Range: 3.3V-4.3V


###Qwiic Connector

The Qwiic connector on the SparkFun XBee Development Board provides power and I<sup>2</sup>C connectivity to Qwiic breakout boards. 

<figure markdown>
[![Qwiic Connector](assets/imgs/21636-XBeeDevBoard-QwiicConnex.jpg){ width="400" }](assets/imgs/21636-XBeeDevBoard-QwiicConnex.jpg "Click to enlarge")
<figcaption markdown>Qwiic Connector</figcaption>
</figure>


###USB Switch

The USB switch allows you to select between Direct USB and I<sup>2</sup>C. Default is Low (I<sup>2</sup>C/SDA).

<figure markdown>
[![DUSB I2C Switch](assets/imgs/21636-XBeeDevBoard-DUSB-I2CSwitch.jpg){ width="400" }](assets/imgs/21636-XBeeDevBoard-DUSB-I2CSwitch.jpg "Click to enlarge")
<figcaption markdown>DUSB I<sup>2</sup>C Switch</figcaption>
</figure>

###Buck Converter - AP63203

The AP63203 Buck Converter ensures appropriate power supply to the components of the board. VIN range is <b>3.8V-5.5V</b>. Output is 2A max. 

<figure markdown>
[![DUSB I2C Switch](assets/imgs/21636-XBeeDevBoard-Buck Converter-AP63203.jpg){ width="400" }](assets/imgs/21636-XBeeDevBoard-Buck Converter-AP63203.jpg "Click to enlarge")
<figcaption markdown>AP63203 Buck Converter</figcaption>
</figure>


###USB to UART Bridge

The FT231XS translates data between your computer and the XBee. This is one of our favorite chips because it supports all computer platforms and it's easy to work with. If this is the first FTDI chip you've ever connected to your computer (it probably won't be your last), there is some driver installation to get out of the way. We've written a tutorial detailing [How to Install FTDI Drivers tutorial](tutorials/74).

<figure markdown>
[![FT231XS USB to UART Bridge](assets/imgs/21636-XBeeDevBoard-FT231XS.jpg){ width="400" }](assets/imgs/21636-XBeeDevBoard-FT231XS.jpg "Click to enlarge")
<figcaption markdown>FT231XS USB to UART Bridge</figcaption>
</figure>

###Lipo Battery Connector

The SparkFun XBee 3 Cat 1 Smart Modem Dev Board includes support for single-cell lithium-polymer (LiPo) batteries, which plug into the board's black 2-pin JST connector. LiPos are perfect for projects on-the-go, or those that just need a little extra oomph. 

<figure markdown>
[![Battery Connector](assets/imgs/21636-XBeeDevBoard-BatteryConnector.jpg){ width="400" }](assets/imgs/21636-XBeeDevBoard-BatteryConnector.jpg "Click to enlarge")
<figcaption markdown>Battery Connector</figcaption>
</figure>

###GPIO

We've broken out the XBee pins to plated through holes on either side of the board. 

<figure markdown>
[![GPIO](assets/imgs/21636-XBeeDevBoard-GPIO.jpg){ width="400" }](assets/imgs/21636-XBeeDevBoard-GPIO.jpg "Click to enlarge")
<figcaption markdown>GPIO</figcaption>
</figure>

###Buttons 

There are two buttons - D0 and RST. 

<figure markdown>
[![Reset and D0 Buttons](assets/imgs/21636-XBeeDevBoard-ResetandD0Buttons.jpg){ width="400" }](assets/imgs/21636-XBeeDevBoard-ResetandD0Buttons.jpg "Click to enlarge")
<figcaption markdown>Reset and D0 Buttons</figcaption>
</figure>

###LEDs

There are three LEDs on the board: 

<figure markdown>
[![LEDs](assets/imgs/21636-XBeeDevBoard-LEDs.jpg){ width="400" }](assets/imgs/21636-XBeeDevBoard-LEDs.jpg "Click to enlarge")
<figcaption markdown>LEDs</figcaption>
</figure>

####PWR

Lights up when power is provided to the board. 

####ASC
The LED on the development board blinks when the XBee is registered to the cellular network.


<table class="tg" align="left">
  <tr>
    <th width="20%" align="center"><b>Blink</b></th>
    <th width="20%" align="center"><b>Timing</b></th>
    <th width="60%" align="left"><b>Meaning</b></th>
  </tr>
  <tr>
    <td align="center">On</td>
    <td align="center">Solid</td>
    <td>Not joined to a mobile network</td>
  </tr>
  <tr>
    <td align="center">Double blink</td>
    <td align="center">½ second</td>
    <td>The last TCP/UDP/SMS attempt failed. If the LED has this
pattern, you may need to check DI (Remote Manager
Indicator) or CI (Protocol/Connection Indication) for the cause
of the error.</td>
  </tr>
  <tr>
    <td align="center">Single blink</td>
    <td align="center">1 second</td>
    <td>Normal operation</td>
  </tr>
</table>


####RSSI 
Received Signal Strength Indicator - When configured, this LED reflects the received signal strength

RSSI PWM
The RSSI/PWM output is enabled continuously unlike other XBee products where the output is enabled for a short period of time after each received transmission. If running on the XBIB development board, DIO10 is connected to the RSSI LEDs, which may be interpreted as follows:


<table class="tg" align="left">
  <tr>
    <th width="20%" align="center"><b>PWM duty cycle</b></th>
    <th width="20%" align="center"><b>Number of LEDs turned on</b></th>
    <th width="60%" align="left"><b>Received signal strength (dBm)</b></th>
  </tr>
  <tr>
    <td align="center">79.39% or more</td>
    <td align="center">3</td>
    <td>-83 dBm or higher</td>
  </tr>
  <tr>
    <td align="center">62.42% to 79.39%</td>
    <td align="center">2</td>
    <td align="left"> -93 to -83 dBm</td>
  </tr>
  <tr>
    <td align="center">45.45% to 62.42%</td>
    <td align="center">1</td>
    <td align="left">-103 to -93 dBm</td>
  </tr>
  <tr>
    <td align="center">Less than 45.45%</td>
    <td align="center">0</td>
    <td align="left">Less than -103 dBm, or no cellular network connection</td>
  </tr>
</table>


###Jumpers

####SHLD/SHLD1

For most applications, the single point grounding of the Direct USB or UART at the USB-C connector is sufficient. However, should you run into problems with EMI/EMC, we've provided jumpers that allow you to disconnect either connector from ground.

Cut the SHLD jumper for the UART USB-C; cut the SHLD1 jumper for Direct USB. 

<figure markdown>
[![Shield Jumpers](assets/imgs/21636-XBeeDevBoard-Jumper-ShldandShld1.jpg){ width="400" }](assets/imgs/21636-XBeeDevBoard-Jumper-ShldandShld1.jpg "Click to enlarge")
<figcaption markdown>Shield Jumpers</figcaption>
</figure>


####ALED/PLED

If power consumption is an issue (or if you just don't like the LEDs), cut the respective jumper to sever power to the LED. 

* PLED: Red
* ALED: Blue

<figure markdown>
[![LED Jumpers](assets/imgs/21636-XBeeDevBoard-Jumper-LEDs.jpg){ width="400" }](assets/imgs/21636-XBeeDevBoard-Jumper-LEDs.jpg "Click to enlarge")
<figcaption markdown>LED Jumpers</figcaption>
</figure>

####I2C 

The I<sup>2</sup>C jumper pulls the SDA and SCL pins to VDD (normally 3.3V) through two 2.2K Ohm resistors. If you have multiple Qwiic devices on the same bus you may want to disable these by opening the jumper (assuming they are also operating at 3.3V logic).


<figure markdown>
[![I2C Jumper](assets/imgs/21636-XBeeDevBoard-Jumper-I2C.jpg){ width="400" }](assets/imgs/21636-XBeeDevBoard-Jumper-I2C.jpg "Click to enlarge")
<figcaption markdown>I<sup>2</sup>C Jumper</figcaption>
</figure>


###Board Outline

The overall size of the SparkFun XBee Development Board is 1.8" by 2.5". For specific measurements, see the image below. 


<figure markdown>
[![Board Outline](assets/BoardFiles/21636-SparkFun_XBee3_Cat1_Smart_Modem-BoardOutline.png){ width="600" }](assets/BoardFiles/21636-SparkFun_XBee3_Cat1_Smart_Modem-BoardOutline.png "Click to enlarge")
<figcaption markdown>Board Outline</figcaption>
</figure>
