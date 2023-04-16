
# SoloTow
An easy to assemble and inexpensive DIY winch for self towing paragliders.

<img src="https://github.com/brian-greeson/soloTow/raw/main/guide/IMG_1869.jpeg"  width="400" />

### Obligatory Warning
*Paragliding is dangerous. Towing is dangerous. Even when used in accordance with this guide serious injury or death can occur when paragliding. This winch is not designed to be used by inexperienced pilots. No warranty is expressed or implied. Use at your own risk. Please seek professional instruction.*
## Introduction
Do you live in the flatlands? Tired of driving for hours to the nearest tow site, finding an extra vehicle and operator, or spending 5-10 thousand on a pay out winch? The SoloTow is the answer to all your paragliding woes. Every flight with the so This is a simple DIY winch for self towing paragliders. Cheap and portable enough for everyone to build and transport to the nearest suitable field. Construction materials are readily available. Assembly requires no special fabrication skills or tools. Currently some electronic knowledge and skills are required. If there is enough interest from the community I could make some partially assembled kits available that would remove the need for soldering and programming.
## Setting Expectations
What this design is:
- Designed to get an average solo paraglider pilot in the air, high enough to grab a nearby thermal for cross country flying. Expect 200m of altitude in lighter winds, 300m in optimal conditions. Able to be easily transported and setup in most places. 

What this design isn't:
- This is not designed for club or commercial use, i.e. back to back towing all day long with no breaks for system to cool down. Nor to get you mega boosted, 1500m+ into the air. You are welcome to make modification to the design to have it suit your particular needs.
## Major Steps
* Select the configuration and parts for your build
* Order and assemble the mechanical parts
* Solder and assemble the electronics
* Connect the electronics
* Program the controllers and transmitter
* Test basic operation
* Spool the tow line onto the drum
* Field test
* Enjoy!
## Part selection
You have some choices to make when selecting parts for your winch. The most important choice is the motor and battery. These two components will determine the top speed, number of tows per charge, and maximum torque of your winch. These must be considered together. In general the higher the voltage of your system, the higher the maximum speed of the winch (not tension). The higher the "kilowatt" (Kw) of your system, the higher the maximum torque. The higher the amp hour rating (aH) of your battery the more tows per charge you will get. If you decide to use a higher Kw rated motor you must select a battery that can safely supply the extra power, else you may damage the battery and/or start a large lithium fire (not good). Many people get hung up on how many tows per charge. The batteries in the guide have enough energy to get an average pilot 4 tows.
In general I would recommend pilots of average size and lower elevations (1000m and below) build a 4.5Kw / 60 volt system. Pilots at higher elevations and average weight should opt for a 72v system. Those wishing to do more frequent towing may consider a 6Kw / 72 volt system. For reference I am a 80kg pilot flying a moderately fast wing at sea level. I have my 4Kw / 60 volt system and never use full power.
## Purchase links
Prices fluctuate so you may end up paying a little more/less that the prices listed below.
### Motor Bits
An average weight pilot will need a 3KW motor minimum. For example: I'm an 80kg pilot flying a moderately fast glider. I use the 4.5KW motor listed below and it works great. Heavier pilots should consider getting a 6KW or higher motor.
| Quantity | Item/Link| Price| Notes |
|:---:|:---:|:---:|:---:|
| 1 | [Brushless Hub Motor](https://kellycontroller.com/shop/brushless-hub-motor-13in/) | $479.00 | Select the 72 volt and at least the 4.5KW |
| 1 | [Motor Controller](https://kellycontroller.com/shop/kls-n/) | $229 | Select the KLS7230ND | 
| **Total** | | **$708.00** | |
### Battery
Be cautious with purchasing from vendors other than the ones listed here. Battery scams are rampant on aliExpress. I have purchased several batteries from this vendor and RMA'd a bad pack. The customer service was slow but good. If you want more tows per charge you can opt for a pack with a higher amp hour (Ah) rating. Or purchase multiple packs.
| Quantity | Item/Link| Price| Notes |
|:---:|:---:|:---:|:---:|
| 2 | [Battery](https://tinyurl.com/46wfumn2) | $452.80 | 60V 25Ah option |
OR
| 2 | [Battery](https://tinyurl.com/46wfumn2) | $612.00 | 72V 20Ah option |
|**Total**| | **$452.80** OR **$612.00**|

### Frame
The Frame is made of easy to source aluminum extrusion. I highly recommend purchasing the frame parts pre-cut and pre-drilled. The extra cost is negligible and it will save you a lot of time and frustration. 
Parts list Coming soon...

### Remote and Winch Controler
| Quantity | Item/Link| Price| Notes |
|:---:|:---:|:---:|:---:|
| 2 | [Lora Board](https://heltec.org/project/wifi-lora-32-v3/) | $17.90 | |
| 1 | [Potentiometer](https://a.co/d/56w9rYE) | $39.37 | |
| 1 | [Micro Switches](https://a.co/d/2vwkWf8) | $9.99| |
| 1 | [Latching Buttons](https://a.co/d/3Erq4vm) | $11.99 | |
| **Total**||**$97.15**|



### Ancillary Parts
| Quantity | Item/Link| Price| Notes |
|:---:|:---:|:---:|:---:|
| 1 | [Antenna Mast](https://a.co/d/f2BagqU) | $19.48 | You need Line of sight between the transmitter and receiver antenna. Ensure you get a mast tall enough to account for any obstructions at your tow area |
| 1 | [Antennas](https://a.co/d/8XnRbzk) | $13.99 |  |
|1| [Antenna Cable](https://a.co/d/dvxMuS1)| $15.99 | Get one a couple feet longer than your mast height |
| 1 | [Tow Line](https://tinyurl.com/2x9287e6) | $411.45 |  |
| 1 | [Drogue](https://towmeup.com/shop/ols/products/round-drogue-parachute) | $289.00 | One of the more expensive options. Let me know if you find a cheaper source |
|1 | [Fairlead](https://a.co/d/cL6a3BA) | $20.99| |
| 2 | [Wheels](https://a.co/d/hkvo3uy)| $29.99 ||
| 1 | [Winch Controller Box](https://a.co/d/iAHD5yw) | $14.98 | |
| 1 | [Winch Controller Battery](https://a.co/d/eulVu19) | $17.95 | |
| 1 | [Ground Anchors](https://a.co/d/alXvBq3) | $37.98 | |
|**Total**| | **$901.79**| |

### 3D Printed Parts
You can print these yourself using the files in this repository or you can purchase them pre-printed from the links below.
Parts list coming soon...



### Manufactured Parts
The drum flanges and motor brackets need to be cut from aluminum. You can use the files provided in this repository and have a local shop cut them. There are also many online services that can do this for you as well. I have had great work done by Xometry
Parts list coming soon...


| **Grand Total** | **$** | 
|:---:|:---:|

## Assembly
1. Assemble the winch frame.
2. Assemble the drum flange onto the hub motor.
3. Install the motor and controller on the winch frame.
4. Connect motor controller to hub motor and perform motor calibration.
5. Install winch controller on the winch frame and make connections.
6. Assemble the remote transmitter and hand controller.
7. Test the winch.
8. Spool the town line onto the winch.
9. Enjoy flying!
