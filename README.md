# IDD-Fa18-Lab1: Blink!

**A lab report by Ananya Paul. Student**

**Fork** this repository to get a template for Lab 1 for *Developing and Designing Interactive Devices* at Cornell Tech, Fall 2019. You should modify this `README.md` file to delete this paragraph and update below. As the lab asks:

> Include your responses to the bold questions on your own fork of the lab activities. Include snippets of code that explain what you did. Deliverables are due next Tuesday. Post your lab reports as `README.md` pages on your GitHub, and post a link to that on your main class hub page.

We've copied the questions from the lab here. Answer them below!

## Part A. Set Up a Breadboard

![Breadboard Initital Setup](./bread_board_setup.jpeg)


## Part B. Manually Blink a LED

**a. What color stripes are on a 100 Ohm resistor?**
The colours on a 100 Ohm resistor are Brown, Black, Brown, Gold.

 
**b. What do you have to do to light your LED?**
To light the LED, press down the button and hold it, when the putton is not pressed, LED turns off. 


## Part C. Blink a LED using Arduino

### 1. Blink the on-board LED

**a. What line(s) of code do you need to change to make the LED blink (like, at all)?**
The line with pinMode and digitalWrite. Replaced all occurences of LED_BUILTIN with the pin number for LED which is 9 in my case.

**b. What line(s) of code do you need to change to change the rate of blinking?**
The delay function controls the rate of the blinking. I changed the value of delay to higher like 1500  for slower blinking and lower like 50 for faster blinking to change the rate of the blinking.

**c. What circuit element would you want to add to protect the board and external LED?**
I would like to add a resistor in the circuit to protect the board and external LED from a short circuit.
 
**d. At what delay can you no longer *perceive* the LED blinking? How can you prove to yourself that it is, in fact, still blinking?**
At delay 11, it can no longer be percieved that the LED is blinking. 
To prove, the LED is on and there is a slight vibration. 
When seen from the corner of an eye, the blinking can be seen when it is blinking. But not when it is just on without any delay.

**e. Modify the code to make your LED blink your way. Save your new blink code to your lab 1 repository, with a link on the README.md.**
[My Blink](./my_blink.ino)

### 2. Blink your LED

**Make a video of your LED blinking, and add it to your lab submission.**

[link to your video here; feel free to upload to youtube and just paste in a link here]


## Part D. Manually fade an LED

**a. Are you able to get the LED to glow the whole turning range of the potentiometer? Why or why not?**


## Part E. Fade an LED using Arduino

**a. What do you have to modify to make the code control the circuit you've built on your breadboard?**

**b. What is analogWrite()? How is that different than digitalWrite()?**


## Part F. FRANKENLIGHT!!!

### 1. Take apart your electronic device, and draw a schematic of what is inside. 

**a. Is there computation in your device? Where is it? What do you think is happening inside the "computer?"**

**b. Are there sensors on your device? How do they work? How is the sensed information conveyed to other portions of the device?**

**c. How is the device powered? Is there any transformation or regulation of the power? How is that done? What voltages are used throughout the system?**

**d. Is information stored in your device? Where? How?**

### 2. Using your schematic, figure out where a good point would be to hijack your device and implant an LED.

**Describe what you did here.**

### 3. Build your light!

**Make a video showing off your Frankenlight.**

**Include any schematics or photos in your lab write-up.**
