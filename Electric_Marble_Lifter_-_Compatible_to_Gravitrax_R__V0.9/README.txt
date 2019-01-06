                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


http://www.thingiverse.com/thing:3294111
Electric Marble Lifter - Compatible to Gravitrax (R)  V0.9 by Mike0365 is licensed under the Creative Commons - Attribution license.
http://creativecommons.org/licenses/by/3.0/

# Summary

This is my first try to create a marble lift.  

It uses a spiral drive mechanism to lift up the marbles.
The lift has 2 entries with 2 corresponding exits and 2 marbles can be lifted at the same time. With every rotation of the spiral, it can pick up marbles. 

There is short video showing the basic function:  https://youtu.be/G2JuTBZbeCU

The spiral is a bit a special design, as the profile changes along the way up.
In the bottom the profile is concave, in order to pick up the marble easily. The marble "falls into" the spiral. In the top part, the profile is convex, so the the marble falls out of the spiral. Don't know if this is really necessary but it seemed a reasonable approach to me. I designed the bottom surface angle (overhang) of the spiral to be 40° so that it prints quite nicely in once piece without support material. 


The lift is designed to use a mabuchi 280 DC motor and 2 AA batteries (rechargeable).
It uses a printed worm gear as transmission.

In case the spiral drive gets stuck, the worm gear is intended to swing back in order to avoid destruction.  The motor holder (gl06 - light green in the CAD screenshots) can move on the gear base (gl07 - yellow in CAD screenshots). For normal operation, the motor holder is pulled against the gear base by a pull-spring (indicated in red in the last CAD screenshot).

The worm gear is my own design too. I wanted the worm to be printable upright in one piece without support material, wich does not seem to work out with the standard designs because the overhang angles are too small. So I designed my own worm with more easily printable angles first and then designed the worm wheel to fit nicely.


I have selected a Mabuchi RE-280SA-2865 motor 
(https://product.mabuchi-motor.com/detail.html?id=67)
With 2 rechargeable NiMH batteries (2.4V)  it runs at approx. 5000 rpm without load.
With the worm gear ratio of 1:60 the spiral will turn approx 1 to 1.4 turns per second.
It takes 6 turns of the spiral to get the marble all the way up.
So the total lift time will be 6 to 8.4 seconds, which seems to be fine.
I guess most motors with same dimensions and similar data will work fine.
I have added a picture with the major dimensions of the motor for reference.

The motor (light blue in the CAD screen shots) is fixed into the motor holder (gl06 - green in CAD screenshots) using 2 zip ties, that are not shown in the pictures. 

I will add more assembly instructions, as well of a bill-of-material. You will need some M3 screws, a small pull-spring, and some 3mm round material.

# Print Settings

Printer Brand: Prusa
Printer: i3 MK2S
Rafts: No
Supports: No
Resolution: 0.15
Infill: 20-30%
Filament_brand: noname
Filament_color: see pictures
Filament_material: PLA

Notes: 
When slicing the worm wheal, your slicer might report lots of fixed errors.
Never mind, it will print out perfectly !

I printed the spiral, the worm and the gear with 30% infill. The others with 20%.
I am using standard PLA on a Prusa i3 MK2s and a Prada i3 MK3.