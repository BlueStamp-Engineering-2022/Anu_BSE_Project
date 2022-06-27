# Real-Time Planet Tracker
The Real-Time Planet Tracker tracks celestial bodies using Kepler’s algorithms. The RTPT is programmed using Arduino and the celestial bodies are located through a GPS and a motion processing unit, which are shown to the user through the servos and laser pointing at the selected celestial body.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Anu | Saratoga High School | Computer Science | Incoming Junior

![Headstone Image](https://lh3.googleusercontent.com/pw/AM-JKLWOE_bWAj9twGssXxUG27Ftw0bwxgn-iafSzjxQ0Uu52ZZpJRw2lnKLgeU_ImVyBurHE6haYbYiNBKq_NpijfUcmvh5ljUwxhtbIEbumTs58MUYXCXgAETFNA0ui6goKovzMg9ULKHzh6mYEWLOX6z3=w1466-h1464-no?authuser=0)
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone was finishing creating a functioning planet tracker. After completing my first milestone, I implemented the potentiometer, which serves as a switch for the user to pick which planet to track. The potentiometer affected the position of the servo by sharing its value, which corresponded to a certain planet. I also attached a laser pointer to the pan servo to point at the location of the planet chosen on the potentiometer. The laser is connected to the center of the servo, so whenever the pan servo is spun by the tilt servo and rotates, the laser goes along with it. I struggled with completing this milestone mainly because the tilt servo wasn't functioning as it was supposed to. When I first plugged the code in, the servo would continuously spin and would never stop at the position of the chosen planet. The process of testing code on the servo was pretty frustrating. Some tests resulted in the servo speed changing for each planet, or the position not updating after the code is run at the beginning. Now that my basic project is functional, my next steps are to encase all of the components into a wooden box to keep everything in place and organized.

[![Second Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone"){:target="_blank" rel="noopener"}
# First Milestone
  
My first milestone was completing the majority of the hardware portion, which included connecting the pan servo, tilt servo, GPS, and MPU to the arduino and breadboard. The first part was to connect the GPS and MPU, which work together to deliver data to my computer. This was a very grueling process, as there were a number of issues that arose. My arduino mega stopped working after the first couple of days, which meant it had to be replaced, and the initial output of running the code showed that there was an error with the wiring in the GPS. I was able to locate the wiring problem and the coding errors, and after fixing them and going outside to get the most accurate data, the program outputted the necessary data. After this was achieved, I implemented the pan servo and tilt servo, which rotate to point at the position of the default planet in the program, which is Jupiter. My next steps are to implement the potentiometer to allow the user to choose which planet to track. Another step I want to acheive is mounting both servos onto the L bracket and adding the laser pointer to point at the chosen celestial body.


[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574117/video_to_markdown/images/youtube--CaCazFBhYKs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=CaCazFBhYKs "First Milestone"){:target="_blank" rel="noopener"}
# Starter Project
  

My starter project was the Simon Says game. The buttons light up in a certain order and the user has to click the buttons in the order given. This project helped me learn how to solder, as I had to solder all of the components onto the PCB board. It was pretty time consuming and difficult to sodler the microcontroller onto the PCB board because of how many legs there were and how close together.

[![Starter Project](https://i.ytimg.com/vi/hjrZfWrw32Q/sddefault.jpg)](https://www.youtube.com/watch?v=hjrZfWrw32Q&t=1s "Starter Project"){:target="_blank" rel="noopener"}
