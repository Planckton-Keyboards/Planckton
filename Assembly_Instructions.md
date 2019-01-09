# Assembling Planckton

## 1. Preparing the PCB 
![PCB](Images/Assembly/PCB-initial.jpg) 

Once you have printed your PCB, the first thing is to pry out the excess plastic in the switch slots. They are fairly easy to pull out, I used a pair of [flush pliers](https://www.aliexpress.com/item/P00337-Electrical-Wire-Cable-Cutters-Cutting-Side-Snips-Flush-Pliers-Nipper-Hand-Tools-Herramientas/32686834481.html?spm=2114.search0104.3.9.99665f6eQu8w5k&ws_ab_test=searchweb0_0,searchweb201602_5_10065_10068_10130_10547_319_317_10548_10696_10192_10190_453_10084_454_10083_10618_10307_10820_10301_10821_538_10303_537_536_10059_10884_10887_100031_321_322_10103,searchweb201603_2,ppcSwitch_0&algo_expid=9b10be04-4f9c-4a78-b933-385b893fbfa9-1&algo_pvid=9b10be04-4f9c-4a78-b933-385b893fbfa9):

![PCB-Phase1](Images/Assembly/PCB-Phase1.jpg)

Once you've finished, your PCB will look like below: 
![](Images/Assembly/PCB-Phase2.jpg)

Next thing (this is somewhat dependent on your print quality), I suggest with a screw driver go through/poke through each of the holes and ensure they're all clear. You don't want any of your filament to be covering the hole as this will make it harder for your hotswap sockets and switches to go in. 

Once you've cleared the holes, using some sand paper, sand down each of the housings to ensure the excess plastic gets shredded off. This will ensure the switch is nice and flush.

---

## 2. Gluing the Hotswap sockets
Next step is to glue our hotswap sockets. Since the sockets are quite small, getting a glue with a 'precision' end will make this a bit easier. You'll notice that your socket will slot in perfectly like shown below: 

![Hotswaps-Glue-Phase1](Images/Assembly/Hotswaps-Glue-Phase1.jpg)

Once you've figured out how they fit, start gluing!

![Hotswaps-Glue-Phase2](Images/Assembly/Hotswaps-Glue-Phase2.jpg)

> In the current revision there was a slight issue with the far left row lacking a bit of space for the sockets. The fix is to increase spacing by 1/2mm or so, but as a short-term fix, you can clip some of the sockets or just brute force it in.  

> Also note the socket closest to where the power cable will slot in the plastic house. The house was added in revision 2, due to an issue with unplugging the power cable causing the microcontroller micro usb to snap clean off!

Once you're done, your PCB will look like below:

![Hotswaps-Glue-Phase3](Images/Assembly/Hotswaps-Glue-Phase3.jpg)

---

## 3. Soldering the Diodes
The next step is to solder our 48 diodes. For those of you who have little to no soldering experience, [here](https://www.reddit.com/r/MechanicalKeyboards/comments/9h4z6x/how_to_solder_xpost_from_rcoolguides/) is a really simple guide on how to do it.

Setup your soldering work station:
![Solder-station-full](Images/Assembly/3/solder-station-full.jpg)

Start from the bottom right and begin by bending and clipping the diode so it fits nicely:

![row-1-pre-solder-first](Images/Assembly/3/row-1-pre-solder-first.jpg)

> Ensure you have the diode the right way round and that it has a little bit of clearance around the holes

Next, solder the diode:

![row-1-solder-first-2](Images/Assembly/3/row-1-solder-first-2.jpg)

You now want to repeat this pattern, but you want the diodes to create a horizontal chain (for the row):
![row-1-solder-second](Images/Assembly/3/row-1-solder-second.jpg)

> You might find it easier to get some small narrow weight to hold the diode in place whilst you're soldering, or it might move. 

Repeat this until you have completed the first row:

![row-1-solder-complete](Images/Assembly/3/row-1-solder-complete.jpg)

> You should also solder the final socket, like shown in the next image. 

Once you've done the first row, repeat for the next two rows, until you end up with something similar to below:

![row-3-solder-complete](Images/Assembly/3/row-3-solder-complete.jpg)

The final row is by far the trickiest due to the power input. You can bend the first diode like this:

![row-4-pre-solder](Images/Assembly/3/row-4-pre-solder.jpg)

And bend the second one like below:

![row-4-pre-solder-2](Images/Assembly/3/row-4-pre-solder-2.jpg)

Now solder:
![row-4-pre-solder-3](Images/Assembly/3/row-4-pre-solder-3.jpg)

The next diode is also quite tricky, but below is how I did it, along with the next few:

![row-4-solder-around-power](Images/Assembly/3/row-4-solder-around-power.jpg)

Your rev of Planckton will be slightly different to this, but here is the completed top row:

![row-4-solder-central](Images/Assembly/3/row-4-solder-central.jpg)

Once done, it will look something like this:

![completed](Images/Assembly/3/completed.jpg)