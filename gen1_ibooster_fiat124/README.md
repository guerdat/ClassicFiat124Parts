## About this project 
These files are to manufacture sheetmetal parts to install a gen1 bosch iBooster in a classic Fiat 124.
This design was specifically used to install a 2017 Honda CRV iBooster assembly to a '67 Fiat 124 Sedan.
The dxf files are designed with the proper bending radius and k-values to be manufactured with sendcutsend laser cutting and bending services. Changing the material thickness, bending radi and/or k-values for different bending services will require altering the drawings. The dxf file name ends with the material thickness in mm.

## What is an iBooster: 
An iBooster is an electronic brake booster. Its useful for providing power brakes to cars with a low or unreliable vacuum source. e.g. Turbo, Hybrid, Electric. The iBooster also has CAN bus feartures which, if reverse engineered, can allow software modulation of the brakes and changes to breaking force. Useful for self-driving or auto braking capabilities.

## File Descriptions:    
**Face_plate_spacer_3.2.dxf** — An aluminum spacer necessary between the mounting box and ibooster.       
**Master_cyclinder_brake_fluid_nipple_hold_down_2.03.dxf** — This hold down allows for use of the stock Fiat 124 master cylinder nipples. 
**ibooster_to_fiat_mouting_box_1.88.dxf** — The steel box to adapt the iBooster bolt pattern to the Fiat 124 pedal box bolt pattern. Welding the corners of this box is suggested for maximum strength. 

## Additional importnat info: 
The Honda master cylinder has two circuits with M12x1.0 outlets. Reducers are necessary to use the smaller 3/16 line size that is stock on Fiat 124. A Tee block is also necessary to split the front circuit to feed both wheels. 
The brake pedal on early 124 cars with manual brakes is different than later models. Early brake pedals will need to be replaced with a late model pedal to use the ibooster or fabrication work will need to be done. 

Once installed after the car ignition is turned off the ibooster remains available for ~30 seconds before powering down completely. The iBooster can take ~1 second to activate when the ignition is switched on. 
Various sites offer the bosch iBooster plugs and pins to be able to wire up the power necessary for the unit. At the time of writing [evcreate] (https://www.evcreate.com/wiring-the-ibooster/) has a lot of information and sells a kit with all the necessary plugs and terminals. 

Part numbers for the connectors and pins:
```
- Bosch 026 EuCon Connector: 1 928 405 762; - 763; -764. (Check keying on your device)
- 1.5mm Terminals: 1 928 498 705; 1 928 498 805. (Depending on wire/insulation diameter required)
- 2.8mm Terminals: 1 928 498 806
- 4.8mm Terminals: 1 928 498 807
```
Main pin-outs wire as follows: 
```
- 1 +12v constant
- 2 Pedal sensor
- 8 Pedal sensor
- 9 Ground
- 17 +12v constant
- 20 +12v ignition
- 22 Pedal sensor
- 23 Pedal sensor
```
iBooster Pedal Clevis has M10x1.5 threads that uses an M8 pin 



Please see LICENSE.txt in project root for licensing info. 
