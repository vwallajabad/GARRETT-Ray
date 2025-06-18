GARRETT Ray

This project uses hardware designs and concepts inspired by the CosmicWatch project, originally developed by the Laboratory for Nuclear Science at MIT. CosmicWatch is licensed under the MIT License.
Original project: https://cosmicwatch.lns.mit.edu
License: MIT License

Overview
---
G.A.R.R.E.T.T RAY (Gas-balloon Array for Ray Research: Emission Timing Tracker) is a project for Hack Club's Apex, in which our project, and similar projects from other groups, will be launched on a weather balloon in Boston this summer. In this project, we are planning on launching a sensor on the balloon to detect cosmic rays at different altitude levels. Our tracker will be based on the CosmicWatch project, which uses a scintillator to detect particles. The data will be tracked on an SD card, and, after the flight, we will connect and analyze the data to find the relationship between the frequency of cosmic rays per minute with the altitude of the tracker.

Data
---
The main forms of data we are tracking are as follows:
* Cosmic Ray Frequency
* Altitude
* Time Stamps for Altitude/Cosmic Ray data

With this data, we aim to be able to analyze the relationship between cosmic ray frequency and altitude.

Hardware
---
*CosmicWatch PCB
* Arduino Nano
* SD Card
* Real Time Clock
* Insulated Box
* Batteries
* Power Switch

Journal
---
March - 6/2/2025

