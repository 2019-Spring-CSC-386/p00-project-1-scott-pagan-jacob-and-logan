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
 
 #Images

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
- Jacob_and_Logan Guide to Computer Necromancy Vol. 1 (main project file-will be renamed at a later date)

# References
- Arduino IDE 
- Stack Overflow
- Berea College
- SparkFun DS3234 Real-Time Clock Packages
- Arduino IDE Example: Digital Debouncer
