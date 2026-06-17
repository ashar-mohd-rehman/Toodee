**title: Toodee**

**author: Ashar**

**description: A diy cartesian style bed slinger 3d printer**

**created at: 2026-06-02**


# June 2: # 1 Research Phase

So my journey exploring 3d printers started when I was 10, delusional me in 4th grade would do anything for an ender 3. This curiousness went on a pause for around 3 years until when I discovered Makerworld and their programme giving free printer sadly being in India I coudn't participate. But this time my interest did not die out as my School newly installed an Ender 3v3 Plus and I even got access to use it as I was disgustingly educated on the topic more than my fellow classmates ofc. Then I discovered HackClub.

From march I've been researching on DIY 3d printers and I had originally planned to start in Blueprint but my exams ended on 16th march and I had to build my hackpad so I couldn't start it their as blueprint ended on 31st march and from 1st April my high-school started. For over a month this project got into a pause as what the heck was the month of april I dont even remember meh

Anyways On the 3D printer so after alot of research and help from people on slack I learnt how 3d printers worked and what components are required to make one .

I originally planned for my printer to have linear rails on all its axis but to save money now I am going to use Linear Rods on all its axiS.

I pitched my project as a T1 multiple times but since Toodee is a bedslinger and doing something unique with a bed slinger is like beating a dead horse with a stick so I am now doing this project as a t2 

To design my own toolhead I read two article on hotends specfically this https://e3d-online.com/blogs/news/anatomy-of-a-hotend?srsltid=AfmBOopv9ZGdgX_PI_wYnak5bT_YGkz35kdcpE4J6TQqU36oKNo6kGPA and this https://www.xometry.com/resources/3d-printing/hotend/ I learned the different parts of a hotend and https://jiga.io/3d-printing/3d-printer-extruder-hot-end-guide/ for learning about the entire print head
![image.png](https://cdn.hackclub.com/019e895c-c379-7955-a840-4986fe9075e1/image.png)

To conclude toodee will use a direct drive system with protoxtruder as extruder and TZ V6 0.2 as the hotend. For part cooling their will be 2x 4010 fans with custom designed ducts. 

The mainboard. I am still exploring options, Earlier I planned to use the BTT SKR e3 v3 mini but due to inflated prices in India I am exploring other options such as BTT Manta Mp4, BTT pico. I think I'll go with pico and pair it with a rpi O 2w to run klipper
![image.png](https://cdn.hackclub.com/019e895d-275d-7c8b-8953-199e38af793c/image.png)

I also watched all DIY 3d printer content on yt to get a understanding of the motion and assembly

The printer will use 2020 extrusions and will somewhat resemble the use of linear rails like the prusa mk4 ![image.png](https://cdn.hackclub.com/019e895a-b1d4-7f87-991a-1f796d5606c6/image.png) 

The Z axis will use Ball Threaded Rods and the X and Y will use GT belts 

Some fellow slack members I would like to thank
1) Charles Braun
2) Anicetus
3) Manan
4) Aethel Veritas

   **Total time spent: 6 hours**

# June 8: # 2 Toodee is now T1 approved!


Ok so yeah I decided to pitch my printer for the last time after some extensive research on how we could achieve a sub 20 benchy. We are going to use Input shaping using an accelerometer to cancel out ringing. 

Also since the last journal I have decided that we will design the toolhead system to be modular so that we can add different toolheads like pen plotter CNC etc .

The mainboard wasnt decided in the last journal and therefore I have decided that we will use Btt Skr Pico anfd pair it with a raspi 2 zero w to run klipper

I am still confused with the extruder as to use either ProtoXtruder 2 or Sherpa mini But I am thinking to go with sherpa maybe?

In fusion360 I applied for student account and got approved dang that was fast and Then I found out about Voron Construct (its a plugin to make designing 3d printers easier in Cad softwares) Installing this plugin into fusion was really hard as their wasnt proper documentation on https://github.com/PrintersForAnts/Voron-Construct but after reading on how to do it on autodesk website and some help from google I got it in 

<img width="1844" height="1524" alt="Screenshot 2026-06-08 232909" src="https://github.com/user-attachments/assets/9515de17-2dc4-4923-9dd4-288a5cc29143" />

also before installing the plugin I tried to design the frame raw and here's the attempt 
<img width="1248" height="1031" alt="Screenshot 2026-05-27 183550" src="https://github.com/user-attachments/assets/0b6520c3-06bc-4d20-bf53-20fee1e78035" />

Toodee will also have a filament runout sensor. When triggered klipper stops the print

**Total time spent: 3 hours**

# June 9 #3 Spent some time learning surface modelling 

I decided to learn surface modelling as it is one of the main tehcniques to make more organic shapes in fusion360 rather than just some blocky stuff. The turotial I used for  was https://www.youtube.com/embed/hIIT2WPEnuk?si=1GRSSYhLiqUDN2MA

All went smooth only problems I encountered were that I miscounted the points needed to project which made my handle loft super weird. I realised this much later and well that didnt end up good anyways I fixed the sketch object and went back to lofting

<img width="1704" height="960" alt="Screenshot 2026-06-09 220219" src="https://github.com/user-attachments/assets/7f26c0e0-2266-4855-8b7b-7b8268741015" />

and i didnt knew why that yellow part was coming because in video his was grey until I flipped it and mine also looked grey and solid <img width="2559" height="1599" alt="Screenshot 2026-06-09 220026" src="https://github.com/user-attachments/assets/1ec42547-d71c-479f-9708-2750909b7444" />

Anyways I also learnt how to render succesfully instead of taking screenshots 
<img width="2561" height="974" alt="Spoon render" src="https://github.com/user-attachments/assets/70da0884-d0da-4091-8854-d7e50dab711a" />

**Total time spent: 1 hours**

# June 17: # 4 Started With Cad

So I started to design the actual printer in CAD and dude I swear this process is gonna take forever CAD is so tedious I wanna cry 
<img width="1170" height="1076" alt="Screenshot 2026-06-17 215740" src="https://github.com/user-attachments/assets/d64335c0-9f26-428c-94f4-df511047d41a" />
Just importing stuff and moving it around was so time consuming it took me over an hour to get the measurements and alignment right

As you can see in the image the z axis will have only 1 Motor and it is going below the printer as later Ill add feets to the printer so it all lines up
I am still not sure about how we will mount the hotend to the 3d printed toolhead which I am figuring it out now

Also  for the hotend , Ill use 2x 4010 fans for part cooling and 1x 3010 fan for heatsink cooling.

speaking of which my fusion crashed multiple times idk why

**Total time spent: 1.5 hours**




