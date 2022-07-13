# Real-Time Planet Tracking System & Trajectory Prediction
The Real-Time Planet Tracker tracks celestial bodies using Kepler’s algorithms. The RTPT is programmed using Arduino and the celestial bodies are located through a GPS and a motion processing unit, which are shown to the user through the servos and laser pointing at the selected celestial body.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Anu | Saratoga High School | Computer Science | Incoming Junior

![Headstone Image](https://lh3.googleusercontent.com/pw/AM-JKLWOE_bWAj9twGssXxUG27Ftw0bwxgn-iafSzjxQ0Uu52ZZpJRw2lnKLgeU_ImVyBurHE6haYbYiNBKq_NpijfUcmvh5ljUwxhtbIEbumTs58MUYXCXgAETFNA0ui6goKovzMg9ULKHzh6mYEWLOX6z3=w1466-h1464-no?authuser=0)
  
# Final Milestone
My final milestone was making the modifications to my basic planet tracker. I attached all of my components to a wooden board and implemented LED lights. The color of the LEDs change as you change which planet you're tracking. Attaching all of the components to the wooden board keeps the entire project in place and organized. I really enjoyed attaching the tilt servo to the wooden board because it taught me how to use a drill. I struggled with implementing the LEDs, especially in the wiring portion. It was difficult to find diagrams on connecting the LEDs, as most of the ideas would cause my arduino to overload from the amount of power the servos and, now, LED required in order to function. After figuring out the wiring, I was easily able to write the code for the LEDs changing. An implementation I would like to add is programming the tracker to track celstial bodies beyond the planets in our solar system.

[![Final Milestone](https://i.ytimg.com/vi/zbGxD67hzGA/maxresdefault.jpg)](https://www.youtube.com/watch?v=zbGxD67hzGA&ab_channel=BlueStampEng "Final Milestone"){:target="_blank" rel="noopener"}
![Circuit Diagram](https://lh3.googleusercontent.com/-p5cQTd7awmsfLWCO1qMMXr8MbqFa-QQoMaFGMNoDnyA_EEMNoEHb7vGGJTGDw7a-2JG7m32_qvmH8DRF5S71qWnc5SWwnWx8NGbtfDTzWCtpSlMX8v1BKOhPRpVdEtalYOHFvQXfCCaDbZ7wzSgXKuobZCkG3O2zReGd0Rcudli5Pp9fR61h_Jqn4971K7UeXD8twArb1HcmSampglwRp3l4ThiSMaeASOu4uQF9VrMksQEl4UIrfLU4kYTGtbV61e8uWRLflvMAeJ377WLxpoyfeRy-frg3fG-mGVuz5M6PMIdm-VuqC_Oyx73B5w9HSUOefFZ7tSA8I2TMvK4n7GbAE_xnSFRT1WlZOtbru3PgGn5xHYRrXGvH9bT8h6EmhcDwX-ppXFEKqv0tvEwTe2nxa4tSJtAcJgDK5b3SutwPXpgLYW07wTDd4Xq0V6PeKp8wqAi-seg0DgxBtlyq-nVfGHEvJytuu4yuWCXd_bCIEc5D6MPcX8bQnDgiZgHvt64zNRxFlCUWxBVvY3AkjxqgjIpES7LMfFeYEbJO16rCff5giiZkTVuW8Y08akmDofuOflGKwXKBD0HBHl3VDSwsdoQ7_KvAztsycKpNhw9H_oA10QBykp9tMiA8auA7e9zBhgfq2RLEC5Bf6sC2i0oJRw2jk1I6qPpphFeR7BQ7gqAk-ht_snVJ0Lx2CqViP65wrCCNZz97A8gNbIEKBlZghqIBBRffQPRr6EKgzXyfeDpNqTk86Zp4LTBovONPkrbR05n33TRNk-9UWMg-O6ByXpSowH4H4mWQSwRJnU7ZQ-WbuUDW48ocpdtTY4MPdOxks3_cp3xHIB5bqkB4-FR8cwA0VbUA8PlUw=w1375-h692-no?authuser=0)

# Second Milestone
My second milestone was finishing creating a functioning planet tracker. After completing my first milestone, I implemented the potentiometer, which serves as a switch for the user to pick which planet to track. The potentiometer affected the position of the servo by sharing its value, which corresponded to a certain planet. I also attached a laser pointer to the pan servo to point at the location of the planet chosen on the potentiometer. The laser is connected to the center of the servo, so whenever the pan servo is spun by the tilt servo and rotates, the laser goes along with it. I struggled with completing this milestone mainly because the tilt servo wasn't functioning as it was supposed to. When I first plugged the code in, the servo would continuously spin and would never stop at the position of the chosen planet. The process of testing code on the servo was pretty frustrating. Some tests resulted in the servo speed changing for each planet, or the position not updating after the code is run at the beginning. Now that my basic project is functional, my next steps are to encase everything in a wooden box to keep all the components organized and in place.

[![Second Milestone](https://i.ytimg.com/vi/vhO4ft5gPMw/maxresdefault.jpg)](https://www.youtube.com/watch?v=vhO4ft5gPMw&ab_channel=BlueStampEng "Second Milestone"){:target="_blank" rel="noopener"}
![Potentiometer Diagram](https://bluestampengineering.com/wp-content/uploads/2022/03/if_noled-1.png)
# First Milestone
  
My first milestone was completing the majority of the hardware portion, which included connecting the pan servo, tilt servo, GPS, and MPU to the arduino and breadboard. The first part was to connect the GPS and MPU, which work together to deliver data to my computer. This was a very grueling process, as there were a number of issues that arose. My arduino mega stopped working after the first couple of days, which meant it had to be replaced, and the initial output of running the code showed that there was an error with the wiring in the GPS. I was able to locate the wiring problem and the coding errors, and after fixing them and going outside to get the most accurate data, the program outputted the necessary data. After this was achieved, I implemented the pan servo and tilt servo, which rotate to point at the position of the default planet in the program, which is Jupiter. My next steps are to implement the potentiometer to allow the user to choose which planet to track. Another step I want to acheive is mounting both servos onto the L bracket and adding the laser pointer to point at the chosen celestial body.


[![First Milestone](https://i.ytimg.com/vi/_fhy38Evc5s/sddefault.jpg)](https://www.youtube.com/watch?v=_fhy38Evc5s&t "First Milestone"){:target="_blank" rel="noopener"}
# Starter Project
  

My starter project was the Simon Says game. The buttons light up in a certain order and the user has to click the buttons in the order given. This project helped me learn how to solder, as I had to solder all of the components onto the PCB board. It was pretty time consuming and difficult to sodler the microcontroller onto the PCB board because of how many legs there were and how close together.

[![Starter Project](https://i.ytimg.com/vi/hjrZfWrw32Q/sddefault.jpg)](https://www.youtube.com/watch?v=hjrZfWrw32Q&t "Starter Project"){:target="_blank" rel="noopener"}
