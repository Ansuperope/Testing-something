<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><h2 id="payload">Payload</h2></th>
</tr>
<tr class="odd">
<th><p><strong><mark>Gianni C Restrictions:</mark></strong></p>
<p><mark>**as of 1/24/26:**</mark></p></th>
<th><p><mark>Diameter: No more than 114mm</mark></p>
<p><mark>Length: No more than 152mm</mark></p>
<p><mark>Mass: No more than 500g</mark></p></th>
</tr>
<tr class="header">
<th><strong>Notes</strong></th>
<th><ul>
<li><blockquote>
<p>scientific payload</p>
</blockquote>
<ul>
<li><blockquote>
<p>in shape of cube</p>
</blockquote></li>
</ul></li>
<li><blockquote>
<p><mark>sensors on the side</mark></p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th><strong>Goal</strong></th>
<th><strong>Notes</strong></th>
</tr>
<tr class="header">
<th><ol type="1">
<li><blockquote>
<p><strong>Create flight path (not live)</strong></p>
</blockquote>
<ol type="a">
<li><blockquote>
<p>GPS collects the data:</p>
</blockquote>
<ol type="i">
<li><blockquote>
<p>time</p>
</blockquote></li>
<li><blockquote>
<p>location</p>
</blockquote></li>
<li><blockquote>
<p>orientation</p>
</blockquote></li>
</ol></li>
<li><blockquote>
<p>saved to a SD card as an csv file</p>
</blockquote></li>
</ol></li>
</ol></th>
<th></th>
</tr>
<tr class="odd">
<th><ol start="2" type="1">
<li><blockquote>
<p><strong>Transmit data to a receiver (live)</strong></p>
</blockquote>
<ol type="a">
<li><blockquote>
<p>will have a display to show rocket location</p>
</blockquote></li>
<li><blockquote>
<p>used to track rocket location</p>
</blockquote></li>
</ol></li>
</ol></th>
<th></th>
</tr>
<tr class="header">
<th><ol start="3" type="1">
<li><blockquote>
<p><strong>Collect microbes</strong></p>
</blockquote>
<ol type="a">
<li><blockquote>
<p>1 door will open and close:</p>
</blockquote>
<ol type="i">
<li><blockquote>
<p>agar plate lid will be on the door</p>
</blockquote></li>
<li><blockquote>
<p>opens 30 seconds after</p>
</blockquote></li>
</ol></li>
<li><blockquote>
<p>air will be pushed to an agar plate</p>
</blockquote></li>
<li><blockquote>
<p>agar plate Velcroed(?) to door and payload</p>
</blockquote></li>
</ol></li>
</ol></th>
<th><ul>
<li><blockquote>
<p>cannot be contaminated</p>
</blockquote>
<ul>
<li><blockquote>
<p>must be airtight</p>
</blockquote></li>
</ul></li>
<li><blockquote>
<p>agar needs to be removable</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th><ol start="4" type="1">
<li><blockquote>
<p><strong>Collect data and save to SD card as a csv file</strong></p>
</blockquote>
<ol type="a">
<li><blockquote>
<p>get the data</p>
</blockquote>
<ol type="i">
<li><blockquote>
<p>particulates</p>
</blockquote></li>
<li><blockquote>
<p>gasses</p>
</blockquote></li>
<li><blockquote>
<p>pressure</p>
</blockquote></li>
<li><blockquote>
<p>humidity</p>
</blockquote></li>
</ol></li>
<li><blockquote>
<p>more readings better (no specific rate yet)</p>
</blockquote></li>
</ol></li>
</ol></th>
<th></th>
</tr>
<tr class="header">
<th><ol start="5" type="1">
<li><blockquote>
<p><strong>Camera</strong></p>
</blockquote>
<ol type="a">
<li><blockquote>
<p>video will not be live</p>
</blockquote></li>
<li><blockquote>
<p>save to an SD card</p>
</blockquote></li>
</ol></li>
</ol></th>
<th></th>
</tr>
</thead>
<tbody>
</tbody>
</table>
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><h2 id="sensors-components">Sensors /
Components</h2></th>
</tr>
<tr class="odd">
<th colspan="2"><strong>Collecting microbes</strong></th>
</tr>
<tr class="header">
<th>Motors</th>
<th><ul>
<li><blockquote>
<p>to open and close doors</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th>Agar plate</th>
<th></th>
</tr>
<tr class="header">
<th>Velcro</th>
<th><ul>
<li><blockquote>
<p>hold agar plates</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="2"><strong>Collecting Data</strong></th>
</tr>
<tr class="header">
<th rowspan="2">Teensy</th>
<th><p>What for / what it does:</p>
<ul>
<li></li>
</ul></th>
</tr>
<tr class="odd">
<th><p>Other Notes:</p>
<ul>
<li></li>
</ul></th>
</tr>
<tr class="header">
<th>SD card</th>
<th></th>
</tr>
<tr class="odd">
<th>Lora / Radio for transmitting / receiving</th>
<th></th>
</tr>
<tr class="header">
<th rowspan="2">GPS</th>
<th><p>What for / what it does:</p>
<ul>
<li><blockquote>
<p>gets location, orientation and time for:</p>
</blockquote>
<ul>
<li><blockquote>
<p>receiver</p>
</blockquote></li>
<li><blockquote>
<p>flight path</p>
</blockquote></li>
<li><blockquote>
<p>sd</p>
</blockquote></li>
</ul></li>
</ul></th>
</tr>
<tr class="odd">
<th><p>Other Notes:</p>
<ul>
<li><blockquote>
<p>needs to read 3 satellites or more for more accuracy</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th><p>Grove Laser PM2.5 Dust Sensor</p>
<p><a
href="https://www.robotshop.com/products/grove-laser-pm25-dust-sensor-hm3301?srsltid=AfmBOorchGyyJaX1OiRnQnjkHcjC5-3EbThS9AytuIxg_Q3Tfj4OYYzs"><u>https://www.robotshop.com/products/grove-laser-pm25-dust-sensor-hm3301?srsltid=AfmBOorchGyyJaX1OiRnQnjkHcjC5-3EbThS9AytuIxg_Q3Tfj4OYYzs</u></a></p></th>
<th><ul>
<li><blockquote>
<p>particulates</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th><p>MiCS-6814 and/or CCS811</p>
<p><a
href="https://www.bosch-sensortec.com/en/products/environmental-sensors/humidity-sensors-bme280"><u>Humidity
Sensor BME280 | Bosch Sensortec</u></a></p>
<p>or</p>
<p><a
href="https://learn.adafruit.com/adafruit-ccs811-air-quality-sensor/overview"><u>Overview
| Adafruit CCS811 Air Quality Sensor | Adafruit Learning
System</u></a></p></th>
<th><ul>
<li><blockquote>
<p>gasses</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th><p>BME280</p>
<p><a
href="https://www.bosch-sensortec.com/en/products/environmental-sensors/humidity-sensors-bme280"><u>Humidity
Sensor BME280 | Bosch Sensortec</u></a></p></th>
<th><ul>
<li><blockquote>
<p>weather</p>
</blockquote>
<ul>
<li><blockquote>
<p>pressure</p>
</blockquote></li>
<li><blockquote>
<p>humidity</p>
</blockquote></li>
</ul></li>
</ul></th>
</tr>
<tr class="odd">
<th></th>
<th></th>
</tr>
<tr class="header">
<th>Camera</th>
<th><ul>
<li><blockquote>
<p>not live</p>
</blockquote></li>
</ul></th>
</tr>
</thead>
<tbody>
</tbody>
</table>
<p>Sensors + Coding</p>
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><h2 id="hm3301---dust-sensor">HM3301 - Dust
Sensor</h2></th>
</tr>
<tr class="odd">
<th><p>Buy: <a
href="https://www.robotshop.com/products/grove-laser-pm25-dust-sensor-hm3301?srsltid=AfmBOorchGyyJaX1OiRnQnjkHcjC5-3EbThS9AytuIxg_Q3Tfj4OYYzs"><u>Grove
Laser PM2.5 Dust Sensor (HM3301) - RobotShop</u></a></p>
<p>Datasheet: <a
href="https://media.digikey.com/pdf/Data%20Sheets/Seeed%20Technology/Grove_Laser_PM2.5_Sensor_HM3301_Web.pdf"><u>Microsoft
Word - Bendable EL Wire</u></a></p>
<p>Official Wiki (has lots of info / references): <a
href="https://wiki.seeedstudio.com/Grove-Laser_PM2.5_Sensor-HM3301/"><u>Grove
- Laser PM2.5 Sensor (HM3301) | Seeed Studio Wiki</u></a></p></th>
<th><ul>
<li><blockquote>
<p>used for continuous and real-time detection of dust in the air.</p>
</blockquote></li>
<li></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="2">Need to Know</th>
</tr>
<tr class="odd">
<th>Power:</th>
<th><blockquote>
<p>3.3V or 5V</p>
</blockquote></th>
</tr>
<tr class="header">
<th>Weight:</th>
<th></th>
</tr>
<tr class="odd">
<th>Protocol:</th>
<th><blockquote>
<p>I2C (address 0x40 hex -&gt; 64 decimal)</p>
</blockquote></th>
</tr>
<tr class="header">
<th>Stability Time (set delay):</th>
<th><blockquote>
<p>30sec after power on</p>
</blockquote></th>
</tr>
<tr class="odd">
<th>Rate:</th>
<th></th>
</tr>
<tr class="header">
<th>Temp:</th>
<th><blockquote>
<p>-10 ~ 60 C</p>
</blockquote></th>
</tr>
<tr class="odd">
<th>Humidify:</th>
<th><blockquote>
<p>10% ~ 90% RH (non-condensing)</p>
</blockquote></th>
</tr>
<tr class="header">
<th colspan="2">Pinout</th>
</tr>
<tr class="odd">
<th><p>Pinout</p>
<p><img src="assets/media/image4.png"
style="width:3.10417in;height:1.79167in" /></p></th>
<th><blockquote>
<p>GND Black GND 5</p>
<p>V or 3.3V Red VCC</p>
<p>SDA White SDA</p>
<p>SCL Yellow SCL</p>
</blockquote></th>
</tr>
<tr class="header">
<th>Library: <a
href="https://github.com/Seeed-Studio/Seeed_PM2_5_sensor_HM3301"><u>Seeed-Studio/Seeed_PM2_5_sensor_HM3301</u></a></th>
<th>Need to read</th>
</tr>
</thead>
<tbody>
</tbody>
</table>
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><h2 id="bme280---humidity-sensor">BME280 - Humidity
sensor</h2></th>
</tr>
<tr class="odd">
<th><p>Buy: <a
href="https://www.bosch-sensortec.com/en/products/environmental-sensors/humidity-sensors-bme280"><u>Humidity
Sensor BME280 | Bosch Sensortec</u></a></p>
<p>Datasheet: <a
href="https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bme280-ds002.pdf"><u>BME280
Datasheet</u></a></p>
<p>Quick Overview: <a
href="https://www.bosch-sensortec.com/media/boschsensortec/downloads/shuttle_board_flyer/application_board_3_1/bst-bme280-sf000.pdf"><u>BME280
Shuttle Board 3.0 Flyer</u></a></p></th>
<th><ul>
<li></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="2">Need to Know</th>
</tr>
<tr class="odd">
<th>Power:</th>
<th><blockquote>
<p>1.2V - 3.6 V</p>
</blockquote></th>
</tr>
<tr class="header">
<th>Weight:</th>
<th></th>
</tr>
<tr class="odd">
<th>Protocol:</th>
<th><blockquote>
<p>I2C and SPI</p>
</blockquote></th>
</tr>
<tr class="header">
<th>Stability Time (set delay):</th>
<th><blockquote>
<p>0.5 and 1000ms</p>
</blockquote></th>
</tr>
<tr class="odd">
<th>Rate:</th>
<th><blockquote>
<p>suggested for weather: 1Hz</p>
<p>oversampling: pressure x0, temperature x1, humidity x1</p>
</blockquote></th>
</tr>
<tr class="header">
<th>Temp:</th>
<th></th>
</tr>
<tr class="odd">
<th>Humidify:</th>
<th></th>
</tr>
<tr class="header">
<th colspan="2">Pinout</th>
</tr>
<tr class="odd">
<th><p><img src="assets/media/image3.png"
style="width:3.10417in;height:1.54167in" /></p>
<p><img src="assets/media/image2.png"
style="width:3.10417in;height:1.66667in" /></p></th>
<th><p>I2C</p>
<ul>
<li><blockquote>
<p>SCK: serial clock (SCL)</p>
</blockquote></li>
<li><blockquote>
<p>SDI: data (SDA)</p>
</blockquote></li>
<li><blockquote>
<p>SDO: Slave address LSB</p>
</blockquote></li>
<li><blockquote>
<p>GND: 0</p>
</blockquote></li>
<li><blockquote>
<p>VDDIO: 1 (needs resistor)</p>
</blockquote></li>
</ul>
<p>SPI (4-3 wires)</p>
<ul>
<li><blockquote>
<p>CSB: chip select, active low</p>
</blockquote></li>
<li><blockquote>
<p>SCK: serial clock</p>
</blockquote></li>
<li><blockquote>
<p>SDI: serial data input; data input/out for 3 wire</p>
</blockquote></li>
<li><blockquote>
<p>SDO: serial data output; hi-Z in 3 wire mode</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th><img src="assets/media/image1.png"
style="width:3.10417in;height:2.84722in" /></th>
<th></th>
</tr>
<tr class="odd">
<th><p>Library: <a
href="https://github.com/boschsensortec/BME280_SensorAPI"><u>boschsensortec/BME280_SensorAPI:
Bosch Sensortec BME280 sensor driver. To report issues, go to</u></a> <a
href="https://community.bosch-sensortec.com/t5/Bosch-Sensortec-Community/ct-p/bst_community"><u>https://community.bosch-sensortec.com/t5/Bosch-Sensortec-Community/ct-p/bst_community</u></a></p>
<p>Outdated Library?: <a
href="https://github.com/Zanduino/BME280"><u>Home · Zanduino/BME280
Wiki</u></a></p></th>
<th></th>
</tr>
</thead>
<tbody>
</tbody>
</table>
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><h2 id="opening-and-closing-payload---motor">Opening and
Closing Payload - Motor</h2></th>
</tr>
<tr class="odd">
<th>How it will work:</th>
<th><p>Program a motor to open and close the lid of the payload.</p>
<p>The physical set up will be as followed:</p>
<ol type="1">
<li><blockquote>
<p>The motor will have a string rolled around it. The string will be
attached to the ball that will be used to close and open payload</p>
</blockquote></li>
<li><blockquote>
<p>Motor rotation direction:</p>
</blockquote>
<ol type="a">
<li><blockquote>
<p>clockwise: makes string length longer, opens payload</p>
</blockquote></li>
<li><blockquote>
<p>counter clockwise: string length shorter, closes payload</p>
</blockquote></li>
</ol></li>
</ol>
<p>The program (in the coding / algorithm section)</p>
<p>Note: only monitor will need to be coded</p></th>
</tr>
<tr class="header">
<th>What we need / need to know:</th>
<th><ol type="1">
<li><blockquote>
<p>Component information (for hardware)</p>
</blockquote>
<ol type="a">
<li><blockquote>
<p>components working with</p>
</blockquote></li>
<li><blockquote>
<p>how much volts to power components</p>
</blockquote></li>
<li><blockquote>
<p>how long it takes components to start up</p>
</blockquote></li>
<li><blockquote>
<p>what protocol to use (for wire connections)</p>
</blockquote></li>
</ol></li>
<li><blockquote>
<p>Functionality:</p>
</blockquote>
<ol type="a">
<li><blockquote>
<p>When we want payload to open and close</p>
</blockquote>
<ol type="i">
<li><blockquote>
<p>open: at certain altitude or time reached</p>
</blockquote></li>
<li><blockquote>
<p>close: after certain amount of time passed</p>
</blockquote></li>
</ol></li>
</ol></li>
</ol></th>
</tr>
<tr class="odd">
<th colspan="2"><h3 id="hardware">Hardware</h3></th>
</tr>
<tr class="header">
<th>Protocol (components will be connected (communicate) / where wires
will be)</th>
<th>I2C</th>
</tr>
<tr class="odd">
<th>Components + Their Roles</th>
<th><ul>
<li><blockquote>
<p>TBD (arduino?): microcontroller</p>
</blockquote>
<ul>
<li><blockquote>
<p>where code goes</p>
</blockquote></li>
<li><blockquote>
<p>controls the motor</p>
</blockquote></li>
</ul></li>
<li><blockquote>
<p>Motor:</p>
</blockquote>
<ul>
<li><blockquote>
<p>controls string length used to open and close payload</p>
</blockquote></li>
</ul></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="2">Wire Connections</th>
</tr>
<tr class="odd">
<th></th>
<th></th>
</tr>
<tr class="header">
<th colspan="2"><h3 id="coding-algorithm">Coding / Algorithm</h3></th>
</tr>
<tr class="odd">
<th>Notes:</th>
<th><strong>Control Variable / Condition:</strong> variable or condition
that will determine when something will execute / run</th>
</tr>
<tr class="header">
<th><strong>Flowchart</strong></th>
<th><strong>Pseudo Code</strong></th>
</tr>
<tr class="odd">
<th></th>
<th><p>Variables</p>
<p>Setup - will only happen once</p>
<ol type="1">
<li><blockquote>
<p>configure motor</p>
</blockquote></li>
<li><blockquote>
<p>initialize control variables</p>
</blockquote></li>
</ol>
<p>Loop - will happen continuously</p>
<ol type="1">
<li></li>
</ol></th>
</tr>
<tr class="header">
<th colspan="2">Control Variable (Open and Close Based on) - Time</th>
</tr>
<tr class="odd">
<th><p>Pros:</p>
<ul>
<li><blockquote>
<p>guaranteed to work (unless power suddenly goes off)</p>
</blockquote></li>
<li><blockquote>
<p>easier to code</p>
</blockquote></li>
</ul></th>
<th><p>Cons:</p>
<ul>
<li><blockquote>
<p>we will have to guess when we will be a good time to open and
close</p>
</blockquote>
<ul>
<li><blockquote>
<p>can be an issue since we will need to guess how long we might need to
wait for our rocket to launch</p>
</blockquote></li>
<li><blockquote>
<p>need to guess the time it will take the rocket to reach desired
altitude to open</p>
</blockquote></li>
</ul></li>
<li><blockquote>
<p>may execute when we don't want it to</p>
</blockquote></li>
<li><blockquote>
<p>not as much control of when we want it to execute</p>
</blockquote>
<ul>
<li><blockquote>
<p>only have once chance to execute</p>
</blockquote></li>
<li><blockquote>
<p>cannot create backup conditions</p>
</blockquote></li>
</ul></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="2">Control Variable (Open and Close Based on) - Altitude /
How high Rocket is</th>
</tr>
<tr class="odd">
<th><p>Pros:</p>
<ul>
<li><blockquote>
<p>no need to guess</p>
</blockquote>
<ul>
<li><blockquote>
<p>better if we are unsure about timing</p>
</blockquote></li>
</ul></li>
<li><blockquote>
<p>more flexibility on choosing when to execute</p>
</blockquote>
<ul>
<li><blockquote>
<p>can create backup conditions incase main one fails</p>
</blockquote></li>
<li></li>
</ul></li>
<li><blockquote>
<p>can execute more accurately</p>
</blockquote>
<ul>
<li><blockquote>
<p>can actually get it open and close when we actually want it to</p>
</blockquote></li>
</ul></li>
</ul></th>
<th><p>Cons:</p>
<ul>
<li><blockquote>
<p>Will need to figure out where it can go</p>
</blockquote>
<ul>
<li><blockquote>
<p>cannot be in payload because payload needs to air to calculate
altitude</p>
</blockquote></li>
</ul></li>
<li><blockquote>
<p>chance it might not open if altimeter is broken or not reading
altitude correctly</p>
</blockquote></li>
<li><blockquote>
<p>will not execute if rocket does not reach desired altitude</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="2">Control Variable (Open and Close Based on) - Multiple
Conditions</th>
</tr>
<tr class="odd">
<th><p>Pros:</p>
<ul>
<li><blockquote>
<p>easier for adjustments / take into account of unexpected
conditions</p>
</blockquote></li>
<li><blockquote>
<p>way more accurate on when we want it to execute</p>
</blockquote></li>
<li><blockquote>
<p>multiple backups</p>
</blockquote>
<ul>
<li><blockquote>
<p>if one sensor fails or if it doesn't execute when it should we will
be fine (another sensor / condition will execute it)</p>
</blockquote></li>
</ul></li>
</ul></th>
<th><p>Cons:</p>
<ul>
<li><blockquote>
<p>more complicated / likely to make logical errors</p>
</blockquote>
<ul>
<li><blockquote>
<p>we have to be careful on how we keep track of things</p>
</blockquote></li>
</ul></li>
<li><blockquote>
<p>will take up more space (and weight)</p>
</blockquote>
<ul>
<li><blockquote>
<p>sensors are small but</p>
</blockquote></li>
</ul></li>
<li><blockquote>
<p>cost more money (if we don't have sensors) :'(</p>
</blockquote></li>
</ul></th>
</tr>
</thead>
<tbody>
</tbody>
</table>
<p>Microbe Collection</p>
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><h2 id="microbe-collection">Microbe Collection</h2></th>
</tr>
</thead>
<tbody>
</tbody>
</table>
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Part</strong></th>
<th><strong>Purpose</strong></th>
</tr>
<tr class="odd">
<th><p>Kevlar cord</p>
<p><a
href="https://www.apogeerockets.com/Building_Supplies/Parachutes_Recovery_Equipment/Shock_Cord/Kevlar_Cord_100"><u>https://www.apogeerockets.com/Building_Supplies/Parachutes_Recovery_Equipment/Shock_Cord/Kevlar_Cord_100</u></a></p></th>
<th><ul>
<li><blockquote>
<p>Pull the ball back into the lid</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th></th>
<th></th>
</tr>
<tr class="odd">
<th></th>
<th></th>
</tr>
<tr class="header">
<th></th>
<th></th>
</tr>
</thead>
<tbody>
</tbody>
</table>
