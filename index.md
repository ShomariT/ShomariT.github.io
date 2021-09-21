---
layout: default
title: Summer 2021 DREU Project Site
---

* TOC
{:toc}









## About Me

I am currently a senior at the University of Alabama majoring in Computer Science with a minor in Mathematics with an expected graduation date of May 2022.  I am doing research with the Brain-Computer Interface (BCI) robotics disciplinary using devices such as the electroencephalogram.

## About My Mentor

Chris Crawford assistant professor at The University of Alabama works at the intersection of Brain-Computer Interface (BCI), Human-Computer Interaction (HCI), and Robotics. Investigating systems that leverage physiological signals such as electroencephalography (EEG) to enhance Human-Robot Interaction (HRI). He is also researching ways to lower the barriers to entry for novice programmers interested in designing and developing BCI applications.

[About my Mentor](https://htilua.org/about-the-pi)

## About My Project

A collaboration with The University of Alabama to create the ability to use low fidelity prototyping with tools like the electroencephalography (EEG) for educational purposes using external software and hardware like the Arduino. Will use low fidelity prototyping to give an interactive ability and to teach middle and high school students about computer science and how to create prototypes themselves. 

[My Final Report](https://github.com/ShomariT/dreuprojecttemplate/blob/master/files/finalreport1.pdf)

## My Blog

Week 1 : 
The first week of my REU experience was spent talking to Dr. Crawford, brainstorming about ideas on the research project. We talked about the absence of journal with infomation about using prototyping for educational purposes. Brainstormed on how we could potientally use low fidelity so students could have the ability to create mock up prototypes while learning about robotics and computer science. 

Week 2:
The second week of the REU was spent on thinking about potiential mockups of prototypes that we could build for participants could use. I was assigned to create the mockups on paper so that we could review them later in the week. I created roughly 20 ideas of interactive mockups that would possibly grab the attention of the future participant. We narrowed down some of the drawings so we could have a better scope of how we could continue. 

Week 3:
In week 3 Dr. Crawford and I came up with a specific scope to take with design of the prototypes, Dr. Crawford and I discussed the potiental ability to use open source hardware and software with the prototypes. Arduino was the open source tool that we decided to work with. I began to do research on arduino and I was granted access to tutorials to learn how to program and create circuits with the Arduino. 

Week 4: 
In week 4 I was still trying to grab a concept of using the Arduino software. The arduino uses a programming langauge similar to C but with some variables that confused me. This was confusing because I am used to programming in languages like C and C++ but the external variables and syntax that Arduino uses made things more difficult. Also, the Arduino has hardware component which was completely new to me. I had little to no experience in creating circuits to hook up to the arduino. After plenty days of training I was finally able to create a complex circuit with the Arduino. 

Week 5: 
In week 5 of the REU. Dr. Crawford gave me the task to create a complicated circuit with a servo motor and other components like buttons. I began tackling the hardware components to create the circuit. I created the circuit but I stumbled across a problem with powering up the servo motor. This was very frustrating because I felt like I had done everything right. I tested the motor by creating a simple circuit and it worked perfectly fine but when I used it with the complicated circuit, it got little to no power. I did my research on a problem and glanced across multiple potiential solutions and none of them worked. I used a voltmeter to test for shortages or open circuits and never found a problem. After trying countless methods I decided to use another arduino with the servo motor and it worked perfectly. It turns out that the old arduino stopped applying the right amount of current due the overwork on the Arduino uno. 

Week 6:
In week 6 I continued to work on the complicated circuit. At this point I got a design working with a fan. I can make the fan turn clockwise and counter clockwise. I decided to try to control the fan with external components like buttons and sensors. I found a lot of modules on the internet to help me with this design. I used the resources to lead me with some code to implement the extra components. I created my own code but came across some issues with compiling. After lots of hours I found my fault in my code and I was able to use the buttons to make the fan turn clockwise and counter clockwise. 

Week 7:
In week 7, I met with Dr. Crawford and we looked over my progress and began to discuss next steps. Dr. Crawford asked me to create a design that controls the speed of the fan. Also, he wanted the fan to be able to use the wind to make an object float. I did research on the web to look for the components I needed to contril the speed of the fan. I found out that I needed more wires and a new driver to power the fan. We got the supplies ordered and I began constructuing the circuit. I set up the circuit correctly but I could not control the speed of the fan. I was very confused because I had the correct driver with the wires in the correct places. I looked up the schematic for the driver to double check my wiring. I eventually asked my mentor, a electrical engineer for help. After a brief meeting he showed me how to rewire the circuit and everything worked perfectly. The issue that he found was that the schematic for the driver.

Week 8:
In week 8, Dr. Crawford and I met discussed the progress of the research project. I completed the foundation for the project since I am able to create disigns using the arduino. The next steps was to find a way to use a web broswer to communicate with the arduino. For example, we could press a button on webpage and it would make the fan turn on. Dr. Crawford drew a workflow giving me some options to tackle this problem. He suggested to try to narrow down as many communications as possible to make this easier to transition to another device. He wanted me to use a module called johnny five to communicate with the arduino without using the arduino IDE. I was able to understand the module using JavaScript to cut off the arduino IDE. I recreated the previous circuit and successfully turned on the fan without usung the arduino IDE. 

Week 9:
In week 9 , I began to create a webpage to send a input to the arduino to control the fan designed circuit. Creating the webpage was fairly easy but getting the arduino to communicate to the browswer was a difficult task. Since, we are doing communication to the arduino without the original arduino IDE so trying to communicate using external modules can get messy. I needed to use a module called websockets to began the communications from the web and to the ardunio. THe functionalities of websockets was very new to me and I had a rough time figuring out the langauge. For days, I continued to run into the same faults in my code because I did not understand the syntax for websockets while keeping up with the other communications. At the end of the week I scheduled a meeting with Dr. Crawford for assistance.

Week 10:
In week 10, Dr. Crawford and I looked over code and the webpage that I created. We sat down for some time and he was able to implement a new webpage using some old modules he had stored. We made a new server to do the communication for the step. The server was able to grab all of the arduino functionalities. The new webpage was able to communicate to the arduino and control the fan. I added a new light module to the webpage and circuit to see if it could handle extra components. This worked and I showed Dr. Crawford my progress and now he will implement a tool called the EEG to the webpage to control the arduino. He will use this project for educational purposes.

