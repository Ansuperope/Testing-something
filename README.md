+-----------------------------------+-----------------------------------+
| ## Payload                        |                                   |
+===================================+===================================+
| **[Gianni C                       | [Diameter: No more than           |
| Restrictions:]{.mark}**           | 114mm]{.mark}                     |
|                                   |                                   |
| [\*\*as of 1/24/26:\*\*]{.mark}   | [Length: No more than             |
|                                   | 152mm]{.mark}                     |
|                                   |                                   |
|                                   | [Mass: No more than 500g]{.mark}  |
+-----------------------------------+-----------------------------------+
| **Notes**                         | -   scientific payload            |
|                                   |                                   |
|                                   |     -   in shape of cube          |
|                                   |                                   |
|                                   | -   [sensors on the side]{.mark}  |
+-----------------------------------+-----------------------------------+
| **Goal**                          | **Notes**                         |
+-----------------------------------+-----------------------------------+
| 1.  **Create flight path (not     |                                   |
|     > live)**                     |                                   |
|                                   |                                   |
|     a.  GPS collects the data:    |                                   |
|                                   |                                   |
|         i.  time                  |                                   |
|                                   |                                   |
|         ii. location              |                                   |
|                                   |                                   |
|         iii. orientation          |                                   |
|                                   |                                   |
|     b.  saved to a SD card as an  |                                   |
|         > csv file                |                                   |
+-----------------------------------+-----------------------------------+
| 2.  **Transmit data to a receiver |                                   |
|     > (live)**                    |                                   |
|                                   |                                   |
|     a.  will have a display to    |                                   |
|         > show rocket location    |                                   |
|                                   |                                   |
|     b.  used to track rocket      |                                   |
|         > location                |                                   |
+-----------------------------------+-----------------------------------+
| 3.  **Collect microbes**          | -   cannot be contaminated        |
|                                   |                                   |
|     a.  1 door will open and      |     -   must be airtight          |
|         > close:                  |                                   |
|                                   | -   agar needs to be removable    |
|         i.  agar plate lid will   |                                   |
|             > be on the door      |                                   |
|                                   |                                   |
|         ii. opens 30 seconds      |                                   |
|             > after               |                                   |
|                                   |                                   |
|     b.  air will be pushed to an  |                                   |
|         > agar plate              |                                   |
|                                   |                                   |
|     c.  agar plate Velcroed(?) to |                                   |
|         > door and payload        |                                   |
+-----------------------------------+-----------------------------------+
| 4.  **Collect data and save to SD |                                   |
|     > card as a csv file**        |                                   |
|                                   |                                   |
|     a.  get the data              |                                   |
|                                   |                                   |
|         i.  particulates          |                                   |
|                                   |                                   |
|         ii. gasses                |                                   |
|                                   |                                   |
|         iii. pressure             |                                   |
|                                   |                                   |
|         iv. humidity              |                                   |
|                                   |                                   |
|     b.  more readings better (no  |                                   |
|         > specific rate yet)      |                                   |
+-----------------------------------+-----------------------------------+
| 5.  **Camera**                    |                                   |
|                                   |                                   |
|     a.  video will not be live    |                                   |
|                                   |                                   |
|     b.  save to an SD card        |                                   |
+-----------------------------------+-----------------------------------+

