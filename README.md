# Flight Delay Causes By Month
Link to the visualization: [Flight Delay Causes By Month](http://bl.ocks.org/jeremy-dai/raw/1bb93535c44e5f23c9f1b18a39bdb91b/)


The flight delay data, which comes from [RITA](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp), contains information on United State flight delays and performance. It comes 

## Delay Causes
- Carrier Delay: delays due to circumstances within the airline's control (e.g. maintenance or crew problems, aircraft cleaning, baggage loading, fueling, etc.).
- Weather Delay: delays due to significant meteorological conditions (actual or forecasted) that, in the judgment of the carrier, delays or prevents the operation of a flight such as tornado, blizzard or hurricane.
- National Aviation System (NAS) Delay: delays due to the national aviation system that refer to a broad set of conditions, such as non-extreme weather conditions, airport operations, heavy traffic volume, and air traffic control.
- Late Aircraft Delay: delays due to a previous flight with same aircraft arriving late and causing the present flight to depart late.
- Security Delay: delays due to evacuation of a terminal or concourse, re-boarding of aircraft because of security breach, inoperative screening equipment and/or long lines in excess of 29 minutes at screening areas.

## Summary
### More delay during summer and winter holidays?
The delay time per delayed flight is higher during summer holidays and winter holidays. The major contributing factors are 
flight delays caused by the airline's control (e.g. maintenance or crew problems) and late previous aircraft. 

Since a tight and unorganized flight schedule can impact airline’s control and previous aircraft arrival, we are 
wondering if the revenue-driven airline industry is trying to move more passengers at the expenses of increasing delays. 

## Design
This design uses a ‘reader-driven’ structure. Reader can explore the data by the years they are interested in.
Also, the animation helps guide the reader through the years.
 
Visual encodings are the mapping of data to display elements.
- Delay time and month are planar variables (position x and y) since they are the most vital variables. 
- Regarding retinal variables, delay cause is shown by different color, which is easy for readers to interpret.

## Resources
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control
http://dimplejs.org/examples_viewer.html?id=area_steps_vertical_stacked
https://stackoverflow.com/questions/28232333/how-to-move-svgs-position-in-d3
https://github.com/schiller/flight-delays-visualization/blob/master/js/app.js
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.axis#fontSize
https://www.w3schools.com/tags/tag_dl.asp
