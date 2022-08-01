---
title: LocoRobo Explained In-Depth
author: Shaikh Aryan Bilal
type: post
date: 2017-09-04T06:41:08+00:00
draft: true
url: /?p=10164
footer_parallax:
  - 'false'
footer_source:
  - no-image
footer_color_rgba:
  - 1
banner_parallax:
  - 'false'
banner_source:
  - no-image
enable_noti_bar:
  - -1
banner_color_rgba:
  - 1
header_parallax:
  - 'false'
header_source:
  - no-image
header_color_rgba:
  - 1
page_parallax:
  - 'false'
page_source:
  - no-image
page_color_rgba:
  - 1
body_parallax:
  - 'false'
body_source:
  - no-image
body_color_rgba:
  - 1
background_selector_orientation:
  - full_width_layout
categories:
  - Uncategorized
tags:
  - education
  - locodrone
  - locorobo
  - locowear
  - locoxtreme
  - pramod
  - python

---
&nbsp;  
**LocoRobo?s LocoXtreme &#8211; LocoXtreme Robot**  
[<img loading="lazy" class="aligncenter  wp-image-10165" src="http://backbonecommunications.com/wp-content/uploads/2017/09/LocoRobo-Xtreme.png" alt="LocoRobo Xtreme" width="733" height="598" />][1]  
The first product I?m going to show you is LocoXtreme Robot. This is a tiny little robot that fits in the palm of your hand. Don?t be fooled by the size of the robot, it is power-packed.  
It comes with six different sensors:

<p style="padding-left: 30px;">
  1. Accelerometer<br /> 2. Gyroscope<br /> 3. Magnetometer<br /> 4. Ultra-Sonic Distance Sensor<br /> 5. Temperature Sensor<br /> 6. Motor Encoders
</p>

