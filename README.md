# Microbit Presentation


### Introduction

The Microbit is a microcontroller created by the BBC in a continuing trend to bring younger generations into the world of programming and IOT.  And to that end, I think the makers of the Microbit did a fantastic job:
* The device is fitted with a number of onboard sensors, buttons, leds, and more.
// CB - I think here giving a list of all sensors, buttons, etc, no matter how mundane, would be fun.
* The libraries available for the Microbit's programming are incredibly easy to work with.
// CB - What programming languages can you use? What IDE? I'd present this up front.
* The power consumption is incredibly low compared to a pi or arduino. Two triple A batteries that last a looong time.
// CB - How long? We're nerds and want specifics. :) 
* Numerous programming languages work well with the micro bit, including drage and drop languages for newcomers
// CB- Here's the language bullet. Which ones? I'd throw this as point number ~2 after sensors/buttons.
* A basic kit, complete with micro-to-usb cable and triple A battery pack, is about 17 dollars(with shipping around 25 dollars)

Interested? They can be purchased at the following link https://www.adafruit.com/product/3362.

### Truly Basic Specs

A couple of basic details:  ARM Cortex-M0 32 bit processor, 16KB RAM, nRF51 Application Processor

Full specs available at http://tech.microbit.org/hardware/

### What are the Microbit's IO capabilities?
// CB - Here are all the fun details! When presenting, I'd offer these just as a full slide, very early. No need to hint/lead this information. It should be short and sweet, so we can spend more time with hands-on.

1. Accelerometer
2. Compass, both for direction and detection of magnetic field strength
3. 25 LEDs
4. 2 programmable buttons
5. bluetooth (not compatible with micropython)
6. 2.4 GHZ transceiver for radio
7. 3 GPIO pads, 3v out, and ground connection.  Additionally, one can use the led pins for a total of 19 pins.
8. temperature sensor – meant for the cpu but does an okay job detecting ambient room temp

### What do the libraries offer?
// CB - This section makes sense to me, and probably the top half of the attendees technically. But for libraries, maybe it'd be useful if you spent a slide or two defining what these libraries actually are. I know this sounds boring, but honestly, probably half of the attendees won't know about GitHub, or much about programming in general. Most don't get into these sort of projects because they don't realize that there are many resources readily available, and getting started with this thing is super easy and takes literal minutes. That's the lesson/goal here. Take something that seems obscure/difficult/like a huge technical wall for the attendee, and convince them that they can be doing this project at home in a half hour. And explaining just how exactly they can utilize these open source libraries/tutorials, is the best way to do that.

Everything and the kitchen sink, practically:
1. robotic speech library.  Connect headphones to pins 0 and ground with alligator clips and listen! The sound is fait, a separately powered speaker might be ideal.
2. neopixel library - control arrays of neopixels wth your microbit!  The microbit can power up to 8 neopixels at a time on its own, or all of them if the neopixels are powered separately.
3. Gestures library - because we have an accelerometer on board, the microbit is also able to sense gestures such as shake, up, down, left, right, or fall.
4. LED Library - Easily light up the matrix with the images provided by the library.  You can also input some text that will be displayed in a scroll fashion across the leds (this feature is very handy and is used in runtime error reporting).

### Programming Languages and Editors

There are a number of languages available for the microbit:
* Microsoft Touch
* Microsoft Blocks
* Javascript (Code Kindom)
* Micropython (Mu offline text editor is what I have used, located here https://github.com/mu-editor/mu)

Note: I have used Mu on Raspberry Pi and Windows without issue, Ubuntu was problematic.

More information on available editors at https://www.microbit.co.uk/create-code

### Demonstration Projects

I have create a few projects to demonstrate the capabilities of the microbit.  Links may be found below:

**Basic Examples** - https://github.com/mabiesen/microbit_basic_examples

**In Home Alarm System** - https://github.com/mabiesen/microbit_alarm_system

**My version of the Firefly project** - https://github.com/mabiesen/microbit_pass_the_light

// CB - I like his presentation a lot. I would not add much more. For timing, my recommendation would be to plan your slides and timing so that everything before the "Demonstration Projects" section was a total ~10-15 minutes. I would then plan ~5-10 minutes to go over each of the three demo projects. I would maybe also add that ski/downhill game you had last week, as I think that was a fun and simple little game.

// CB - Note, that these presentations don't need to be as long as Reilly's was last week. Especially for a presentation like this, as I think keeping the total presentation around ~30 minutes would be great, allowing more time for people to get their own hands on, and play with the micro:bit, their own code, etc. The presentation should be a jump off point, where they can then go and spin off.
