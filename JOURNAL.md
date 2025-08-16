---
Title: "Yenvo X3"
Author: "Shubham"
Description: "A CoreXY 3D Printer having a large build volume 300x300x400 mm³"
Created_at: "2024-07-28"
Total Time Spent: 64 hours
---

# Yenvo X3

## Overview

| Section          |   Details   |
| ---------------- | ----------- |
| Design Choices   | Decided to go with **CoreXY** over Cartesian / Delta printer for a combination of speed and stability.<br/> Wanted to make a large **400x400x400 mm³** printer but limited to **300x300x400 mm³** due to unavailibity of large heatbeds still enabling printing large parts without joints. <br /> Decided to use **2020 and 2040** Aluminium Extrusions for the sturcture to provide structural rigidity and ease to joints. <br /> Initially thought on using **V-Wheels** for the XY motion, went with **Linear Rails** after learning about the drawbacks of using V-Wheels. <br /> Used **2x Lead Screw Threaded Rods** both joint with one stepper motor each along with **4x Smooth Rods** for the movement of Z-Axis. <br /> For the movement of Hotend assembly along X-axis decided to go with **Linear Rails** too might be an overkill but would provide much precise movement <br /> For the extruder favoured **Bowden Drive Extruder** setup over the Direct Drive to minimize the vibrations and backslash errors on high-speed prints. <br /> As for the hotend, I would most likely be using a **0.4mm Volcano Hotend** to allow fast print times fitting the large build volume. <br /> As for the motherboard I would most likely be using [SKRat V1](https://novo3d.in/bigtreetech-skrat-v1-0/) due to it's pricing and connectors for 2 Z-Axis motors (which I might add in future) or [SKR MINI E3 V3](https://novo3d.in/skr-mini-e3/) which doesn't have separate connections for 2 Z-Axis motors but supports parallel connection with same pricing as SKRat V1 and additional silent features and larger heat sink for better heat management. |
| Challenges Faced | The most problematic issue I faced was **Components Sourcing**, whenever I decided to go with a part either it was unavailable or was for ridiculous high price on the local vendors. And purchasing them overseas although cheaper would end up being higher price due to shippings and customs. <br /> The second problem I faced was dimensions issue since at start I had no idea what the dimensions would each part be, I had to made some changes almost every time I added a new component.|
| References       | I got to learn a lot about CoreXY Printers builds from amazing videos like [TechBuilder's DIY Guide](https://www.youtube.com/watch?v=yuAN5AzEWCg) and [3DJake's DIY Guide](https://www.youtube.com/watch?v=NMfFirtB1D4), apart from these I also watched and read articles few more to learn more. <br /> I also used some 3D models from [GrabCAD](https://grabcad.com/). |
| Learning         | Throughout the whole build I learnt a lot more about Fusion 360, how to use each and every tools. Apart from that I also learned how to design sketches effectively for an easier 3d model. Not only that I also got to know how to manage various instances of same component without creating a link between them. |

## Journal

### Day 1

**Log 1** - Started the day by gathering a brief information on different types of 3D Printers, their advantages, disadvantages and working principle. (CoreXY, Cartesian, Delta, etc.). Initially thought of making a large size printer 400x400x400 mm³ CoreXY printer due to high speeds prints but was restricted to 300x300 mm² beds, so ended up with 300x300x300 mm³ still large height to allow larger builds to made without any joints. Gained a lot of information from various sources especially
[TechBuilder's CoreXY Guide](https://www.youtube.com/watch?v=yuAN5AzEWCg) and [3DJake's CoreXY Guide](https://www.youtube.com/watch?v=NMfFirtB1D4).
Didn't did anything in CAD yet.

**Time Spent** - 8 hours

### Day 2

**Log 1** - Watched some more tutorials, regarding different CoreXY builds, component placements and different parts that can be used for getting the same effect. After some discussion with one of my friends, I decided to go with a 300x300x400 mm³ with the same bed size but still allowing models upto 400mm print without joints.

As for the CAD I started making up the basic structure of the Printer by using just basic cuboids.

<p align="center"><img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/491fca8c-b001-43de-a6fe-4ada7e0a0ae9" /></p>

**Time Spent** - 6 hours

**Log 2** - Redesigned the structure by using 2020 and 2040 Aluminium Profiles.

<p align="center"><img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/2db09694-ed9b-4033-9140-5c7824eddcf0" /></p>

**Time Spent** - 4 hours

### Day 3

**Log 1** - Added the Stepper Motors, Shafts and 400mm Threaded Rods. The threaded rods appreared to be at height higher than the profiles due to starting ~50-60mm above ground surface because of the motor and shaft.
So recreated the structure with more height in the Z Axis. And created some 3D models for the Linear shafts.

<p align="center"><img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/eb41cba4-03f0-452c-a92b-e7a675b11f31" /></p>
<p align="center"><img width="600" height="705" alt="image" src="https://github.com/user-attachments/assets/e3a4aeb9-8778-432d-b22e-7cb9c8dad778" /></p>
<p align="center"><img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/94023340-fec5-4161-9103-5c8c3c8f8613" /></p>

**Time Spent** - 5 hours

**Log 2** - After looking out various Gantries I decided to make my printer unique by using V-Wheels instead of linear rails as I was already using Aluminium Profiles and linear rails were also very expensive.

Added linear Smooth rods and shafts. <br />
Create wheels model and added the wheels, also added the plates for the wheels.
Added 300mm Aluminium Profile which felt short which I would be fixing tommorrow.

<p align="center"><img width="631" height="506" alt="image" src="https://github.com/user-attachments/assets/2d90f682-f82c-46c3-9d5e-af76b71d621d" /></p>
<p align="center"><img width="600" height="725" alt="image" src="https://github.com/user-attachments/assets/19303293-7bdf-4d9d-90a6-ec89e56fa56e" /></p>

**Time spent** - 5 hours

### Day 4

**Log 1** - As the 300mm Aluminium Profile felt short, adjusted it's length and created and added linear rails on side of the Aluminium profile, for the movement of hotend assembly on the X-Axis.
And created L-Joints for the corners.

<p align="center"><img width="487" height="287" alt="image" src="https://github.com/user-attachments/assets/52d03d74-f53e-46d6-a749-93bda82bde37" /></p>
<p align="center"><img width="560" height="664" alt="image" src="https://github.com/user-attachments/assets/2fba6ee7-4b21-43e4-b9b7-ffd7caf0e7ba" /></p>
<p align="center"><img width="463" height="388" alt="image" src="https://github.com/user-attachments/assets/3e9807f8-7c90-49e8-90dd-a14503189a85" /></p>

**Time spent** - 5 hours

**Log 2** - While gathering more information about V-wheels mouting and proper usage, found out many resources recommending not to use V-wheels for XY motions due to their bad performance and wear-tear, which makes sense why no one used V-wheels in the first place, so I eventually decided to go with the linear rails.
Had to recontruct from scratch in a new Document due to the fact components were linked and couldn't resize components at different places.

<p align="center"><img width="1000" height="750" alt="1" src="https://github.com/user-attachments/assets/0b9d7857-ec9e-4f94-92d8-dcd7ba3aa896" /></p>        
<p align="center"><img width="561" height="688" alt="Screenshot 2025-07-31 172029" src="https://github.com/user-attachments/assets/2e888b06-8152-406a-a3ea-9445dab4d621" /></p>

**Time spent** - 4 hours

**Log 3** -
Created 3 models for the pulleys required.
The Pulleys section filled up a lot of confusion inside me, I was to search for Idler Teeth Pulley, but was just searching Teeth Pulley, which I never found. After releasing this I created a model for the Idler teeth pulley as well.

<p align="center">
          <img width="414" height="509" alt="image" src="https://github.com/user-attachments/assets/fd3d0b24-1b5a-4b72-890e-aa0e5893ed0a" />
          <img width="385" height="398" alt="image" src="https://github.com/user-attachments/assets/346471b5-679e-44f1-a4a3-450df8a59843" />
        </p>

<p align="center"><img width="419" height="454" alt="image" src="https://github.com/user-attachments/assets/5661f0d4-8e3e-4765-b374-c4ac93e1de09" /></p>

**Time spent** - 4 hours

**Log 4** - Created and added 3D models for various parts such as pulleys, hotend, hotend cover and some other parts as well.

<p align="center"><img width="492" height="640" alt="image" src="https://github.com/user-attachments/assets/f1514a33-a544-435d-8814-96ee499a9c43" /></p>

**Time spent** - 4 hours

**Log 5** - Added other remaining components like heatbeds, linear bearing, etc.

<p align="center"><img width="461" height="614" alt="image" src="https://github.com/user-attachments/assets/9ad96524-51be-4250-bcf1-eb7d60997a59" /></p>

**Time spent** - 3 hours

### Day 5

**Log 1** - Fixed heatbed and created mounting plates and brackets for motion and extrusion motors respectively.

<p align="center"><img width="718" height="498" alt="image" src="https://github.com/user-attachments/assets/4fae13a6-a9ca-40a7-9eae-55cd9278c49a" /></p>

**Time spent** - 4 hours

### Day 6

**Log 1** - Added missing top joints for threaded rods to mount it to Aluminium profiles.

<p align="center"><img width="1031" height="637" alt="image" src="https://github.com/user-attachments/assets/fc598405-0e91-4d9f-8fd9-8fb67c557ac2" /></p>

**Time spent** - 2 hours

### Day 7

**Log 1** - Fixed gantry by adjusting the levels of pulleys and change pulleys types. The hotend extruder also seemed very odd, so redesigned it again.
The Heatbed support felt a bit wierd when I thought of thier movement, so decided to extend the base to cover the full motion bearings

**Time Spent** - 7 hours

<p align="center"><img width="849" height="551" alt="image" src="https://github.com/user-attachments/assets/cb9a9801-42d4-4d02-a115-09b587cc2979" /></p>
<p align="center"><img width="922" height="475" alt="image" src="https://github.com/user-attachments/assets/be9b51e5-62f3-442c-ad1c-7195854f1f79" /></p>
