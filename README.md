 <p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-ND 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nd.svg?ref=chooser-v1" alt=""></a></p> 

A case for the lily58 with a suspended switchplate. The Lily58 is originally created by [kata0510](https://github.com/kata0510), the case is made to use with the Lily58L created by [BenRoe](https://github.com/BenRoe).

![](https://github.com/SineScire/LilyCase/blob/67452ea44ff2f6d6c83ab36c8d1c95dc17c37ed3/Images/Angle%20view.jpg)

## Parts to assemble the case for one side

| Part | Quantity for one side | Description | Photo |
| ---- | -------- | ----------- | --- |
| Top housing | 1x | 3D Printed |
| Bottom housing | 1x | 3D Printed |
| Switchplate | 1x | 3D Printed |
| IO Brace | 1x | 3D Printed, holds down the USB and TRRS breakout board down in the bottom housing | ![](https://github.com/SineScire/LilyCase/blob/bd04925a0f7e573289788de1d8b8854aa9a3e55a/Images/Brace.jpg) |
| Washers | 5x | 3D Printed, for the screws connecting the switchplate to the PCB | ![](https://github.com/SineScire/LilyCase/blob/bd04925a0f7e573289788de1d8b8854aa9a3e55a/Images/Washer.jpg) |
| m2x5mm Socket Head Screw | 13x | For the Switchplate, Top housing and IO Brace |
| m3x5mm Socket Head Screw | 11x | Connects the Bottom housing to the Top housing |
| m2x4mm Brass Insert | 13x | For the Switchplate, Top housing and Bottom housing |
| m3x5mm Brass Insert | 11x | For the Top housing, to connect with Bottom housing |
| Gasket foam | 3x | In the length of 20mm, 50mm and 70mm, the width of 8mm |
| TRRS plug | 1x | Connects to the PCB |
| TRRS Breakout board | 1x | Mounts to the Bottom housing for IO access | ![](https://github.com/SineScire/LilyCase/blob/bd04925a0f7e573289788de1d8b8854aa9a3e55a/Images/USB-C%20and%20TRRS.jpg) |
| Wire | 4x | Around 10cm of wire to connect the TRRS plug and breakout board |
| Shrinkwrap | 3x | To tidy the cables for the TRRS plug. |
| 90° USB-C Flex Connector | 1x | Connects to the PCB | ![](https://github.com/SineScire/LilyCase/blob/a0095cbd26be3239dec1c03cc9cdd155c50838e4/Images/90degree%20USB-C.jpg)
| USB-C Flex Connector | 1x | Mounts to the Bottom housing for IO access | See TRRS Breakout board |
| Ribbon cable | 1x | Connects the two USB-C Boards |
| Stick on feet | 4x |
| Lily58 PCB | 1x |
| Soldering Iron | 1x | To insert the brass inserts into the case parts |
| Multimeter | 1x | To check the continuity for soldering the TRRS cable |
| Small metal object with a flat surface | 1x | Optional but useful, to align and straighten the brass insert after inserting it |
| Tweezers to hold brass inserts | 1x |

Because the switchplate is able to flex, this case requires two cables to be routed inside from the Lily58 PCB to the bottom housing where the USB-C port and TRRS port will be. This requires making a TRRS cable and ordering parts for a USB-C ribbon cable.

### Assembly

#### Preparing the switchplate
* Parts needed: Switchplate, PCB, 5x m2x4 brass inserts, 5x washers, 5x m2x5mm Socket head screws, dampening foam.
1. Place the switchplate down with the standoffs facing up and place the Lily58 PCB on top as show in the image, the PCB prevents excess deformation of the Switchplate when inserting the brass inserts and ensures a proper fit afterwards.
2. Insert the 5 m2x4mm Brass Inserts into the blue hightlighted openings.
![Switchplate](https://github.com/SineScire/LilyCase/blob/f742c73ddb7eaefbcd8f68132b50881ada31b136/Images/Insert%205x%20m2x4mm%20brass%20inserts%20into%20switchplate.jpg)
3. Using the 5 washers and 5 m2x5mm Socket head screws, the switchplate can be mounted onto the PCB.
4. Apply the dampening foam to the areas highlighted in blue.
![](https://github.com/SineScire/LilyCase/blob/90f54d0df92699f66692af860c6c79015507a384/Images/Dampening%20foam%20spots.jpg)
5. Assemble the PCB/Switchplate with the desired switches and keycaps, resulting in an assembly looking like this.
![](https://github.com/SineScire/LilyCase/blob/9a0e8c2ce669bf5005cfb7baed4aae24dbb11a6b/Images/Assembled%20Switchplate.png)

#### Soldering the TRRS cable and assembling the USB-C Flex cable
* Parts needed: TRRS jack, TRRS breakout board, USB-C 90° flex connector, USB-C flex connector, 4x wire.
1. Assemble the USB-C connector by sliding back the black locking mechanism on the ribbon connector and insert the ribbon cable with the contacts facing away from the PCB, resulting in a cable looking like this.
![](https://github.com/SineScire/LilyCase/blob/3258ab2884d4ba8946a00fd531a2db8299b42a82/Images/USB-C%20Flex%20cable.jpg)
2. Solder the wires to the solder points of the TRRS plug and apply a 90° bend for clearance with the case.
![](https://github.com/SineScire/LilyCase/blob/3258ab2884d4ba8946a00fd531a2db8299b42a82/Images/TRRS%20plug.jpg)
3. Solder the corresponding wires on the TRRS plug to the breakoutboard, keeping note of the ring closest to the tip and to the sleeve.
![](https://github.com/SineScire/LilyCase/blob/3258ab2884d4ba8946a00fd531a2db8299b42a82/Images/Breakout%20board.jpg)
4. Apply some heat-shrink to the end of the TRRS plug, the resulting cable should look something like this.
![](https://github.com/SineScire/LilyCase/blob/3258ab2884d4ba8946a00fd531a2db8299b42a82/Images/TRRS%20Cable.jpg)
5. Plug the 90° USB-C board and the TRRS plug into the PCB before assembling it with the top housing.

#### Preparing the Top housing
* Parts needed: Top housing, 5x m2x4mm brass inserts, 11x m3x5mm Socket head screws, 5x m2x5mm Socket head screws.
1. Place the housing facing down.
2. Insert the 5 m2x4mm brass inserts in the opening shown in the blue highlights in the image below.
![](https://github.com/SineScire/LilyCase/blob/bd04925a0f7e573289788de1d8b8854aa9a3e55a/Images/Insert%205x%20m2x4mm%20brass%20inserts%20into%20top%20housing.jpg)
3. Insert the 11 m3x5mm brass inserts around the outer edge shown in the blue highlights in the image below.
![](https://github.com/SineScire/LilyCase/blob/bd04925a0f7e573289788de1d8b8854aa9a3e55a/Images/Insert%2011x%20m3x5mm%20brass%20inserts%20into%20top%20housing.jpg)
4. If desired, the assembled PCB with switches, keycaps, 90° USB-C connector and TRRS jack can be mounted to the top housing.

#### Preparing the Bottom housing
* Parts needed: Bottom housing, IO Brace, 3x m2x4mm brass inserts, 3x m2x5mm Socket head screws, 4x stick on feet.
1. Insert the 3 m2x4mm brass inserts in the openings show in the blue highlights in the image below.
![](https://github.com/SineScire/LilyCase/blob/c84eab74e7b79bf375c6481fb5333822dabd0113/Images/Insert%203x%20m2x4mm%20brass%20inserts%20into%20bottom%20housing.jpg)
2. Place the top housing with the keyboard facing down above the bottom housing to have the shortest path for the cables to the bottom housing.
3. The TRRS breakout board and USB-C board can be placed in the bottom housing and held down with the brace using 3x m2x5mm socket head screws, note that the thicker part of the brace holds down the USB-C PCB.
![](https://github.com/SineScire/LilyCase/blob/4bcbec4c719c17594ee39ae533747c1e9570fcb9/Images/IO.jpg)
4. The top housing of the case can be placed on the bottom housing, make sure not to put too much tension on the cables. Use the 11x m3x5mm socket head bolts to assemble the case.
