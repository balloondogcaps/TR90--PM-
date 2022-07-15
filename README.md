![Balloondog logo](http://balloondog.nl/wp-content/uploads/2022/07/logo-small-transparent.png)
 
# TR90(-PM) Macropad Build Guide

Hi and welcome to the TR90(-PM) buildguide!
In this build guide, the Acrylic [Imposter case](https://balloondog-store.nl/) is used to demonstrate the process of building the Macropad.

## Parts List

![](https://imgur.com/q4lx4EP.png)

Most of the parts below are included in the kits sold on the official [Balloondog webshop](https://balloondog-store.nl/).
- (1) TR90 or TR90-PM PCB (available [here](https://balloondog-store.nl/)) 
- (1) TR90 Case (available [here](https://balloondog-store.nl/)) 
- (1) Pro Micro or Pro Micro-equivalent controller if you have the TR90-PM PCB
- (8) 6mm Hex Srews
- (4) 15mm Standoffs
- (4) Rubber feet (optional)
- (1) 1.5mm Hex Head Screwdriver
- (9) Cherry MX-style switches 
- (9) Cherry-MX compatible keycaps


## Instructions

### 1). Preparation 
If you use an acrylic case like in this in this build guide please note that:
- Acrylic is very easily scratched
- Acrylic is a hard material that can crack under pressure
- Acrylic is not very fingerprint friendly

We advice to use gloves and build the Macropad on a soft mat. 
In case you use an Acrylic case provided by Balloondog please first remove the safety sheets from the Acrylic plates (on front and back of each acrylic plate). 

### 2). Soldering
If you own a TR90-PM, start by inserting the (short side) Pro Micro headers into the backside of the PCB.

![](https://imgur.com/7FL54sK.png)

Solder the header pins to the PCB on the top side like shown in the image below.

![](https://imgur.com/G1zTz1i.png)

After soldering the header pins start by inserting the switches in the plate and put the PCB on top.
Once all switches are in solder them into place.

![](https://imgur.com/DS45uKa.png)

Place the Pro Micro top down on top of the header pins.

![](https://imgur.com/NO3nbic.png)

** BEFORE SOLDERING THE PRO MICRO MAKE SURE TO FLASH THE PRO MICRO USING THE STEPS BELOW**
Solder the Pro Micro onto the header pins and trim as much as possible from the header pins once done. 


### 3). Flashing the PCB

**Note: The TR90 comes pre-flashed and the  TR90-PM doesn't.**

To start flashing the PCB open up the [QMK Configurator](https://config.qmk.fm/#/balloondogcaps/tr90/LAYOUT) and select the right keyboard. The keyboards start with the prefix "balloondogcaps/" in the configurator. 
After you selected the right keyboard you can go wild with the QMK futures and map the desired layouts below. 

![QMK Configurator](https://imgur.com/cYFeHtc.png)

Once done and happy with the layout press the compile button in the top right corner of the QMK Configurator.
A big potato shows up and QMK starts baking your keyboard firmware. When the QMK Configurator is done with the compiling process the potato disappears and the button to download either the source code or firmware appears. Click the firmware button do download the firmware.

![QMK firmware download](https://imgur.com/DGM7UsM.png)

Once the firmware is downloaded you need to download and open up a tool called the [QMK Toolbox](https://github.com/qmk/qmk_toolbox). When you open the tool, look up your freshly downloaded firmware using the "open" button in the QMK Toolbox. 

![QMK firmware download](https://imgur.com/VTB5iUx.png)

Plug your PCB into your computer and press the reset button found on the backside of the PCB.
A yellow line of text should pop up in the dark QMK Toolbox logger.

![QMK device connected](https://imgur.com/0XFEhGu.png)

When it found the devices, click the flash button in the top right corner and keep an eye on the QMK Toolbox Logger. 
It should give you an acknowledgment that it succeeded flashing the keyboard.

![QMK flash done](https://imgur.com/nYzyE8h.png)

### 4). Putting the case together
The Balloondog acrylic cases come in 7 layers.
- (1) Bottom Layer
- (3) Open Layer
- (1) Plate
- (2) Closed Layer

Take 4 screws and rotate them slightly in a standoff. Take the standoffs with the screws, screwed in, and put them inside the holes of the bottom plate with the logo facing down.

![](https://imgur.com/W8gwxKL.png)

Stack the 3 open layers on top of the bottom layer structure

![](https://imgur.com/0n6PJSC.png)

Stack the plate on top the structure

![](https://imgur.com/eieX7Y3.png)

Finish off by putting the 2 top layers on top of the plate and screwing the case together.

![](https://imgur.com/eieX7Y3.png)

Keep in mind to not screw the case together overly tight because acrylic can crack under to much pressure.

![](https://imgur.com/XZBLFCK.png)

### 5). Playtime!
Now that you build and set up the Macropad its time to enjoy the functional piece of art on your desk!

### 6). Help and support
For firmware issues or questions see the [QMK Documentation](https://docs.qmk.fm/#/) 
For official hardware issues or questions please open up a ticket using the [Balloondog Support System](https://balloondog.atlassian.net/servicedesk/customer/portals)





