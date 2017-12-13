# Final Project - Physical Computing and the Internet of Things

This is a template for your final project documentation.  Please replace <content like this> with your own.  For help with the syntax of Github markdown, visit: [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

*Name:*  Shreya Shankar

*Date:* December 13, 2017

## Project: Theymiscira 

This project is a womens safety wearable device, designed to offer women protection while they are out for a run by themselves. The device works as an armband that mimics an armband one would use to hold a phone or water bottle while out for a run. This device operates in a simple manner, by sending a text message to a pre-registered phone number if a force is detected on the armband. 

### Detailed Project Description

< Explain the "what" of your project:   What is it?   What does it do?   Explain the "why" of your project:  What problem is it responding to?  What issue is it engaging?   

This device operates in a simple manner, by sending a text message to a pre-registered phone number if it detects a force over a certain amount. The force sensitive resistor used while creating this device measures force in terms of resistance; a higher resistance equates to a lower amount of force applied. A resistance measurement of 250 Ohms equates to a force measurement of 100 Newtons, or 22 pounds. For the purpose of the demo, the force that was required for the sensor to send a signal was on the lower side - 200 Ohms. If used in the real world, an average 30-year-old man has a crushing grip strength of 80 pounds for his dominant hand. Therefore, the resistance value required to be measured would be much lower (around 100 Ohms). 

Using this device is simple, a woman simply has to put the armband on before she goes out for a run, and the continue with her regular routine. This device will only act if force is detected. There is no extra effort required on the woman's part, apart from the pre-registration of her "emergency" number. 

The idea for this device came from personal experiences as well as other horrifying stories that have happened to women as they went out for a run themselves. This device is responding to the growing problem of womens safety across the globe, and this device was created to enable women to be able to lead healthy lives while worrying less about their safety (something I believe they shouldn't have to worry about at all). Personally, there have been many times when I have wanted to go out for a run in the dark but have been too scared to do so or have been told by others that it isn't a good idea. Even in Singapore, where the crime rate is incredibly low (less than one percent), I have been told to not go for a run by myself after dark because womens safety is still at risk in a country as safe as Singapore. 

The issue of womens safety is far from resolved and requires a lot more work and education, but until the world is able to get to that point where women no longer fear their safety, devices like these will be necessary to allow women to lead their lives in the same way that men do without any fear. 

### Technical Description

To build this device, I used a Force Sensitive Resistor and connected it to a wearable photon shield. The wearable photon shield was connected to a mini-arduino which was powered by a USB pack. The hardware interacts with the software through IFTTT, which monitors the force variable and only sends a signal if that variable is detected to be over a certain amount. My goal was to make this device as compact as possible, as a clunky device will provide inconveniences if being used while someone is running. To ensure that the device stays intact through the shocks of running, the wires are soldered together and are wrapped with heat-shrink tubing. 

#### Hardware Wiring Diagram

![Wiring Diagram](images/WiringDiagram.png)
< Insert Picture and explanation of Your Wiring Diagram here >

#### Code

< Explain your code.  You might include code snippets, either `inline` or
```c++
//Multiline
bool photon_fun = TRUE;
```
You should link to your full code, either included in the repository (e.g. [my_code.ino](code/my_code.ino)  or to the Shared Revision in your Particle IDE. >


### Design / Form

< Explain the device's form, the aesthetic choices made and how they relate to the concept/function the device is intended to engage >

< include photos of your device >

### Evaluation / Reflection

< What is your own evaluation of your project?   What did you learn through this project?  What would you do differently in the future? >