It has a ring of eight (8) RGB LEDs that come to life when the robot is powered on. It uses four (4) AA batteries so they can be easily managed. It was a buzzer as well. It can play the full octave, in monotone, but it can truly play the full octave. You can introduce some music into the mix. The robot has a bluetooth chip which allows it to connect to any iOS device. Using a little dongle, you can connect to a Chromebook, a Mac, or Windows PC as well. It has a 3-D printed shell which comes in different colors. You can run several classes where you can talk about 3-D design and computer-aided design software applications where you can create different shells for the robot. It comes to life truly when it connects to our coding platform.  
Let?s take a look.  
**LocoRobo Cloud Platform**  
&nbsp;  
[<img loading="lazy" class="aligncenter  wp-image-10150" src="http://backbonecommunications.com/wp-content/uploads/2017/08/LocoRobo-Sample-Coding-Platform.png" alt="LocoRobo Sample Coding Platform" width="569" height="315" />][2]  
LocoRobo?s coding platform is housed on the website app.locorobo.co. When you enter this website, you will see two options; Coding and Academy. When you click on Coding, you?re presented with this interface where you can create a new program. Under the ?Program Name? field, you?ll see that there are a few options in a drop down menu which you will see the true power of the coding platform. You can program the robot using GUI (Graphical User Interface), which is the graphical blocks, C programing, Node.js (JavaScript), Python, and Matlab.  
Let?s start with GUI and name a new program; i.e. getting_started. After clicking ?confirm? we are presented with a blank canvas. The ?plus sign? (+), presents you with a menu of graphical blocks. This is similar to several graphical systems available with a few twists, which in our opinion, make them more suited for robotics and coding education specifically.  
[<img loading="lazy" class="aligncenter  wp-image-10167" src="http://backbonecommunications.com/wp-content/uploads/2017/09/Screen-Shot-2017-09-03-at-10.09.54-PM.png" alt="Screen Shot 2017-09-03 at 10.09.54 PM" width="568" height="347" />][3]  
Let?s add a few blocks: Let?s add a ?drive block?, a ?rotate block?, a ?song block?, a ?note block?, a ?lights block?, and a ?loop block?. We scroll down and click ?done.? As you see here, we have a bunch of blocks that have arranged themselves linearly. This is the beginning, the germinations of computational thinking, which is a collection of steps of instruction that the computer follows inside the robot. Each of these blocks, without going into a lot of detail, because you will have a lot of time to explore these blocks after receiving a demo account. They have the ability to change the direction of motion, for example, from forward to backward. You can rotate clockwise or counterclockwise. The song block offers a few in-built songs in the robot?s memory and you can play them here. The buzzer includes a full octave. You can read sheet music and create any sound, in monotone, and introduce the idea of frequencies through the robot?s programming interface. The robots have RGB LEDs, eight of them. You can select a few, unselected a few and change the colors of the LEDs. Finally we have the loop block which is just a basic computational concept that machines can repeat tasks indefinitely, and computers are really good at that. The way you would use the loop block is simply using the arrow keys to include the next block as part as the loop. You can increase the repetitions, or the loop count, by changing the number of times it?s repeated. This is just the beginning of the graphical user interface and the beginning of the coding experience inside the ecosystem of LocoRobo. One of the coolest things that follows is the idea of code conversion. That is the real power of where this ecosystem lies. When you click on the ?eye? icon, you are able to select Python, C, Node.js, Matlab. As the name suggests, you can convert the graphical blocks into real lines of code. We?re going to click Python, then select the robot name, and click ?convert?. Immediately after, the screen is split in two with the graphical blocks on the left and the real lines of code in Python on the right. This is called code conversion, a very straight forward concept, but very powerful. It becomes powerful when you start seeing something very simple yet intuitive. For example, on the left hand side you?ll see a ?drive block? and it says ?robot, drive forward for 1 second?. On the right hand side you have ?robot.setup_wait(WaitType.TIME, 1000?. 1000 corresponds to milliseconds. I?ve always wanted to keep this a little more technical and a little more rigorous, so we deal with milliseconds as opposed to directly seconds. The code continues ?robot.move(MotorDirection.FORWARD,? etc. Both motor directions, the right and left, should be forward. Both of them move at 100% power which is ?1? and ?1? in the code. When you click the arrow on the left hand side to change from forward to backwards, you will see the code change instantly. Ever option in the graphical blocks gets represented in the code. You will time and again, students would like to know how they are doing in code. The most powerful way to show them is by taking something they already understand, which is the graphical blocks, and show them how it maps into lines of real-world Python code. After you make the desired changes and you?re ready, you click ?play? and the code gets transferred to the robots as instructions and the robots will follow the commands.  
[<img loading="lazy" class="aligncenter  wp-image-10168" src="http://backbonecommunications.com/wp-content/uploads/2017/09/LocoAcademy.png" alt="LocoAcademy" width="584" height="333" />][4]  
The last part of this ecosystem is called the ?content?, which is housed in the ?Academy? section. LocoXtreme Explorer contains Visual Coding and Python Coding, LocoXtreme Voyager contains Python and C/C++ Coding. Once you click on the academy you have access to, it will display the lessons associated. For example, if you clicked on ?Voyager?, you?ll see that there are 52 lessons.  
Let?s click on a lesson. You will see that there is a video, a mission statement, a Materials Needed list, there is a worksheet you can download, there is a Procedure, and Useful Information section. When you click on the worksheet, you?ll see that it?s a PDF document with several technical tasks as well as assignment problems or challenges that helps students gain a better understanding using hands-on exercises and ultimately help them improve their proficiency and knowledge, with the task at hand, about robotics and coding.  
In addition, there is an Instructor Guide section, where you will have access to the answer key to the worksheets among other things.  
Now that you know about the robots that are on the ground, let?s talk about the robots that fly in the air, the LocoDrone.  
**LocoDrone**  
[<img loading="lazy" class="aligncenter  wp-image-10166" src="http://backbonecommunications.com/wp-content/uploads/2017/09/LocoDrone.png" alt="LocoDrone" width="644" height="597" />][5]  
As you see, it?s a reasonably sized drone that is meant for indoor use. It comes with a plastic frame that is protective and it can protect the drone propellers and the motors from several crashes or bumping into several objects inside the classroom. The LocoDrone comes with incredible technology. In fact, in comes with the some of the most advanced drone technology that is available out there. It is controlled using the LocoDrone joystick controller, and packaged with the drone. The joystick has an accelerometer sensor inside so you can control the drone using just gestures. You can program the controller to control the drone using Python. You can introduce a lot of topics in drone science and modern drone technologies in the classroom to bring the drone and the class to life together.  
Now it?s time for the final product, LocoWear  
**LocoWear**  
[<img loading="lazy" class="aligncenter  wp-image-10169" src="http://backbonecommunications.com/wp-content/uploads/2017/09/LocoWear.png" alt="LocoWear" width="625" height="626" />][6]  
This is a programmable wearable device.  
We live in a world with devices such as FitBit and other Smart Watches that allow you to put a piece of technology on your wrist or your hand and measure the activity that you are performing during they day. They take these measurements in infer using mathematical models the status of your health. This kind of movement is called the quantified self, or life logging. These devices are only going to get more ubiquitous as we move forward. It?s important for our students to understand how these devices work and even customize them to their needs and liking. In that spirit, the LocoWear is an excellent platform to bring to the classroom. Using the sensor suite that?s inside LocoWear and the straps, you can put the device on your hand or wrist or arms or shoulders or even your legs. You can code, using Python, not only the software application, but you can also do the physics behind login steps, logging other calorific activities, just like the FitBit. Another cool thing we see in the classroom is the idea of measuring certain aspects of sports. If you put the device on certain parts of the hand, you can measure how well are you shooting to the hoop when it comes to basketball. You can see how well your swing is when it comes to baseball, or tennis, or squash. You can see how well your form is performing or your body is performing when you are doing track activities. It?s also a device that can come up with metrics pertaining to sports activities, measuring those activities using the device, analyzing it using statistics. A lot of our curriculum around LocoWear is coding and statistics and finally optimizing their performance when it comes to sports. We are really excited to see the adoption of this wearable, programmable device starting this year.

<p style="text-align: center;">
  <a class="mk-button outline-btn-lightblue mk-shortcode outline-dimension large" style="font-size: 14px; line-height: 1.5em;" title="Webinar Registration" href="https://events.genndi.com/register/169105139238437242/d26604330f" target="_blank" rel="noopener">Webinar Registration</a>
</p>

 [1]: http://backbonecommunications.com/wp-content/uploads/2017/09/LocoRobo-Xtreme.png
 [2]: http://backbonecommunications.com/wp-content/uploads/2017/08/LocoRobo-Sample-Coding-Platform.png
 [3]: http://backbonecommunications.com/wp-content/uploads/2017/09/Screen-Shot-2017-09-03-at-10.09.54-PM.png
 [4]: http://backbonecommunications.com/wp-content/uploads/2017/09/LocoAcademy.png
 [5]: http://backbonecommunications.com/wp-content/uploads/2017/09/LocoDrone.png
 [6]: http://backbonecommunications.com/wp-content/uploads/2017/09/LocoWear.png