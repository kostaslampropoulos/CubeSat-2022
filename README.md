# CubeSat-prototype-for-after-fire-tree-planting

2021 FIRST GLOBAL CHALLENGE: CubeSat Prototype Challenge
Team Name: Team Greece
Mission Name: Mission Dryad

1. MISSION
1.1. Defining the Mission
Due to the latest fires in Greece, both the micro-climate of many areas but also the quality of the soil have changed. Our team was deeply affected by this situation so we decided to create a CubeSat that could partly solve this problem. We suspect that the fires that happened in the summer of 2021 in Greece may have impacted the quality of the atmosphere and the soil of the burnt areas. This CubeSat is said to be able to take measurements of the temperature,the humidity, the altitude as well as the Ultraviolet radiation in the area being examined. 

What’s more, we decided to name our mission “Mission Dryad”. According to Greek mythology, the Dryads were shy spirits that dwelt deep inside forests and were also the ones responsible for their protection from unjustified human actions or wildfires.This is what we want to be: The protectors of nature and wildlife of our Homeland.

1.2. Accomplishing the Mission
When launched, the CubeSat Prototype will immediately start measuring the altitude, temperature, Ultraviolet radiation and various other particles contained in the atmosphere while also keeping track of the exact time and location this data was taken. All this data will be stored into an SD card, but it can also send its exact location and time back to the operator through a transceiver we installed. When the mission is over, we will simply pull it down and retrieve the full data. All this data will be then reviewed by experts to see in which location the atmosphere is suitable for reforestation.


2. DESIGN PROCESS
2.1. Approach
Being given the chance to create a CubeSat made us think of and recognise a problem that jeopardises our country. After brainstorming and doing various meetings we came to the conclusion that the latest fires in Greece have created a new problem; Are the burnt areas ideal enough to be reforested? This is the problem we are hoping to partly solve by creating an innovative CubeSat prototype. Taking into consideration the sensors that FIRST provided us with, we came to choose which of them would be proved useful to our project, as well as which ones we would like to further add. Our team decided to create a CubeSat that consists of a GPS to be able to track the exact position and altitude of our CubeSat, a UV sensor to measure the sun’s radiation in an area, an atmospheric pressure and a humidity sensor to note down such measurements, as well as a thermometer to check if the atmosphere’s temperature is normal. 

2.2. Prototyping
At our research we did not find any CubeSats similar to our idea so we decided to prototype ours. While making a CubeSat from scratch, we undoubtedly faced various difficulties that we got through by working as a team, taking part in the STEM talk provided by FIRST and researching through the internet. After comparing the ideas our team brainstormed, we came to the result that helping nature at this moment would be the best decision to make rather than creating other projects. We had to test our limits and make the most of the knowledge and capabilities our team had, on programming, building and creating the CubeSat.

In the programming and electrical engineering department some of the sensors used were new to us. So with a lot of practice on breadboards we managed to have a working prototype. The enclosure was designed many times and tested in simulations. The final design was selected for its stability, airflow, and endurance to shocks. The material used at first (PLA) was capable of withstanding what the CubeSat would go through so it was our final choice. 

The recovery system was simple. At first we discussed what type of parachute or parasheet we would use. After landing on the 1st option, we calculated the area the parachute needed to be so that it would land at an appropriate speed like the simulation showed the CubeSat could withstand. We concluded that a hexagon would fit best and provide enough drag and would be easy to deploy. 

2.3. Tools and Resources
As a team, for the development of our CubeSat we used multiple programming and CAD softwares, as well as physical tools. More specifically, our microcontroller was programmed using the Arduino IDE platform which uses the C/C++ language and the electronics were at first done on Fritzing. The enclosure of our Cubesat prototype was designed on Fusion 360 and Shapr 3D. The physical tools we used include a 3D 
printer, a caliper, a soldering iron and lead free solder, stainless steel screws and threaded wires. The resources used for making our CubeSat are the Arduino Forum, the FGC’s paperwork, Github as well as Stack Overflow. 
You can see the code of the CubeSat here!


3. FINAL CUBESAT PROTOTYPE DESIGN
3.1. 2021 CubeSat Prototype Kit Components
For the implementation of our experiment a variety of specific sensors were used. Firstly the 2021 CubeSat Prototype Kit provided us with the UV sensor which is using a simple analog connection, MKR ENV Shield Rev 2 for the temperature, atm pressure  and humidity which is connected directly, Real Time Clock module which is using the I2C communication protocol. This concludes the components coming from the 2021 CubeSat prototype kit. 

Each sensor had a data output and was programmed using the Arduino IDE software. All of the data was then stored in the SD card being hosted by the MKR ENV Shield Rev 2. This information was then being categorized by the software so that it would be more readable by the user and scientist analyzing them. 

