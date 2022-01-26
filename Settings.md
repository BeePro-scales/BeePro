
#### Functions without a serial monitor

Spaudžiame (užsidega žalias led) ir laikom (~3sek.) mygtuką.
1. Užsidegus mėlinam led ir atleidus mygtuką : 
                            kalibravimo režimas dega mėlinas led 15 sek. , per tą laiką at svarstyklių platformos reikia uždėti 1kg. svorį.
                            Jei pavyko žalias diodas mirkteli 2 kartus. Kalibravimas baigtas.
                            Jei nepavyko (neprijunkta platforma, blogas sensorius ir t.t.) raudonas diodas mirkteli 3 kartus.
2. Laikome mygtuka kol dega melinas led (3sek.), užsidega žalias led, atleidžiame :
 SMS testas, išsiuncia testine sms žinutę. 
 Jei nebustatytas šeiminko numeris mirkteli 2 kartus raudonai.
    
#### Functions with a serial monitor                        
The communication speed (baudrate). Usee 9600 bits per second. Set the flow control to Software (8-N-1).

3. Laikome mygtuka kol dega žalias led (3sek.), užsidega raudonas led, atleidžiame :
   Į serial monitor išvedamas menių:
 
 Menu:
1-Test Hardware
2-Send Test SMS
3-Change/Add Master Number
4-Set ID
5-Set Date/Time
6-Power Off

Menių punktai:
1. Tikriname SI7020 sensor ir real time clock  
  Jei viskas gerai gauname:
      Test RTC: OK Date: 01/01/2000 00:00:52
      Test SI7020: OK  H%: 32 Celsius: 20
  Jei Blogai:
      Test RTC: FAIL
      or
      Test SI7020: FAIL
2. Send sms ir testuojame gsm modema.
3. Nustatome į kokį mob. telefono numeris bus siunčiama ataskaita 20 val.
4. Nustatme svarstyklių ID (matosi SMS)
5. Nustatome Datą ir laiką
6. Išjungiame įrenginį.
