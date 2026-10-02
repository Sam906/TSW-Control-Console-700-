---
title: "Train Sim World Control Panel for Class 700"
github: "https://github.com/Sam906/TSW-Control-Console-700-"
description: "This console will be controlled by an arduino Leonardo, and feature components such as push buttons, estops and toggle switches.  I'm a big fan of trains in general and have always liked playing train simulator. However, it did get quite repetitive and boring. So, having a physical console would make the play experience alot more realistic and enjoyable. Unfortunately, due to different layouts and throttle designs ranging from train to train, I can't use this for all of my trains. "
created_at: "2026-10-01"
total_time: "4h"
---

# TSW Controll Console (700) #
A physical console for controlling a class 700 in Tran sim world.
Project start date: 01/10/26
Total time: 1 Hour




# October 1, 2026: Getting Started - Initial plan - 1st October 2026
<!-- fabricate:entry 58 -->

In my first session, I sketched out a draft for the layout of the control panel. 
The sketch includes the dimensions of the 3D printed casing, the locations of each component and their functionality. 
So far, I have planned for 17 components, all controlled by an arduino Leonardo. No python code is needed to run on the computer for this to work as i'm intending to use this console as a HID.
To identify what components are needed and their approximate location, I used this attached image online and also had a look in the actual game. 

Attached below is my first design.


## INITIAL IDEAL PARTS LIST & APROX. DIMENSIONS #
I compiled a rough list of all my parts. It's a mix of push buttons, selector knobs and key switches. Most use screw terminals and a few soldering terminals. I've done this before with previous projects so I know what to do. I am also planning to use the same sort of components from previous projects as I am familiar with them and know they are good quality! I have wrote them out here but also attached my IRL workings.

1. 22mm key switch 2 position
2. 22mm selector knob - 3 position
3. sliding potentiometer 
4. 22mm red LED push button momentary reset
5. Dual axis XY KY-O23
6. 40mm Yellow mushroom button
7. 22mm Estop
8. TO BE DETERMINED
9. 22mm 3 position selector knob
10. 22mm 2 position selector knob
11,12,13 all use a 22mm 3 position self reset selector knob
14 and 15 use a red 22mm button self reset
16 and 17 all use a Blue 22mm button

The numbers correspond to the location and name of the component on my first attached sketch. I plan to make a final sketch before submission with more details and exact measurements!
Currently, i'm debating if I should keep number 8 (exterior lights) as I require a 5 position knob and looking on Aliexpress, they look quite bulky and overall not suitable for my needs. 
I plan to source all project parts from aliexpress to keep the project low cost, and I find it to be the best library of parts, unlike something like Amazon. I have already looked on aliexpress so I do have a general idea of what parts i will be using. 


MY NEXT STEPS:
That's all for today but tomorrow I will most likely compile a list of exact parts so I can confirm their dimensions and begin the CAD design in fusion 360. I also need to start setting up my github page! 

The attached timelapse shows me designing my first sketch. Also attached you can find my initial parts list, but i did re-write it here as well. 



![](https://fabricate.hackclub-assets.com/7565adc26fb886e114e00109b60562e59d942970493d4c9670ace980ec75b2ba/class700%20interior.webp)
![](https://fabricate.hackclub-assets.com/5bd343ab3dbfdd3fb7b76ebd791a6c07e88a24a7ff71e23fca2eab91d3f2f885/20261001_194948.jpg)
![](https://fabricate.hackclub-assets.com/c9235ad61238125f58bae710d005ab857df448a20877eeed0d6fcbb552673e45/20261001_203241.jpg)

Timelapse: https://lapse.hackclub.com/timelapse/-fPWmEi31AXu

**Total time spent: 1h**

# October 2, 2026: Gathered list of parts & Began precise Birds eye design
<!-- fabricate:entry 78 -->

I started by compiling a list of all the project parts. I drafted a google doc, then transferred it to my github in BOM.md - Read it [here](https://github.com/Sam906/TSW-Control-Console-700-/blob/main/BOM.md) 
During this mock up in github, I learnt alot about markdown like titles, lists linking images and websites, pretty cool! 
You can check out my google doc as well, attached below.
During my part selection, I learn a bit about how sliding potentiometers work as i will be using one for the throttle. My plan is to split it in two, top half is for acceleration while bottom half is for deceleration. I know its possible as I have done some experimentation before. 
I've also thought about how the 3d printed case will work. I'm planning on having 8 screws total. I will make another diagram going into more detail regarding the case but for now, i've just got positioning of parts as well as sizes (excluding 2). I do plan to make a more detailed one but first, I need to figure out how to make the screws as I've had issues in the past with them, and how I will mount the joystick and potentiometer. I do have some ideas though. So below is the layout of the compioments. I designed it simply in google slides. I plan to make more with different details, including one for the screws and how the 2 sections of the panel snap together as I will have to split it in two. I also made a start on my journal.md - That's all for today.
Check [BOM.md](https://github.com/Sam906/TSW-Control-Console-700-/blob/main/BOM.md) for the aliexpress links!

![](https://fabricate.hackclub-assets.com/af79eb672dc2320a305d8a3e2bdb27bb00ca00bd9ec332235c3543a54fe9460a/tswcontrol%20console%20parts%201.png)
![](https://fabricate.hackclub-assets.com/b21ebd026c2e8dd529a48ce2b89e95b3faa24cce937d8b8def6453e90bdc63a1/Screenshot%202026-10-02%20230748.png)

**Total time spent: 3h**
