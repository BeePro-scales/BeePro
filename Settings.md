#### Functions for scales without a screen:

Short click <3 seconds. If LED blinks for 2 times - the scales are alive and working.

Information that scales provide:

F0.1 +30000000000 LA256 4.00 01/01/2000 00:17:13
hg: 34 cls: 23 wg: 0.00

Explanation:

  - F0.1 - software version;
  - +30000000000 - phone number scales send SMS to;
  - LA256 - Unique scales ID;
  - 4.00 - battery volts;
  - 01/01/2000 00:17:13 - Scales date and time;
  - hg: 34 - Humidity;
  - cls: 23 - Temperature;
  - wg: 0.00 - Day weight difference;

---- Test and calibration mode:

-- Calibration mode:

  Hold the power button till LED turns blue, then release click:
    - Calibration mode is on for 15 seconds. You’ll need to add 1kg. weight on the scales in this period (15 seconds ).
    - In case calibration was successful - the LED blinks 2 times in green color and this means that calibration is done.

  If LED blinks 3 times in red color - calibration failed, this could be for many reasons (unconnected platform, bad sensor, etc.)

-- Send a test SMS message:

  Hold the power button till LED turns blue, hold for another 3 seconds ( do not release click when LED turns blue), when LED turns green, release click :
    - This will send a test SMS message.

  If LED blinks 2 times in red - scales does not have master phone number (you need to set it in the scales settings )

#### Functions for scales with a screen:

Click and hold the power button for 3 seconds, when LED turns red - release click :

Screen menu :

1. Test Hardware
2. Send a Test SMS
3. Change/Add Master Number
4. Set ID
5. Set Date/Time
6. Power Off

Explanation of menu items:

1. Test Hardware - test SI7020 sensor:
  - If the test is successful, see this on the screen:

    Test RTC: OK Date: 01/01/2000 00:00:52
    Test SI7020: OK H%: 32 Celsius: 20

  - If the test failed, see this on the screen:
    Test RTC: FAIL
    or
    Test SI7020: FAIL

2. Send a Test SMS - Send a test SMS and test the GSM module.
3. Change/Add Master Number - Set the main (master) phone number to where to send the day report (scales send a report every day at 20:00 ).
4. Set ID - Set unique scales ID (this ID is visible in the SMS message )
5. Set Date/Time - Set scales date and time.
6. Power Off - Turn off scales.
