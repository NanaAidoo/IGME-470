# What I wanted to do
I wanted to create a demo where there are three different types of light sequences going on

A button sequence which is just a simple function where when the button is pressed, the light turns on

A switch that when iy is flipped on, an LED is flashing on and off every three seconds

Lastly, simple function where a random number is called between 0 and 20 and if the number is less than 10, the LED on the arduino turns on

# Discoveries/Confusions
the way I made my circuits initally weren't done properly and only one of my switches work consistently but not fully. However the light functions I made do work so I at least know that all of them work properly.

I found out you need to send power to the other side if the breadboard in order for it to parts to work if you have it on the other side

I also found out that the sparkfun push button actually needs to be wired differently in order for it to work but in order to keep this assignment simple I switched it out for another switch.

The switch also requires power in it's second pin specifically or else it won't work properly 

# How it actually works
One switch when it flips simply turns the light on and off

The oher switch when it's on alternates between the LED and the onboard LED every three seconds

pictures of circuit: https://drive.google.com/drive/folders/1PeDBddsdboHe1y1YFMTf6mT_tNzt4-d4?usp=sharing

this is the code that I figure could work:
 https://create.arduino.cc/editor/nanaaidoo/e5022b56-0d49-4241-81ea-b29d4e99fead/preview

# Sources
http://www.arduino.cc/en/Tutorial/Button
