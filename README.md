#Project Title- Automatic smart-egg-incubator
##Problem & Solution
**Problem:** Small-scale farmers in uganda lose chicks due to inconsistent temperature/humidity and power outages during incubation. Manual egg turning is also labour-intensive and error-prone.

**Solution:** This system auatomates temperature + humidity control, switches  between AC mains and battery backup automatically, turns eggs every 2 hours via a motor,and includes GSM alerts + mobile app monitoring. users can monitor and control the incubator remotely.

##Setup Instructions
**1. Hardware Requiremens:**
-Arduino +DHT22+DS18B20+ SIM800L GSM Module
-100w heater bulbs,dc fans,synchronous motor,relay modules
-12v battery+ AC mains input

**2.SoftwareRequiremens:**
-Arduino IDE 2.0+
-Required Libraries: DHT.h,WiFi.h.firebase ESP32.h
-Mobile app: Install APK from '/app-release.apk' ,run fluterr project in '/app'

**3.Installation & Configuration:**
1. Connect hardware as per 'wiring_diagram.png in '/docs'
2. Open 'firmware/incubator.ino' in Arduino IDE
3. Update WiFi SSID,password and Firebase credetials in 'config.h'
4. Upload code to Arduino 
5. For mobile app: 'cd app' and 'flutter pub get' and 'flutter run'

**4.Running the project:**
Power on the incubator. Connect phone to same WiFi. Open app and login. Dashboard will show live temp/humidity.

##circuit diagram 
see'/docs/wiring_diagram.png'

##Team 
-Kimbowa Patrick- Team Lead & Embedded Systems (CEO)
-Wandera Bruno - Technical Lead & Finance Lead (CTO)
-Mukisa Joseph - Hardware Lead 
-Abaho vine - Marketing Lead
-Kwesiga Innocent -Operations Lead





