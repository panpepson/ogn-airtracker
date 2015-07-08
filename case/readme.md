# LCD 5110 project case

Case designs pro projects with this type of LCD for Nokia 5110 [@eBay](http://www.ebay.com/itm/221475096725):

<img src="../doc/img/lcd5110.jpg" width="200px">


The case is designed in a parametric 3D CAD modeller [OpenSCAD](http://www.openscad.org/)
and printed on a 3D printer from ABS plastics.


## Box variants

### V1 - Flat spacy box with powerbank

* With holder for power bank electronics - see below
* *I don't recommend print it in the current form*, this was the first prototype,
  there should be some corrections, mainly GPS holder takes needlessly too space,
  it's impossible to plug some micro USB

<img src="../doc/img/case-v1.png" width="200px">


### V2 - Flat small box with or without powerbank

* Smaller than variant 1, corrected problems
* Includes subvarinats with and without holder for power bank electronics
* *I've never tested this design*, probably the STM32 board holder would require some adjusting
* Probably too little space inside for my style of wiring

#### V2-A - with holder for power bank electronics

* set `with_battery = true`

<img src="../doc/img/case-v2.png" width="200px">


#### V2-B tiny, without holder for power bank electronics

* set `with_battery = false`
* meant to be powered from external supply directly to STM32 micro USB port

<img src="../doc/img/case-v2b-f.png" width="200px">
<img src="../doc/img/case-v2b-b.png" width="200px">


### Prism long box with powerbank

* With holder for power bank electronics - see below

<img src="../doc/img/case-v3.png" width="200px">


### Prism short box

* With holder separate battery charger board
* *favourite design, but not tested yet*


## Adjustments

The case size can be easily adjusted editing values in `dimensions.scad` file (`box_i_x`,
`box_i_y`, `box_i_z` define inner dimnesions).


## Power bank electronics alternative

As an alternative to the separate battery charger and holder one case use electronics from
power bank [@eBay](http://www.ebay.com/itm/231432999482) and print the *case variants
with printed holders for battery and electronics*.

Advantages:
* Components a little bit cheaper suprisingly (but longer case costs something too)
* By 2 joints less soldering :-)
* Device can be used as an emergency 5V USB power source (in case other sources around are drained)

Disadvantages:
* To protect battery from undervoltage, the CPU and other stuff should be connected to the 5V bank's output, so it engages one other switching regulator (adding some RF noise around)
* Longer case (more money, longer time to print)

