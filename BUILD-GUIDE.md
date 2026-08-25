*Build Guide*

*Electrical*

To build this you will need:BOM parts,printed model,double sided tape,2 second glue.
first,solder the JST connectors (tp4056 b- , b+ fe/male) then on the 18650 holder cut a part of wire (for mt3608 to pwm regulator)
then solder jst on the reamining wire(- and + fe/male depends on tp4056 type) . Solder jst (fe/male) on tp4056 out+ ,out- and on the mt3608 vin+ , vin- (fe/male depends on tps out)
then get the cable from the 18650 holder and solder it to mts vout+ , vout- 

*Mechanical*

cut the 100x100 copper sheet into 50x50mm (or if you can buy a cut 50X50 sheet),glue it into the hole inside of the fan chamber.
use double sided tape to keep electronics in place inside the electronics compartment.
then,orient the fan so its PWM connector is in immediate proximity to the hole between fan chamber and electronics compartment,so you can route the pwm cable inside the compartment.
screw in the fan,plug in all the jsts.Now you will need to configure settings on the pwm controller.The controller comes with a thermistor and piezo buzzer.
Use these if you like,but thermistor isnt gonna work properly for the temperature based pwm control of the board because you cant put it close to the hotspot.
switch the first switch of the board, (DIP 1) on and connect the fan to FAN1 on the pwm board. This mode outputs 40% PWM which is perfect for the p9 max for:
zero sound,good efficiency,and strong performance.
If you do want higher speeds, connect to FAN2 or FAN3 and turn the dials next to them for higher pwm %.