+-----------------------------------+-----------------------------------+
| ## Sensors / Components           |                                   |
+===================================+===================================+
| **Collecting microbes**           |                                   |
+-----------------------------------+-----------------------------------+
| Motors                            | -   to open and close doors       |
+-----------------------------------+-----------------------------------+
| Agar plate                        |                                   |
+-----------------------------------+-----------------------------------+
| Velcro                            | -   hold agar plates              |
+-----------------------------------+-----------------------------------+
| **Collecting Data**               |                                   |
+-----------------------------------+-----------------------------------+
| Teensy                            | What for / what it does:          |
|                                   |                                   |
|                                   | -                                 |
+-----------------------------------+-----------------------------------+
|                                   | Other Notes:                      |
|                                   |                                   |
|                                   | -                                 |
+-----------------------------------+-----------------------------------+
| SD card                           |                                   |
+-----------------------------------+-----------------------------------+
| Lora / Radio for transmitting /   |                                   |
| receiving                         |                                   |
+-----------------------------------+-----------------------------------+
| GPS                               | What for / what it does:          |
|                                   |                                   |
|                                   | -   gets location, orientation    |
|                                   |     > and time for:               |
|                                   |                                   |
|                                   |     -   receiver                  |
|                                   |                                   |
|                                   |     -   flight path               |
|                                   |                                   |
|                                   |     -   sd                        |
+-----------------------------------+-----------------------------------+
|                                   | Other Notes:                      |
|                                   |                                   |
|                                   | -   needs to read 3 satellites or |
|                                   |     > more for more accuracy      |
+-----------------------------------+-----------------------------------+
| Grove Laser PM2.5 Dust Sensor     | -   particulates                  |
|                                   |                                   |
| [[https://www.robotshop.          |                                   |
| com/products/grove-laser-pm25-dus |                                   |
| t-sensor-hm3301?srsltid=AfmBOorch |                                   |
| GyyJaX1OiRnQnjkHcjC5-3EbThS9AytuI |                                   |
| xg_Q3Tfj4OYYzs]{.underline}](http |                                   |
| s://www.robotshop.com/products/gr |                                   |
| ove-laser-pm25-dust-sensor-hm3301 |                                   |
| ?srsltid=AfmBOorchGyyJaX1OiRnQnjk |                                   |
| HcjC5-3EbThS9AytuIxg_Q3Tfj4OYYzs) |                                   |
+-----------------------------------+-----------------------------------+
| MiCS-6814 and/or CCS811           | -   gasses                        |
|                                   |                                   |
| [[Humidity Sensor BME280 \| Bosch |                                   |
| Sensortec]{.und                   |                                   |
| erline}](https://www.bosch-sensor |                                   |
| tec.com/en/products/environmental |                                   |
| -sensors/humidity-sensors-bme280) |                                   |
|                                   |                                   |
| or                                |                                   |
|                                   |                                   |
| [[Overview \| Adafruit CCS811 Air |                                   |
| Quality Sensor \| Adafruit        |                                   |
| Learning                          |                                   |
| System]{.underline}](https        |                                   |
| ://learn.adafruit.com/adafruit-cc |                                   |
| s811-air-quality-sensor/overview) |                                   |
+-----------------------------------+-----------------------------------+
| BME280                            | -   weather                       |
|                                   |                                   |
| [[Humidity Sensor BME280 \| Bosch |     -   pressure                  |
| Sensortec]{.und                   |                                   |
| erline}](https://www.bosch-sensor |     -   humidity                  |
| tec.com/en/products/environmental |                                   |
| -sensors/humidity-sensors-bme280) |                                   |
+-----------------------------------+-----------------------------------+
|                                   |                                   |
+-----------------------------------+-----------------------------------+
| Camera                            | -   not live                      |
+-----------------------------------+-----------------------------------+

Sensors + Coding

+-----------------------------------+-----------------------------------+
| ## HM3301 - Dust Sensor           |                                   |
+===================================+===================================+
| Buy: [[Grove Laser PM2.5 Dust     | -   used for continuous and       |
| Sensor (HM3301) -                 |     > real-time detection of dust |
| RobotShop]{.underline}](http      |     > in the air.                 |
| s://www.robotshop.com/products/gr |                                   |
| ove-laser-pm25-dust-sensor-hm3301 | -                                 |
| ?srsltid=AfmBOorchGyyJaX1OiRnQnjk |                                   |
| HcjC5-3EbThS9AytuIxg_Q3Tfj4OYYzs) |                                   |
|                                   |                                   |
| Datasheet: [[Microsoft Word -     |                                   |
| Bendable EL                       |                                   |
| Wire]{.underline}](http           |                                   |
| s://media.digikey.com/pdf/Data%20 |                                   |
| Sheets/Seeed%20Technology/Grove_L |                                   |
| aser_PM2.5_Sensor_HM3301_Web.pdf) |                                   |
|                                   |                                   |
| Official Wiki (has lots of info / |                                   |
| references): [[Grove - Laser      |                                   |
| PM2.5 Sensor (HM3301) \| Seeed    |                                   |
| Studio                            |                                   |
| Wiki]{.underlin                   |                                   |
| e}](https://wiki.seeedstudio.com/ |                                   |
| Grove-Laser_PM2.5_Sensor-HM3301/) |                                   |
+-----------------------------------+-----------------------------------+
| Need to Know                      |                                   |
+-----------------------------------+-----------------------------------+
| Power:                            | > 3.3V or 5V                      |
+-----------------------------------+-----------------------------------+
| Weight:                           |                                   |
+-----------------------------------+-----------------------------------+
| Protocol:                         | > I2C (address 0x40 hex -\> 64    |
|                                   | > decimal)                        |
+-----------------------------------+-----------------------------------+
| Stability Time (set delay):       | > 30sec after power on            |
+-----------------------------------+-----------------------------------+
| Rate:                             |                                   |
+-----------------------------------+-----------------------------------+
| Temp:                             | > -10 \~ 60 C                     |
+-----------------------------------+-----------------------------------+
| Humidify:                         | > 10% \~ 90% RH (non-condensing)  |
+-----------------------------------+-----------------------------------+
| Pinout                            |                                   |
+-----------------------------------+-----------------------------------+
| Pinout                            | > GND Black GND 5                 |
|                                   | >                                 |
| ![](media/image4.                 | > V or 3.3V Red VCC               |
| png){width="3.1041666666666665in" | >                                 |
| height="1.7916666666666667in"}    | > SDA White SDA                   |
|                                   | >                                 |
|                                   | > SCL Yellow SCL                  |
+-----------------------------------+-----------------------------------+
| Library:                          | Need to read                      |
| [[Seeed-Studio                    |                                   |
| /Seeed_PM2_5_sensor_HM3301]{.unde |                                   |
| rline}](https://github.com/Seeed- |                                   |
| Studio/Seeed_PM2_5_sensor_HM3301) |                                   |
+-----------------------------------+-----------------------------------+