During this time frame, our main focus was on getting the project approved and getting our parts ordered. We made our project proposal which can be viewed [here](https://docs.google.com/document/d/1Ost-K2Dkp49aPkbqhb2MIPfQj7q0qgYn6kRJGQYj6K8/edit?usp=sharing), and once the project was approved we began to plan out our design/construction and got our parts ordered. We focused on ordering the PCB and the components that must be soldered to it, as we believed that would be the longest step and we thought we would get enough hours from this to have another one of our teammates hit the 30 hours mark, allowing us to get another $100 grant to put towards more parts.

6/3/2025

Today, Kyle began by updating our readme to better describe the project and be more up-to-date. He then moved on to researching airfare in an attempt to find tickets that fell within the $400 per person stipend. Varun also researched airfare, and he was able to find tickets from an airport a few hours away from us that fit within our budget. Ideally we would be able to fly from our local international airport, but the cost seems prohibitive. 

Later that evening, Kyle and Garrett met up in person to work on soldering components to the PCB, since we chose not to get PCBA for our order to save money. We began working on the SD card PCB with Garrett soldering the components on and Kyle finding each component and getting it out of the bag. We found that it was faster to use soldering paste and a heat gun than it was to use solder and a soldering iron. This approach saved us quite a bit of time and we believe we should be able to get the rest of the boards done relatively quickly.

6/4/2025

Kyle updated the journal and continued to look into travel. The three main approaches he looked at were renting a car, taking a bus, and finding a cheap flight. Turo would allow Garrett to rent a car, but he would be the only one able to drive it since Varun and Kyle are not old enough for Turo's insurance. The Grayhound bus would have been very slow, however it would have been more affordable and was worth keeping around as a last resort. Kyle was also able to find cheap flights through frontier that would fit within our stipend, but these would add a travel day to and from Boston compared to direct flights. Once again, we are keeping these as a last resort option, but direct flights would be preferable. After talking with Varun, he had some luck finding a more direct flight yesterday, but we still need to look further into the trustworthyness of the website he was using.

6/5/2025

On this day Garrett and Kyle worked together to organize and begin assembling the new parts that had finally shipped. After we overcame the learning curve associated with the very small components, we pushed past the SD card PCB that was finished and started working on the main PCB. Starting with the resistors, we used soldering paste and a hot air gun to secure the components, however, that was time-consuming because the soldering paste melted at 600 degrees F. After about 2 hours of working with the numerous resistors on the board, we moved on to the capacitors, diodes, and logic controllers. For these components, we initially used the same soldering paste and hot air but switched to a Pinecil soldering iron and lead solder instead for convenience and speed. After completing the previously mentioned work, Garrett and Kyle realized that one part, U2 was ordered in the incorrect size and that another, U1, was forgotten during the use of the first grant. Seeking to move on with the project, Garrett and Kyle shifted to working on the SIPM PCB and the Arduino Nano. Beginning with the 6-pin connector on the SIPM PCB and moving to the resistors and capacitors, that PCB was finished aside from attaching the SIPM chip and plastic scintillator itself, which was not shipped yet. The 6-pin connector proved to be challenging due to the fact that what shipped in the box was a 4-pin connector, and we had to improvise and use two pins that were not utilized on the Arduino Nano, cutting them off and soldering them in place. Finally, Garrett and Kyle soldered on the pins to the Arduino Nano and plugged it into Garrett's laptop to ensure it was functional. After the successful test of power, we ended our session and further discussed travel plans.

6/6/2025

On June 6th, there was a large amount of progress made toward completing the PCBs and finalizing the soldering aspect of our project. Beginning in the afternoon, Garrett and Kyle started with organizing the larger parts that needed to be added onto the PCB such as the 3.5mm jack, reset button, red LED, BNC connector (which was mistakenly identified by Garrett as an antenna), and 6-pin connector. With how the PCB is sketched, parts overlap and must be assembled in a particular order to ensure a proper fit and connection. Because of this, Garrett and Kyle started with the 3.5mm jack, soldering it onto the board and testing its functionality. After reviewing our previous work, Garrett realized that the hot air gun had partially melted some of the plastic in the microSD card reader, which brought up the question of its ability to be used. Since there wasn't a way to test the SD reader yet as our parts aren't fully assembled, we took note of the potential issue and moved on to the reset button. Attaching the button was simple, and we got through it relatively quickly. The next component was the BNC connector, which was slightly tricky for Garrett to attach due to the large size of the connector, the size of the support structure, and the small soldering pads. After the small frustrations caused by the BNC connector, Garrett and Kyle began attaching the LED and cut off any excess length to preserve the strict weight requirements and any potential for shorts on the PCB, then finished up with the 6-pin connector. The next steps involved attaching the microSD PCB and the Arduino Nano to the main board in that order, so while ensuring the pins remained straight and the board was level, Garrett soldered the microSD PCB on and Kyle did the finishing touches with the Arduino. To end the day, we attached the 4-pin connector for the OLED display and tested the functionality, which resulted in a success and ended the day on a high note.

6/7/2025 - 6/15/2025

Once Garrett received his grant after reaching the 30-hour threshold, he ordered the plastic scintillator, optical gel, SIPM chip, and the U1 and U2 logic controllers. The shipping was much longer than anticipated and led to this large gap in our timeframe, as well as hindered our progress. In this span, Kyle also obtained his grant and placed an order for the styrofoam box that contains the project, Energizer Lithium AA batteries that will supply our project with 9V of power, battery containers to hold the AA cells, screws for the SIPM PCB, standoffs for the SIPM PCB, and a power switch. All of these components arrived on June 16th, which is when we picked back up with our work and raced to get it completed in time. 

6/16/2025

Now that all of the components for our project had arrived, we began the final stretch of assembly and neared the testing stage. Garrett and Kyle started the day off by preparing the plastic scintillator to be polished and added on to the SIPM chip. Unfortunately, when we were ordering the last components for our muon detector, the pre-polished scintillator plastic went out of stock, which only left the cheaper yet much more labor-intensive unpolished version. Using Garrett's drill press and a 1.4mm drill bit, Kyle drilled the holes while trying to minimize heat in the plastic to prevent deformations and cracking. Although the MIT team said in their documentation that they drilled at 60 RPM, that speed wasn't possible or practical for us, so we opted for 2700 RPM and some water drops as coolant. Using a 3D-printed guide, we successfully drilled the holes in the correct spots and moved on to finish the SIPM PCB. Due to the fact that the SIPM chip is heat-sensitive, Garrett had to be careful while soldering it onto the PCB because the angle it needed to be attached was awkward to work with. After a few failed attempts, it was successfully added to the board, and Kyle began drilling the 1/2" holes in the styrofoam box where the project would be mounted on the weather balloon. As soon as the holes were done, Garrett and Kyle worked on attaching U1 and U2, the last two electrical components on the main PCB, and soldering the power switch into the two battery cases using excess 20 AWG wire, and then we had to research the correct way to connect the battery power to the board, since for the MIT project they used USB power instead of batteries. After researching the Arduino Nano pins, we found that we could attach the positive wire to the VIN (Voltage In) pin and the ground wire to the ground connection on the board to supply it with power. The typical 5V pin was unable to be used because the higher voltages from the series batteries would damage the computer, so the other option was the best. Finally, we attached the OLED display to the project and turned on the power which showed us our work so far had been successful.

6/17/2025

Since this was one of the last days available to work on our project, we had a "marathon" session where we essentially finished the project, minus some verifications, testing, and debugging. To start the day, Garrett and Kyle took out the mostly finished assemblies and searched Garrett's garage for sandpaper which we eventually had to make a quick hardware store run for, and then began the long process of polishing the plastic scintillator. This process took nearly half of the total session, and we worked our way from 120 grit to 200 grit, 400 grit, 560 grit, 660 grit, 1000 grit, 1500 grit, 2000 grit, and finally polishing compound. Since the plastic scintillator arrived unpolished and had numerous deep scratches and uneven edges, a large amount of time was taken at lower grits to even out the surfaces and shape the plastic into a rectangular prism that would evenly fit into the project. As soon as Garrett and Kyle took turns sanding the lower grits, they worked on wet sanding from 1000 grit and above to start to smooth the surface and prepare it for polishing. There were concerns that mistakes were made since the plastic was still cloudy after 2000 grit sanding, but after applying polishing compound the plastic turned completely clear. After the polishing was completed, the next process was wrapping the plastic in aluminum foil to prevent outside light from entering and ensuring the detector picks up as many particles as possible. After taping over the PCB with black electrical tape to prevent light from penetrating that surface, Kyle and Garrett, with Varun on a video call, got to work loading code onto the Arduino Nano that would allow it to correctly identify and record data. At this stage, we encountered numerous issues that led to a long troubleshooting session. The muon count on the OLED display showed 1, whereas it should be steadily increasing at about 1 muon/second, and the rate of change was near 0. Since our team doesn't have a high tech setup or a physics lab like the team at MIT did, their use of an oscilloscope to solve issues was impossible for us. This led to all 3 of us reviewing the code on the Arduino, ensuring the correct versions were loaded, researching potential solutions, and changing variables in the code to test. After about 3 hours of frustration, Kyle tried changing the count displayed on the OLED display to an analog count, which maxes out at 1023, and the value shot up from 0 to 1023. This meant that the sensor itself was working, but there was something else creating a problem. By accident, when picking up the project and blocking the plastic scintillator with my hand from the overhead lighting in Garrett's garage, the value changed, which led us to the realization that light particles were entering the scintillator and preventing the accurate detection of muons. To solve this problem, we added more black electrical tape to all sides of the plastic, which led to the detector working as intended. After the tiring session, we attempted to collect data on a microSD card, but failed, which presents our team with June 18ths first topic of focus.

6/18/2025

Starting off in the early morning of June 18th, Garrett updated this journal with detailed information regarding our process of assembly and documented everything that will be used to help Kyle create his short documentary over our efforts. This took just over an hour and a half, and was done to reduce the workload later in the day when stress would be high with the finishing touches being added.











