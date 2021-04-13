# Original Idea
For my poem I want to visualize what it's like when you are too much in your own thoughts. As a person keeps looping about in their own mind
their thoughts get more and more clouded and sometimes all you need to clear it is for someone there to snap you out of it.

# What I wanted to do

In order to do this I set up a canvas in p5.js where I us perlin noise to create waves. The waves start off slow and steady but as it continues
It rages on and gets more out of control. 
In order to calm it down, a voice needs to be heard which will make it hard reset.
I wanted to use a mic or knock sensor that will sense a person's voice.
The sound will be set to a value and only when the value is high enough does it register in the canvas



# Discoveries/Confusions
I have less expereince working with sound so it's a bit diffucult to figure how the values will work properly.

I haven't gotten it to work yet due to my mic not picking anything up.

With my new knock senor(the plastic one I realized that compared to an actual mic, 
the knock sensor can't pick up actual noises that well due to it relying on vibrations instead of actual sound. and the vibration I would need for my voice requires a vibration that is unfortunatly present in my room, from the hum of my computer to just the birds that can be heard outside.

# How it actually works
I decided due to the options I was presented with, I decided to make a tweak where now it will just be a vibration sound that resets the wave. 
I lose the human aspect of my original concept but I am still able to keep the main focus of it which is that all you need to get you out of your head is some type of outside interference.

this is the code that I figure could work:
Here is concept code for the wave without any audio inputs(it's been updated to cide that works
https://editor.p5js.org/NanaAidoo/sketches/2UGnuCG7J
 
 Arduino code used:
https://create.arduino.cc/editor/nanaaidoo/6c5f5a32-dd71-4935-8218-a0f9c6bd1411/preview

Arduino circuit:
![20210412_222738](https://user-images.githubusercontent.com/54689756/114489099-8b7aea00-9be0-11eb-9f67-19c025fee339.jpg)


# Sources
https://github.com/p5-serial/p5.serialport

https://create.arduino.cc/editor/nanaaidoo/6c5f5a32-dd71-4935-8218-a0f9c6bd1411

https://editor.p5js.org/wmharris/sketches/Ul0jX176S
