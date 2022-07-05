# Real-Time Planet Tracking System & Trajectory Prediction
The Real-Time Planet Tracker tracks celestial bodies using Kepler’s algorithms. The RTPT is programmed using Arduino and the celestial bodies are located through a GPS and a motion processing unit, which are shown to the user through the servos and laser pointing at the selected celestial body.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Anu | Saratoga High School | Computer Science | Incoming Junior

![Headstone Image](https://lh3.googleusercontent.com/pw/AM-JKLWOE_bWAj9twGssXxUG27Ftw0bwxgn-iafSzjxQ0Uu52ZZpJRw2lnKLgeU_ImVyBurHE6haYbYiNBKq_NpijfUcmvh5ljUwxhtbIEbumTs58MUYXCXgAETFNA0ui6goKovzMg9ULKHzh6mYEWLOX6z3=w1466-h1464-no?authuser=0)
  
# Final Milestone
My final milestone was making the modifications to my basic planet tracker. I attached all of my components to a wooden board and implemented LED lights. The color of the LEDs change as you change which planet you're tracking. Attaching all of the components to the wooden board keeps the entire project in place and organized. I really enjoyed attaching the tilt servo to the wooden board because it taught me how to use a drill. I struggled with implementing the LEDs, especially in the wiring portion. It was difficult to find diagrams on connecting the LEDs, as most of the ideas would cause my arduino to overload from the amount of power the servos and, now, LED required in order to function. After figuring out the wiring, I was easily able to write the code for the LEDs changing. An implementation I would like to add is programming the tracker to track celstial bodies beyond the planets in our solar system.

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}
![Circuit Diagram](https://lh3.googleusercontent.com/BL5eNfxXB6bBOCtKt5-zU2n9D0hwLug_WQ1VxfvgzOcP8RswQz6ziA4_gsmPtbiWah8id6icuvLGha8G0JBGq6UDwtnVRksQ9w2sd5omP45wYKB9PN2U1-DLvz94rr2dVUGTdMyIwlzJC9NxBc3TWO5KDtPKCwH3zdwxoHOK5YSnQ58WWNd9SNdb-gouG1sy7_3fwPd8tTmYEURY6Ccy4jxQgsMEFa8PbIFy_vYvLePaE0_ZhGJotRUaZCmEzwIdn4kmlRFrlFWvrlblldH6xvN2ZQbtokKQ-B9jjs_rs50eMWl6hxVPjeu4ajGT0upTCTTez_qg0LQlDYPWXgjSzIEjIvpjLzm8D16oF8AD_T_ncpzuYzslTrjOLXrQNxxt4aA7XECQI6lUWNinqlJpc85iCUFBs_tlhsOPuXb0hsGUno9fODoq5NOT12Xm6ii6sZGN2ysG5PB-2MTW7zEzVe9iqPiEdvRBZa3T3VSgEGbdZ-2kkpT9bs7euT5kqU5sTKC-_VhRwUpnEJz2ozOoQ0u8gKxIHSslETeaF4iL-koGBYvMsKsr4G-uZjVhCBrJBNVbhTvtobmxPmjVsoe1h0yrUZWZvFRTSHodG2_60XRZjKJ94ePD8MwRC35ztlT3t3IFG9tmiSh5DUELVSHr-siY9BVGXsq_EikZM22w5ytuoMLeSRvvq3taPrHstu6NvIOBK7dGoXOyY6wzctd-kfP_ulmJ1m7ADODvbbpqOAZ2Oda19NP1U84brMTfQ1eDFBJViE4-8OuM0mLacf6Y6_Fvs_zpsGYbtsDdgPogkXt1TsRkLSs7Mn75hH2-TiHoR4-lhLBBE-PfygJpT1ptjMxPX2FQFcSwKq3B7Q=w1375-h692-no?authuser=0)

# Second Milestone
My second milestone was finishing creating a functioning planet tracker. After completing my first milestone, I implemented the potentiometer, which serves as a switch for the user to pick which planet to track. The potentiometer affected the position of the servo by sharing its value, which corresponded to a certain planet. I also attached a laser pointer to the pan servo to point at the location of the planet chosen on the potentiometer. The laser is connected to the center of the servo, so whenever the pan servo is spun by the tilt servo and rotates, the laser goes along with it. I struggled with completing this milestone mainly because the tilt servo wasn't functioning as it was supposed to. When I first plugged the code in, the servo would continuously spin and would never stop at the position of the chosen planet. The process of testing code on the servo was pretty frustrating. Some tests resulted in the servo speed changing for each planet, or the position not updating after the code is run at the beginning. Now that my basic project is functional, my next steps are to encase everything in a wooden box to keep all the components organized and in place.

[![Second Milestone](https://i.ytimg.com/vi/vhO4ft5gPMw/sddefault.jpg)](https://www.youtube.com/watch?v=vhO4ft5gPMw&ab_channel=BlueStampEng "Second Milestone"){:target="_blank" rel="noopener"}
![Potentiometer Diagram](https://bluestampengineering.com/wp-content/uploads/2022/03/if_noled-1.png)
# First Milestone
  
My first milestone was completing the majority of the hardware portion, which included connecting the pan servo, tilt servo, GPS, and MPU to the arduino and breadboard. The first part was to connect the GPS and MPU, which work together to deliver data to my computer. This was a very grueling process, as there were a number of issues that arose. My arduino mega stopped working after the first couple of days, which meant it had to be replaced, and the initial output of running the code showed that there was an error with the wiring in the GPS. I was able to locate the wiring problem and the coding errors, and after fixing them and going outside to get the most accurate data, the program outputted the necessary data. After this was achieved, I implemented the pan servo and tilt servo, which rotate to point at the position of the default planet in the program, which is Jupiter. My next steps are to implement the potentiometer to allow the user to choose which planet to track. Another step I want to acheive is mounting both servos onto the L bracket and adding the laser pointer to point at the chosen celestial body.


[![First Milestone](https://i.ytimg.com/vi/_fhy38Evc5s/sddefault.jpg)](https://www.youtube.com/watch?v=_fhy38Evc5s&t "First Milestone"){:target="_blank" rel="noopener"}
# Starter Project
  

My starter project was the Simon Says game. The buttons light up in a certain order and the user has to click the buttons in the order given. This project helped me learn how to solder, as I had to solder all of the components onto the PCB board. It was pretty time consuming and difficult to sodler the microcontroller onto the PCB board because of how many legs there were and how close together.

[![Starter Project](https://i.ytimg.com/vi/hjrZfWrw32Q/sddefault.jpg)](https://www.youtube.com/watch?v=hjrZfWrw32Q&t "Starter Project"){:target="_blank" rel="noopener"}
