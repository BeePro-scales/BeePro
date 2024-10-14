# BeePro Sms Scales
#### Hardware Design Files [Here](/Hardware)
#### Firmware file [Here](/firmware)
#### Assembly Instructions [Here](/AssemblyInstructions.md)
#### How to set the scales [Here](/Settings.md)

#### Technical Characteristics
Humidity measurement: 0 to 100% RH operating range, precision :± 4% RH (max), 0–80% RH
Temperature measurement: -25 to +60 C, ±0.4 °C (max), –10 to 85 °C
Power source: 18650 Li-Ion battery
Standby power consumption: ~1 µA (microampere)

#### SMS Of Daily Report
![Sms](/images/sms.png)     
Lines
1. Scales ID and hive weight at 8pm
2. Daily beehive weight change
3. Scales time
4. Current humidity and temperature
5. Battery volts and remaining charge
6. GSM network signal quality range from 1 to 33
7. 6 hour hive weight, temperature and humidity
8. 12 hour hive weight, temperature and humidity
9. 14 hour hive weight, temperature and humidity
10. 16 hour hive weight, temperature and humidity

#### Over 1 Kg Change In 1 Hour Report
![Sms Alert](/images/alertSms.png)   
Lines
1. Scales ID and hive weight at 8pm
2. Daily beehive weight change
3. Scales time
4. Current humidity and temperature
5. Battery volts and remaining charge
6. GSM network signal quality range from 1 to 33
7. Weight change in last hour

![SmsScales](/images/pcb.jpg)

![3d Model](/images/Case.jpeg)
