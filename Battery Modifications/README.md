# Battery Modifications

The Dji stock battery has a very high energy density of about 175Wh/kg, despite this there are cells even more capable. Therefore some might want to change or ad cells to achieve a longer flight time. Unfortunately Dji set a power limit in their firmware meaning there is almost no point in putting in a high discharge LiPo battery. In addition almost all of the LiPo mods result in the battery being mounted on the outside of the Mavic mini, as the battery compartment is designed to fit round 18650 cells. This isn't to say that it is disadvantageous to strap a pack of cells under your drone, sometimes this preferable as it can get hot inside the drone. If this wasn't already clear, high temperatures ( > 35 Celsius) are damaging to your cells. 


Now, how do you choose a battery cell? Of course that depends on what you want to achieve, mostly in terms of flight time. Not any cell can be chosen, because hovering or flying needs a decent amount of power. These are the required specifications for a Mavic Mini battery:
- <200g
- at least 10A continuous discharge
- internal resistance of <50mOhm
- 2S (2 cells in Series) 
- the number of cells in parallel doesn't matter
- nominal voltage between 3,5V and 3,8V per Cell or 7V and 7,6V for the Pack

There have been tests in which the Mavic Mini was able to lift an additional 180g of ballast, resulting in a total weight of 430g. This would mean that the drone (150g without the battery) could take off with a battery weighing in at 280g. But from my experience everything above 350g total weight isn't really pleasant to fly except when going for range records. The maximum amperage the drone can draw, just flying large circles in sport mode, is 10A. Unsurprisingly the cells replacing the stock ones should be able to supply the same current. While the Mavic Mini's ESC would be able to accept 3S batteries, the BMS is designed for 2S. A 3S battery is possible but a lot more complicated will not be described on this repo. Again for simplicity sake i advise against using LiHV cells and rather choose LiIon chemistry or LiPo batteries.

## Changing the Cells

![alt test](MM_stock_Bat_topview.png?raw=true)
![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)
## BMS Editing 

Dji Battery Killer