+-----------------------------------+-----------------------------------+
| ## BME280 - Humidity sensor       |                                   |
+===================================+===================================+
| Buy: [[Humidity Sensor BME280 \|  | -                                 |
| Bosch                             |                                   |
| Sensortec]{.und                   |                                   |
| erline}](https://www.bosch-sensor |                                   |
| tec.com/en/products/environmental |                                   |
| -sensors/humidity-sensors-bme280) |                                   |
|                                   |                                   |
| Datasheet: [[BME280               |                                   |
| Datasheet]{.underlin              |                                   |
| e}](https://www.bosch-sensortec.c |                                   |
| om/media/boschsensortec/downloads |                                   |
| /datasheets/bst-bme280-ds002.pdf) |                                   |
|                                   |                                   |
| Quick Overview: [[BME280 Shuttle  |                                   |
| Board 3.0                         |                                   |
| Flyer]{.underl                    |                                   |
| ine}](https://www.bosch-sensortec |                                   |
| .com/media/boschsensortec/downloa |                                   |
| ds/shuttle_board_flyer/applicatio |                                   |
| n_board_3_1/bst-bme280-sf000.pdf) |                                   |
+-----------------------------------+-----------------------------------+
| Need to Know                      |                                   |
+-----------------------------------+-----------------------------------+
| Power:                            | > 1.2V - 3.6 V                    |
+-----------------------------------+-----------------------------------+
| Weight:                           |                                   |
+-----------------------------------+-----------------------------------+
| Protocol:                         | > I2C and SPI                     |
+-----------------------------------+-----------------------------------+
| Stability Time (set delay):       | > 0.5 and 1000ms                  |
+-----------------------------------+-----------------------------------+
| Rate:                             | > suggested for weather: 1Hz      |
|                                   | >                                 |
|                                   | > oversampling: pressure x0,      |
|                                   | > temperature x1, humidity x1     |
+-----------------------------------+-----------------------------------+
| Temp:                             |                                   |
+-----------------------------------+-----------------------------------+
| Humidify:                         |                                   |
+-----------------------------------+-----------------------------------+
| Pinout                            |                                   |
+-----------------------------------+-----------------------------------+
| ![](media/image1.                 | I2C                               |
| png){width="3.1041666666666665in" |                                   |
| height="1.5416666666666667in"}    | -   SCK: serial clock (SCL)       |
|                                   |                                   |
| ![](media/image3.                 | -   SDI: data (SDA)               |
| png){width="3.1041666666666665in" |                                   |
| height="1.6666666666666667in"}    | -   SDO: Slave address LSB        |
|                                   |                                   |
|                                   | -   GND: 0                        |
|                                   |                                   |
|                                   | -   VDDIO: 1 (needs resistor)     |
|                                   |                                   |
|                                   | SPI (4-3 wires)                   |
|                                   |                                   |
|                                   | -   CSB: chip select, active low  |
|                                   |                                   |
|                                   | -   SCK: serial clock             |
|                                   |                                   |
|                                   | -   SDI: serial data input; data  |
|                                   |     > input/out for 3 wire        |
|                                   |                                   |
|                                   | -   SDO: serial data output; hi-Z |
|                                   |     > in 3 wire mode              |
+-----------------------------------+-----------------------------------+
| ![](media/image2.                 |                                   |
| png){width="3.1041666666666665in" |                                   |
| height="2.8472222222222223in"}    |                                   |
+-----------------------------------+-----------------------------------+
| Library:                          |                                   |
| [                                 |                                   |
| [boschsensortec/BME280_SensorAPI: |                                   |
| Bosch Sensortec BME280 sensor     |                                   |
| driver. To report issues, go      |                                   |
| to                                |                                   |
| ]{.underline}](https://github.com |                                   |
| /boschsensortec/BME280_SensorAPI) |                                   |
| [[https://community.bos           |                                   |
| ch-sensortec.com/t5/Bosch-Sensort |                                   |
| ec-Community/ct-p/bst_community]{ |                                   |
| .underline}](https://community.bo |                                   |
| sch-sensortec.com/t5/Bosch-Sensor |                                   |
| tec-Community/ct-p/bst_community) |                                   |
|                                   |                                   |
| Outdated Library?: [[Home ·       |                                   |
| Zanduino/BME280                   |                                   |
| Wiki]{.underline}](ht             |                                   |
| tps://github.com/Zanduino/BME280) |                                   |
+-----------------------------------+-----------------------------------+

+-----------------------------------+-----------------------------------+
| ## Op                             |                                   |
| ening and Closing Payload - Motor |                                   |
+===================================+===================================+
| How it will work:                 | Program a motor to open and close |
|                                   | the lid of the payload.           |
|                                   |                                   |
|                                   | The physical set up will be as    |
|                                   | followed:                         |
|                                   |                                   |
|                                   | 1.  The motor will have a string  |
|                                   |     > rolled around it. The       |
|                                   |     > string will be attached to  |
|                                   |     > the ball that will be used  |
|                                   |     > to close and open payload   |
|                                   |                                   |
|                                   | 2.  Motor rotation direction:     |
|                                   |                                   |
|                                   |     a.  clockwise: makes string   |
|                                   |         > length longer, opens    |
|                                   |         > payload                 |
|                                   |                                   |
|                                   |     b.  counter clockwise: string |
|                                   |         > length shorter, closes  |
|                                   |         > payload                 |
|                                   |                                   |
|                                   | The program (in the coding /      |
|                                   | algorithm section)                |
|                                   |                                   |
|                                   | Note: only monitor will need to   |
|                                   | be coded                          |
+-----------------------------------+-----------------------------------+
| What we need / need to know:      | 1.  Component information (for    |
|                                   |     > hardware)                   |
|                                   |                                   |
|                                   |     a.  components working with   |
|                                   |                                   |
|                                   |     b.  how much volts to power   |
|                                   |         > components              |
|                                   |                                   |
|                                   |     c.  how long it takes         |
|                                   |         > components to start up  |
|                                   |                                   |
|                                   |     d.  what protocol to use (for |
|                                   |         > wire connections)       |
|                                   |                                   |
|                                   | 2.  Functionality:                |
|                                   |                                   |
|                                   |     a.  When we want payload to   |
|                                   |         > open and close          |
|                                   |                                   |
|                                   |         i.  open: at certain      |
|                                   |             > altitude or time    |
|                                   |             > reached             |
|                                   |                                   |
|                                   |         ii. close: after certain  |
|                                   |             > amount of time      |
|                                   |             > passed              |
+-----------------------------------+-----------------------------------+
| ### Hardware                      |                                   |
+-----------------------------------+-----------------------------------+
| Protocol (components will be      | I2C                               |
| connected (communicate) / where   |                                   |
| wires will be)                    |                                   |
+-----------------------------------+-----------------------------------+
| Components + Their Roles          | -   TBD (arduino?):               |
|                                   |     > microcontroller             |
|                                   |                                   |
|                                   |     -   where code goes           |
|                                   |                                   |
|                                   |     -   controls the motor        |
|                                   |                                   |
|                                   | -   Motor:                        |
|                                   |                                   |
|                                   |     -   controls string length    |
|                                   |         > used to open and close  |
|                                   |         > payload                 |
+-----------------------------------+-----------------------------------+
| Wire Connections                  |                                   |
+-----------------------------------+-----------------------------------+
|                                   |                                   |
+-----------------------------------+-----------------------------------+
| ### Coding / Algorithm            |                                   |
+-----------------------------------+-----------------------------------+
| Notes:                            | **Control Variable / Condition:** |
|                                   | variable or condition that will   |
|                                   | determine when something will     |
|                                   | execute / run                     |
+-----------------------------------+-----------------------------------+
| **Flowchart**                     | **Pseudo Code**                   |
+-----------------------------------+-----------------------------------+
|                                   | Variables                         |
|                                   |                                   |
|                                   | Setup - will only happen once     |
|                                   |                                   |
|                                   | 1.  configure motor               |
|                                   |                                   |
|                                   | 2.  initialize control variables  |
|                                   |                                   |
|                                   | Loop - will happen continuously   |
|                                   |                                   |
|                                   | 1.                                |
+-----------------------------------+-----------------------------------+
| Control Variable (Open and Close  |                                   |
| Based on) - Time                  |                                   |
+-----------------------------------+-----------------------------------+
| Pros:                             | Cons:                             |
|                                   |                                   |
| -   guaranteed to work (unless    | -   we will have to guess when we |
|     > power suddenly goes off)    |     > will be a good time to open |
|                                   |     > and close                   |
| -   easier to code                |                                   |
|                                   |     -   can be an issue since we  |
|                                   |         > will need to guess how  |
|                                   |         > long we might need to   |
|                                   |         > wait for our rocket to  |
|                                   |         > launch                  |
|                                   |                                   |
|                                   |     -   need to guess the time it |
|                                   |         > will take the rocket to |
|                                   |         > reach desired altitude  |
|                                   |         > to open                 |
|                                   |                                   |
|                                   | -   may execute when we don\'t    |
|                                   |     > want it to                  |
|                                   |                                   |
|                                   | -   not as much control of when   |
|                                   |     > we want it to execute       |
|                                   |                                   |
|                                   |     -   only have once chance to  |
|                                   |         > execute                 |
|                                   |                                   |
|                                   |     -   cannot create backup      |
|                                   |         > conditions              |
+-----------------------------------+-----------------------------------+
| Control Variable (Open and Close  |                                   |
| Based on) - Altitude / How high   |                                   |
| Rocket is                         |                                   |
+-----------------------------------+-----------------------------------+
| Pros:                             | Cons:                             |
|                                   |                                   |
| -   no need to guess              | -   Will need to figure out where |
|                                   |     > it can go                   |
|     -   better if we are unsure   |                                   |
|         > about timing            |     -   cannot be in payload      |
|                                   |         > because payload needs   |
| -   more flexibility on choosing  |         > to air to calculate     |
|     > when to execute             |         > altitude                |
|                                   |                                   |
|     -   can create backup         | -   chance it might not open if   |
|         > conditions incase main  |     > altimeter is broken or not  |
|         > one fails               |     > reading altitude correctly  |
|                                   |                                   |
|     -                             | -   will not execute if rocket    |
|                                   |     > does not reach desired      |
| -   can execute more accurately   |     > altitude                    |
|                                   |                                   |
|     -   can actually get it open  |                                   |
|         > and close when we       |                                   |
|         > actually want it to     |                                   |
+-----------------------------------+-----------------------------------+
| Control Variable (Open and Close  |                                   |
| Based on) - Multiple Conditions   |                                   |
+-----------------------------------+-----------------------------------+
| Pros:                             | Cons:                             |
|                                   |                                   |
| -   easier for adjustments / take | -   more complicated / likely to  |
|     > into account of unexpected  |     > make logical errors         |
|     > conditions                  |                                   |
|                                   |     -   we have to be careful on  |
| -   way more accurate on when we  |         > how we keep track of    |
|     > want it to execute          |         > things                  |
|                                   |                                   |
| -   multiple backups              | -   will take up more space (and  |
|                                   |     > weight)                     |
|     -   if one sensor fails or if |                                   |
|         > it doesn\'t execute     |     -   sensors are small but     |
|         > when it should we will  |                                   |
|         > be fine (another sensor | -   cost more money (if we don\'t |
|         > / condition will        |     > have sensors) :\'(          |
|         > execute it)             |                                   |
+-----------------------------------+-----------------------------------+

Microbe Collection

+-----------------------------------+-----------------------------------+
| ## Microbe Collection             |                                   |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

+-----------------------------------+-----------------------------------+
| **Part**                          | **Purpose**                       |
+===================================+===================================+
| Kevlar cord                       | -   Pull the ball back into the   |
|                                   |     > lid                         |
| [[https://www.apogeerockets.      |                                   |
| com/Building_Supplies/Parachutes_ |                                   |
| Recovery_Equipment/Shock_Cord/Kev |                                   |
| lar_Cord_100]{.underline}](https: |                                   |
| //www.apogeerockets.com/Building_ |                                   |
| Supplies/Parachutes_Recovery_Equi |                                   |
| pment/Shock_Cord/Kevlar_Cord_100) |                                   |
+-----------------------------------+-----------------------------------+
|                                   |                                   |
+-----------------------------------+-----------------------------------+
|                                   |                                   |
+-----------------------------------+-----------------------------------+
|                                   |                                   |
+-----------------------------------+-----------------------------------+
