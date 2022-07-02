Smart Auto Irrigation  

The SAI  detects soil humidity using a  sensor and activates the pump when the soil is dry (below the soil humidity threshold set by the user).   

The pump is active for a set amount of seconds then stops to allow water to penetrate the soil. A reading is taken every 30 seconds and the cycle restarts until the desired humidity level is reached. 
Plant growth stage (Vegitative/Bloom)
 can be set to change how dry the soil gets before triggering the pump to irrigate. 

The soil moisture sensor can be calibrated to suit the type of growing medium used.

Hardware required

Splash proof case
Capacitive Soil moisture sensor 
5v Relay
240v Submersible Pump with ext power / 12 Volt pump and 12V submersible pump / 5v 
Microcontroller - Nodemcu
USB power supply (ext battery or charger )
LCD Screen

Features : 

Wifi Enabled
The device connects to a WIFI Network to send and receive MQTT msgs 


MQTT Enabled Publishing of Humidity level to MQTT broker (Can be viewed on phone)

Stage setting via MQTT (Veg or Bloom)  This setting allows the device to change the level at which the pump will activate. In VEG the trigger is set at 50%, in Bloom the trigger is set at 40%


Irrigation Duration - This setting has 4 presets for the duration the pump is enabled.


Sensor Calibration :This setting allows to set the DRY and WET calibration in the required medium.


OTA UPDATES ENABLED  







Code

GitHub link

Future upgrades


Lipo Batteries w/ Solar recharge (Outdoor version)
Twin sensor
Longer sensor cables 




Timer Version Features
Irrigation Cycle PresetTimings 0-60sec, 1-2hrs, 2-4hrs, 3-8hrs, 4-8hrs
Irrigation duration presets 1-3sec, 2-6sec, 3-12sec,  4-15sec
MQTT Parameter settings
Wifi 
5V - USB POWER


