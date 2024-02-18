# 3dRotationESP32Nokia5110
This demo should show the blurring effect on a Nokia 5110/PCD8544 LCD display. The display is controlled by an ESP32 and the blurring is dependent on the frame rate. I think the blurring effect up to 25 frames per second is acceptable.

![10 framse per second](/assets/images/fps010.png)

![25 framse per second](/assets/images/fps025.png)

![50 framse per second](/assets/images/fps050.png)

![100 framse per second](/assets/images/fps100.png)

![200 framse per second](/assets/images/fps200.png)

My [Arduino IDE code](/3dRotationESP32Nokia5110/3dRotationESP32Nokia5110.ino) for this demo based on https://github.com/codingABI/3dRotation

# Nokia 5110/PCD8544 LCD display

![Nokia 5110 front side](/assets/images/front.png)

![Nokia 5110 backside](/assets/images/back.png)

Jumper "JP" sets the "LIGHT" pin to ground and enables the back light leds permanently. 

# Wiring
| Display pin | Conntect to ESP32 pin | 
| --- | :---: |
| RST | 2 |
| CE | 15 |
| DC | 4 |
| DIN | 23 |
| CLK | 18 |
| VCC | 3.3V |
| LIGHT | GND |
| GND | GND |
