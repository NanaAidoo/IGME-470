# What I wanted to do
I wanted to build and expand off of the inital light homework we did, I wanted to make it as interesting as possible despite of my lack of extra controls outside of the sparkfun components  

A switch that when it is flipped, one LED turns on after the other and continusly loops

A button in which when pressed the sequence of the lights turning on changes as it's pressed into a sequence where two lights are turned on at a time and cycle through


Lastly, a potentiometer which controls the rate at which the lights switch

# Discoveries/Confusions
While my project was simple for the most part, one interesting thing I did find out was that you actually have to wait for the previous sequence to finish before the next one can start. This means even if I press the button inbetween the original switch sequence it won't change and if anything I would havve to press the button right after the sequence ends and before it loops.

I can also just hold down the button so that I know that the next sequence will be the button sequence.

The same can be said by letting go of the button mid button sequence. the sequence will finish out before switching.

However, this isn't the case with the potentiometer. That will work mid sequence no matter what is affected

One extra thing I tried to add to my project was code that would cause the lights in the switch sequence to fade out instead of blink but I couldn't seem to get it to work and I was also reminded this was a blink project specifically.

# How it actually works
Outside of having to wait for a sequence to finish out everything worked as planned

Image of circut
![20210301_163748](https://user-images.githubusercontent.com/54689756/109563657-0fa06480-7aae-11eb-87ff-e2986e5c7bc6.jpg)



this is the code that I figure could work:
 https://create.arduino.cc/editor/nanaaidoo/ab65dfe0-62f8-49d1-ace6-7c7723a7c609/preview
 
 video clip of it in action
 https://drive.google.com/file/d/1R-qGXc_6kGSJiVs83NNiHnA-sStlvU_c/view?usp=sharing



# Sources
http://www.arduino.cc/en/Tutorial/Button
https://create.arduino.cc/example/builtin/03.Analog%5CAnalogInput/AnalogInput/preview
