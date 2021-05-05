# Glasslabs Raspberry Pi LED Controller

## System Diagram
![System Diagram](https://github.com/glassboard-dev/gl-rpi-led-controller-project/blob/develop/assets/led-tunnel-system-diag.png)

## Parts List
* Power Supply : [RSP-1000-27](https://www.digikey.com/en/products/detail/mean-well-usa-inc/RSP-1000-27/7706282)
* Network Switch : [TL-SG108E](https://www.amazon.com/Ethernet-Unmanaged-Shielded-Replacement-TL-SG108E/dp/B00K4DS5KU)
* Raspberry Pi x6 : [Raspberry Pi 4](https://www.digikey.com/en/products/detail/raspberry-pi/RASPBERRY-PI-4B-4GB/10258781)
* LEDs 30/m/3m x48 : [WS2812B](https://www.amazon.com/Aclorol-Individually-Addressable-Programmable-Non-Waterproof/dp/B07BGSZLGX)
* Custom Power & Breakout PCB x6 : [Controller Hardware](https://github.com/glassboard-dev/gl-rpi-led-controller-hardware/tree/2ab05d9f7b06ac152dadaf971d9b6c25116d70ea)
* Target Project Budget : $2,000

## Initial Testing Results
* All White Max Brightness: 30V @ 5.5A = 165W
* Highest Temperature: 85C (LED power supply inductor)
* Voltage ripple @ 165W: ~300mV
* Max system power: 165W * 6 = 990W
