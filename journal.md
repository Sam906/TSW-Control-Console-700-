---
title: "Train Sim World Control Panel for Class 700"
github: "https://github.com/Sam906/TSW-Control-Console-700-"
description: "This console will be controlled by an arduino Leonardo, and feature components such as push buttons, estops and toggle switches.  I'm a big fan of trains in general and have always liked playing train simulator. However, it did get quite repetitive and boring. So, having a physical console would make the play experience alot more realistic and enjoyable. Unfortunately, due to different layouts and throttle designs ranging from train to train, I can't use this for all of my trains. "
created_at: "2026-10-01"
total_time: "8h"
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

![](https://fabricate.hackclub-assets.com/7565adc26fb886e114e00109b60562e59d942970493d4c9670ace980ec75b2ba/class700%20interior.webp)

Here is my frist sketch of the compoments layout:

![](https://fabricate.hackclub-assets.com/5bd343ab3dbfdd3fb7b76ebd791a6c07e88a24a7ff71e23fca2eab91d3f2f885/20261001_194948.jpg)

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

# October 3, 2026: Modeled up the main case and did some tests!
<!-- fabricate:entry 101 -->

Made some awesome progress today!
I started by doing some research into making screws in fusion 360 for the mounting of the top section to the bottom section of the casing but i couldn't get it to work. So just know I just thought i could use an M3 screw to self tap into a hole in the casing to easily make the screws work. Just found a reddit post saying the hole should be ~2.5-2.7mm so will be doing a test print later - will let you know how it turned out next journal log.

I then moved onto the snapping part of the case. The panel is split in two so I needed to test a way to join them together. I ran two test prints, with different clearances. My first had 1mm of clearance - way too much! See here:
![](https://fabricate.hackclub-assets.com/980b7c5f31d323cd9c570d058ad8f569912f1306aef511d6717042d0e38ba744/20261003_165036.jpg)
And my second had 0.5mm of clearance - perfect!
See here:
![](https://fabricate.hackclub-assets.com/b4d3b5e2546b57f0432bebeee2d63188691320fd8fbec7ea56f079f083494ece/20261003_165046.jpg)
I then moved onto the actual case design - which i time lapsed. Take a look [here]()
During that, I did make some modifications to my original design. I'm no longer using a joystick for the horn as I just couldn't figure out how I'd mount it to my case, so I'm just gonna use a button instead - I have updated BOM.md but NOT updated the google doc picture i had in my last journal, so be mindful of that. In terms of the potentiometer, I'm going to print a sort of frame around it then use super glue to stick it to the case. I've done something very similar before and it worked out amazing! Quick note, the potentiometer I planned to buy SOLD OUT so i'm just gonna use one I have here at home that I was saving for another project but that's ok. It does also reduce the cost! I'll keep it linked in BOM.md
I did also just print a test piece for the handle of the potentiometer, and I need to make it 0.5mm on each side wider and a bit longer by about 4mm. Its really tiny but I will make it bigger for the finished product, this is of course just a test piece! Take a look:
![](https://fabricate.hackclub-assets.com/4e058575902282ab809f770c058c06f5244f6e4f4afb279fc8ce7816edf10759/20261003_165105.jpg)
That's all for now, but I will do some more progress later in the day. I will log that later. I wanted to get this down before I forgot it haha

Timelapse: https://lapse.hackclub.com/timelapse/s7sRHozJ2O6O

**Total time spent: 3h**

# October 4, 2026: Wired it up!
<!-- fabricate:entry 122 -->

So I learnt kicad! It's actually really fun to wire up my components. I time lapsed my session of wiring everything. However, I had to **remove** 3 components as the the Leonardo didn't have enough digital pins, and it got super expensive having these switches! Besides, i'd only use the switches once in my journey when operating a train so it really doesn't matter. I do have to edit the parts list, layout and cad file but that's not an issue. I also spent like 30 mins learning a bunch about screws. i'm going back to that idea for the main casing. I will print some tests of later as im currently printed something. My next journal log will most likely showcasing the finished CAD product. Then after will be the code. But overall, good progress!

Timelapse link : https://lapse.hackclub.com/timelapse/SkCTx7vOoFKG

![](https://fabricate.hackclub-assets.com/e6956bb0475d8faa924755c4c15e3b54cf7859555cb6025cd5fcb7b70ac117d7/Screenshot%202026-10-04%20152759.png)

Timelapse: https://lapse.hackclub.com/timelapse/SkCTx7vOoFKG

**Total time spent: 1h**
