# P00: Scott Pagan: Jacob and Logan

**Author(s)**: Jacob Beckman and Logan Owens

**Google Document**: https://docs.google.com/document/d/1hsyco2lYED1d21zSUrluGJs95nO4BOk33x6JR7TQmBE/edit?usp=sharing

---
# Purpose
This product will solve the issue of not waking up due to getting used to an alarm. Very often you will just have one alarm tone and after a long time your brain may get used to hearing it and so it will no longer surprise you or wake you up. This product will instead require more activity to snooze it and thus better waking the user. It will accomlish this by playing a loud noise from speakers that can only be turned off by furiosly shaking the product.

# Initial Design Plan
- The product will have at least one speaker but possibly more. 
- It will use the accelerometer to detect input from the user.
- Possibly a wifi connection, if that is possible.
- Code will include:
  - A function to check if the accelerometer has exceeded a preset threshold to turn off the speakers.
  - A function that determines what time it is based on either information from maybe WiFi or a preset internal clock, possibly a combination of both.
  - A function that plays a tone.
  Revisions:
  - Instead of an accelerometer we are instead using a flip switch to keep track of how many times the device is shaken.
  - We are also using a realtime clock module to manage the time and set alarms.
  - We intend to use the real time clock and flip switch to control the buzzer we will be using for the alarm.
 
 # Images

 ![Top of the Breadboard for Tilt Switch connections](images/picture1.jpg)
 ![Top of the Arduino for Tilt Switch Connection](images/picture2.jpg)
 ![Top of the Arduino for Tilt Switch Connection](images/picture3.jpg)
 ![Top of the Breadboard for Real Time Clock Connections](images/picture6jpg)
 ![Top of the arduino for Real Time Clock Connections](images/picture7.jpg)
 ![Diagram of Real Time Clock Connection](images/deadonrtc-example-circuit_bb.png)
 ![Diagram of Tilt Switch Connection](images/force__flex_tiltarduinolay.gif)
  
# Files
- Images Folder
- License
- README.MD
- example-README.MD
- Jacob_and_Logan Guide to Computer Necromancy Vol. 1.ino (main project file-will be renamed at a later date)

# References
- Arduino IDE 
- Berea College
- SparkFun DS3234 Real-Time Clock Packages - https://learn.sparkfun.com/tutorials/deadon-rtc-breakout-hookup-guide/all
- Arduino IDE Example: Digital Debouncer - https://learn.adafruit.com/tilt-sensor/using-a-tilt-sensor

# Summary

To summarize this experience, this turned out to be a lot more difficult than we originally planned. When we started, we sought to make a device that would help with scheduling. This evolved into wanting to make an alarm. That further evolved into wanting to make an alarm that needed to be shook to be turned off, forcing the user to actually move, increasing the chances that they would wake up and stay up. At first, we were making great strides in getting what we need done for our project to work. Near the end of the project, we got caught up on trying to get the alarm turn off, since we couldn’t get the code to recognize when we were shaking the sensor attached to the Arduino. Then we finally got it to where it would tell when it was being shook, but it refused to keep track of time in the serial monitor. We quickly fixed that and got our project to work as intended.

# Instructions

1. Set your alarm for when you want it to go off.
2. Wait for the Alarm
3. ?????
4. Profit
5. Once the alarm starts going off it will not turn off until the minimum amount of shakes.
6. Shake the tilt switch (viciously) until the minimum number of shakes has been met.

# Errors and Constraints

You have to set the time and date in the code, or else the time is a little off in the serial monitor. The system can slightly be cheesed by holding the Tilt Switch down instead of shaking it. 

# Reflection

When we first started, we had a few different ideas in mind for our project. After we did our journals for the two days, we decided an alarm would be helpful for keeping track of our tasks. At first, we wanted an alarm that you would scream at loudly until the alarm would shut off. This was not only a terrible idea, but it would evolve into our good idea; a clock you would have to shake to get the alarm to shut off.

This moved into us finding the right materials for this assignment. The materials we ended up using were a breadboard, the Arduino Metro, many jumper cables, a broken tilt switch, another broken tilt switch, a 10k ohm resistor, a DeadOn RTC DS3234 clock, and a buzzer. It took us awhile to figure out how we needed to wire everything correctly. Through trial and error (and Jacob almost frying his computer), we were able to get everything working harmoniously.

Once we were able to get the physical set up correct, we finally finished up our code. It took a lot of time and required us to study and understand the Arduino language better than we already did. This was a great learning experience and it was humbling. We were extremely happy once we were able to get everything working correctly. This project was a fun experience that helped both of us learn.

# Final Self-Evaluations

Ideation, Brainstorming, Design:

Partner 1 Logan Owens: 5

Partner 2 Jacob Beckman: 5

Code creation:

Partner 1 Logan Owens: 2

Partner 2 Jacob Beckman: 8

Documentation creation:

Partner 1 Logan Owens: 7

Partner 2 Jacob Beckman: 3

Teamwork & Participation:

Partner 1 Logan Owens: 5

Partner 2 Jacob Beckman: 5
