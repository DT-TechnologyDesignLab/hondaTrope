ANTHROPOTROPE LED POV POLE
=============

In Jan 2013 DT and Honda created the HondaTrope for the Sydney Festival - a full colour, volumetric, real time POV display using Teensy3's, FastSPI and 5V LPD8806 RGB LED strips.

We call the whole 'thing' an anthropotrope - basically a cup that you can spin yourself around in to activate the POV from the LED strips.

This repository is here to give something back to those who are interested in making their own POV pole and maybe even taking it to a park and trying it out as we did in testing :) 

There are loads of different ways to create POV poles and each has it's own advantage and dissadvantage. For our application we needed - 

    > Simple, cheap and reliable microcontrollers with low overhead and decent memory for each pole = Teensy3.
    http://www.pjrc.com/store/teensy3.html
    
    > ~1000fps from an RGB LED strips that did not appear to flicker - it just appeared as if it was ON = LPD8806.
    http://www.adafruit.com/products/306
    
    > A good library for writing to the LPD8806 strips from the Teensy3 = FastSPI.
    https://code.google.com/p/fastspi/
    
So once you have all these components you are good to go!

You can use the code on a standard Arduino although it does not have such a good processor or as much memory so you'll have to make shorter LED strips (~32 leds) or make it one colour - and accept that it may flicker a little.

If you have any questions don't hesitate to contact us - we will continue to improve this over the coming weeks.
