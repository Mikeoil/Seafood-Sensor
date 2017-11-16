#Seafood-Sensor
Open Source Arduino Ocean Condition Sensor Monitoring 

Premise: Ken Ekstrom of MIT SeaGrant has confirmed that the following sensors, if correlated with seafood catch counts, 
share the broadest array of measurements to reflect sustainable or unsustainable ocean conditions, to correlate with healthy 
or unhealthy fisheries. 

These hardware requirements are shared Open Source for Arduino so that as many of these Seafood Sensors as possible 
can be built and deployed globally, ultimately resulting in consistent inexpensive universal ocean condition monitoring for replenishment of seafood species worldwide. And our goal is to ensure that the data can be shared with sustainable seafood ratings centers, so we'll also be working on an interactive website to upload data you save worldwide in a consistent format.

Note: this combination of data points, hardware, and software is NOT yet tested, but as it becomes built out, coded, and tested, all info will be shared here. 

Metadata: Date, times of deploy and recovery, depth, latitude and longitude, - can be recorded by Fishers

Universal Needs: 

Arduino RBB “Really Bare Bones” (looks like a Fishbone!): $11 https://moderndevice.com/product/rbbb-kit/ 
Micro SD Card Breakout Board: $7.50 https://www.adafruit.com/products/254 
GPS Breakout Board: $39.95 https://www.adafruit.com/products/746?gclid=CIv_gMW6xNACFZdMDQodxv0LaA 
Case: TBD; must be waterproof to 100’  

Requisite Sensors per Ken’s recommendations: Temperature / Salinity / Ambient Light / Sound: 

Temperature sensor options: 
DS18B20   $9.95 + extras https://www.adafruit.com/products/381 (not for salt water, or corrosive environments; external)
TMP 36 (Analog for greater accuracy; ambient): $1.50 https://www.adafruit.com/products/165 

Salinity (or water level; based on electrical charge; could purchase 2): $4.99 
http://www.elechouse.com/elechouse/index.php?main_page=product_info&cPath=&products_id=2233 

Light Measurement 
Ambient (Diurnal light conditions): $6.95 https://www.adafruit.com/products/1980?gclid=CMKir6ymxNACFZdMDQodxv0LaA 
Analog (Close to Human Eyes): $2.50 https://www.adafruit.com/products/2748 

Sound
Hydrophone Microphone amp w/ auto gain (useful for remote adjustments): $7.95 https://www.adafruit.com/products/1713

Optional Sensors (Camera & Dissolved Carbon [acidity]): 

Infrared Camera (with Arduino Code!): $39.95 https://www.sparkfun.com/products/11610 
Acidity (Carbonization): 
http://sandboxelectronics.com/?post_type=product&p=1341 (100,000 ppm accuracy; easy calibration w/ fresh air every 6 months) $67.95
http://sandboxelectronics.com/?product=50000ppm-mh-z16-ndir-co2-sensor-with-i2cuart-5v3-3v-interface-for-arduinoraspeberry-pi-2 (50,000 ppm accuracy; easy calibration w/ fresh air every 6 months) $67.95
http://sandboxelectronics.com/?product=mh-z16-ndir-co2-sensor-with-i2cuart-5v3-3v-interface-for-arduinoraspeberry-pi (10,000 ppm accuracy; easy calibration w/ fresh air every 6 months) $67.95 
http://sandboxelectronics.com/?product=mg-811-co2-gas-sensor-module&gclid=COWTxKSzxNACFQxMDQodgMALqw $52.95 (uses chemicals & heat; not ideal)
http://www.pro-oceanus.com/images/mini-pro-co2.pdf (not priced; might be proprietary; claim options avaiable) 