Lastly, all of the sensor data is transmitted back to our computer, wirelessly and in case the CubeSat gets lost, all of the information collected does not and will be provided to the operator in no time.

3.2. Additional Components
In order to complete our CubeSat and have a complete working satellite, some added components that were not included in the 2021 CubeSat Prototype were used. 

Firstly, for the transmitting of our data, 2 transceivers were used. More specifically the RYLR 896 which uses the LoRa technology was used for it’s long range transmitting capabilities (up to 20 km) and low power consumption. AT commands were used for calibrating the ADDRESS and BAND. The frequency we used is 915 MHz, which is legal for our country. This transmitter is connected to our microcontroller using the UART communication protocol.

Another component used on our CubeSat prototype is a GPS module. This component is useful for knowing the exact coordinates and altitude of our CubeSat. The exact module is the Adafruit GPS breakout board which is connected to the microcontroller using the UART communication protocol.

3.3. Enclosure
The enclosure of our CubeSat is mostly made from 3D printable PLA with 30% infill. Each side is printed separately and then we used M6 screws to be strongly connected together. The top and bottom of the CubeSat are being held with M4 screws. Overall the enclosure was tested in Fusion 360 simulations for stress tests in case of impact and dropped from 7 meters with no visible damage. The electronics are being held by 4 wires which run along the top to the bottom of the CubeSat. The electronics are being held with 4 M4 wires with threads which also help holding the 6 pieces that the CubeSat consists of. The holes are mainly for ventilation and usability for the sensors to have a brief understanding of the environment, but the ones for the screws have special cutouts for the head of the screw to be flash with the body.  


4. LAUNCH
4.1. Technique Used
The circumstances we got to launch our CubeSat under were not ideal, so not everything went as expected. Our primary method was to deploy the CubeSat Prototype into the atmosphere by using a balloon, filled up by a bottle of helium gas. The balloon would be attached to our CubeSat making it go high enough, so that we could take all the measurements needed for our experiment. In order to prevent the loss of the CubeSat, we would attach a parachute for the touchdown.

4.2. Launch Event
Watch the launch of Mission Dryad here!
Watch our team trying out the parachute with different weights here!
Unfortunately, on the day of the launch event, it was really windy, making it impossible for the balloon to go high enough, since it was blown further away. Knowing that these days are breezy in Greece, we decided to provide ourselves with a drone in case not everything goes as planned. Luckily, one of our team’s members was able to bring one to the launch event, which under these circumstances could go higher up in the atmosphere. Therefore, our CubeSat was attached to the drone and driven up to a height of approximately 200 meters, in order to take measurements as accurately as possible. 


5. RESULTS
5.1. Results
Although we faced some difficulties during the launch event that prevented us from deploying the CubeSat as high as we intended, our mission was partly successful. The sensors attached to the CubeSat took many measurements, transmitting all of the data back to our computer wirelessly. After comparing specialists’ data to ours, we concluded that the area where we launched our CubeSat was suitable for reforestation.

5.2. Lessons Learned
We did not manage to get permission to deploy the CubeSat from the Hellenic Military. This prevented us from flying the CubeSat higher than 300 meters. Therefore, we could not take measurements from the altitude we intended to explore. That is the reason why the balloon used for deploying the CubeSat into the atmosphere had a rope attached to it. Unfortunately, due to the wind the balloon could not go as high as expected. In order to complete our mission, we decided to use a drone that could reach a height of approximately 200 meters. We believe that if we had the chance to launch our CubeSat again, after being granted permission, the balloon given would have been useful. We would have reached a higher altitude and approached the eight kilometer distance, where we could take more accurate measurements. 

5.3. FUTURE
Making a cubesat was not only a challenging but also an exciting experience! We had the chance to experiment on our project, and make the most of our skills, or even research to gain more knowledge. As for our future plans, we intend to create a simpler version of our cubesat prototype, so that students can easily recreate it low-cost, with materials that can easily be found. Making some alterations based on the needs somebody might have, would make our cubesat even more accessible to people as they could partly customise it according to their needs. If we had access to a real CubeSat and more financial resources we could also add more advanced sensors; not only to measure the atmosphere but also the soil’s properties too. Additionally, we could also add extra components to prevent wildfires from getting out of control. To conclude, our aim is to prevent wildfires from proliferating, and in case of a fire, we would be able to track whether the area being burnt is good enough to move on to reforestation.

6. REFERENCES
https://www.nasa.gov/sites/default/files/atoms/files/nasa_csli_cubesat_101_508.pdf 
https://csl.noaa.gov/factsheets/csdWildfiresFIREX.pdf
https://forum.arduino.cc

Apart from the links and resources we came across on the internet, we also communicated and elaborated on different subjects in regard to the CubeSat, with other teams from different competitions about micro satellites, like college teams from AUTH and more. 
