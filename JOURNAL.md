# Yenvo X3

---
title: "Yenvo X3"
author: "Shubham"
description: "A CoreXY 3D Printer having a large build volume 300x300x400 mm³"
created_at: "2024-07-28"
---

Total Time Spent - 64 hours

- ### Day 1 (28 July, 2025) ( 7 - 8 hrs )
  - **Research**
    - Gathered a brief information of different types of Printers and their working principle (CoreXY, Cartesian, Delta, etc.)
    - Collected data about parts availiabity for each type of build required on local vendors.
    - Decided to make a big (350-400)³ mm³ CoreXY would need to go with 300³ mm³ build volume, due to unavailabity of big heatbeds.
    - Watch a lot of CoreXY build related videos like [TechBuilder](https://www.youtube.com/watch?v=yuAN5AzEWCg), [3DJake](https://www.youtube.com/watch?v=NMfFirtB1D4), etc.
  - **CAD**
  - **Software**

- ### Day 2 (29 July, 2025) (Journal 1) (6 hrs)
  - **Research**
    - Watched some more tutorials of custom CoreXY builds to learn more about building one.
    - Researched for all the parts needed and available locally.
    - Discussed about it with a friend and decided to go with a 300x300x400 mm³.
  - **CAD**
    - Made a basic structure of the 3D Printer
    <p align="center"><img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/491fca8c-b001-43de-a6fe-4ada7e0a0ae9" /></p>
  - **Software**

- ### Day 2 (29 July, 2025) (Journal 2) (4 hrs)
  - **Research**
    - Calculated the size and quantity of required Aluminium Extrusions.
  - **CAD**
    - Replace the structural blocks with Aluminium 2020 and 2040 Extrusions
    <p align="center"><img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/2db09694-ed9b-4033-9140-5c7824eddcf0" /></p>
  - **Software**

- ### Day 3 (30 July, 2025) (Journal 1) (1 hrs)
  - **Research** 
  - **CAD**
    - Added Stepper Motors, Shafts, Threaded Rods. 
    <p align="center"><img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/eb41cba4-03f0-452c-a92b-e7a675b11f31" /></p>
  - **Software**
 
- ### Day 3 (30 July, 2025) (Journal 2) (4 hrs)
  - **Research**
    - After adding the stepper motor and threaded rod of 400mm, saw some incorrect measurents of the Aluminium profiles so recalculated the lengths of all profiles.
  - **CAD**
    - Updated the Structure to new lengths of Aluminium Profiles.
    <p align="center"><img width="600" height="705" alt="image" src="https://github.com/user-attachments/assets/e3a4aeb9-8778-432d-b22e-7cb9c8dad778" /></p> 
    - Couldn't find any step files for rod support, so created one using the below measurements.
    <p align="center"><img src="https://robu.in/wp-content/uploads/2017/12/SK10-SH10-Dimensions.jpg"></p>
    <p align="center"><img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/94023340-fec5-4161-9103-5c8c3c8f8613" /></p>

- ### Day 3 (30 July, 2025) (Journal 3) (5 hrs)
  - **Research**
    - Read articles and watched different videos on X-Y Plane Movement in CoreXY Printers. Almost every one of them used Linear Rails which were very expensive, so I thought of using V Wheels as I am already using Aluminium Extrusion Profiles.
  - **CAD**
    - Added the previous created rod supports and smooth rods.
    <p align="center"><img width="630" height="723" alt="image" src="https://github.com/user-attachments/assets/3d9aca44-cb8e-4749-bd1a-f2823aa05bc9" /></p>
    - Created a custom wheel for the one available in local store.
    <p align="center"><img width="631" height="506" alt="image" src="https://github.com/user-attachments/assets/2d90f682-f82c-46c3-9d5e-af76b71d621d" /></p>
    - Added wheels, created a part to connect the wheels with moving extrusion in between and yes measurements for XY axis are also messed up.
    <p align="center"><img width="600" height="725" alt="image" src="https://github.com/user-attachments/assets/19303293-7bdf-4d9d-90a6-ec89e56fa56e" /></p>

 - ### Day 4 (31 July, 2025) (Journal 1) (5 hrs)
   - **Research**
     - Gathered info how to properly use Vwheels on CoreXY, only found not to use Vwheels on CoreXY due to terrible performance. Watched some more CoreXY builds and found all using linear rails only, so decided to go with linear rails myself.
   - **CAD**
     - First created a linear rail model of 300mm using a reference model of 100mm
     <p align="center"><img width="487" height="287" alt="image" src="https://github.com/user-attachments/assets/52d03d74-f53e-46d6-a749-93bda82bde37" /></p>
     - Then imported the model in the main structure and place it on the 300mm Aluminium profile.
     <p align="center"><img width="560" height="664" alt="image" src="https://github.com/user-attachments/assets/2fba6ee7-4b21-43e4-b9b7-ffd7caf0e7ba" /></p>
     - Created a 3d model for L joins and placed it on all corners.
     <p align="center"><img width="463" height="388" alt="image" src="https://github.com/user-attachments/assets/3e9807f8-7c90-49e8-90dd-a14503189a85" /></p>

  - ### Day 4 (31 July, 2025) (Journal 2) (4 hrs)
    - **Research**
    - **CAD**
      - Reconstructed whole module from scratch in a new Fusion Document because the old one had all the similar components linked together making me unable to change dimensions of a single component. Instead of copy pasting the whole components, copied only the bodies to get control over each item placed.
      <p align="center"><img width="1000" height="750" alt="1" src="https://github.com/user-attachments/assets/0b9d7857-ec9e-4f94-92d8-dcd7ba3aa896" /></p>   
      - Added XY linear rails
      <p align="center"><img width="561" height="688" alt="Screenshot 2025-07-31 172029" src="https://github.com/user-attachments/assets/2e888b06-8152-406a-a3ea-9445dab4d621" /></p> 

  - ### Day 4 (31 July, 2025) (Journal 3) (4 hrs)
    - **Research**
      - After coming onto Pulleys section I got confused and watched the refernce video about pulley section for more than an hour just to realise I didn't focused on the word Idle Teeth Pulley and searched the whole web for that pulley size.
    - **CAD**
      - Since I didn't found the correct pulley I thought to go with an alternative and made a 3d model for that pulley, an idle pulley.
      <p align="center">
        <img width="414" height="509" alt="image" src="https://github.com/user-attachments/assets/fd3d0b24-1b5a-4b72-890e-aa0e5893ed0a" />
        <img width="385" height="398" alt="image" src="https://github.com/user-attachments/assets/346471b5-679e-44f1-a4a3-450df8a59843" />
      </p> 
      - After finding out I needed a idle tooth pulley made a 3d model for that as well.
      <p align="center"><img width="419" height="454" alt="image" src="https://github.com/user-attachments/assets/5661f0d4-8e3e-4765-b374-c4ac93e1de09" /></p>

  - ### Day 4 (31 July, 2025) (Journal 4) (5 hrs)
    - **CAD**
      - Added pulley, some printable parts, hotend, hotend cover.
      <p align="center"><img width="492" height="640" alt="image" src="https://github.com/user-attachments/assets/f1514a33-a544-435d-8814-96ee499a9c43" /></p> 

  - ### Day 4 (31 July, 2025) (Journal 5) (3 hrs)
    - **CAD**
      - Added remaining components like heatbeds, linear bearings, etc.
      <p align="center"><img width="461" height="614" alt="image" src="https://github.com/user-attachments/assets/9ad96524-51be-4250-bcf1-eb7d60997a59" /></p> 

  - ### Day 5 (1 August, 2025) (Journal 1) (4 hrs)
    - **CAD**
      - Fixed various components like heatbed, added top covers for Z Axis motors.
      <p align="center"><img width="718" height="498" alt="image" src="https://github.com/user-attachments/assets/4fae13a6-a9ca-40a7-9eae-55cd9278c49a" /></p>  

  - ### Day 6 (3 August, 2025) (Journal 1) (2 hrs)
    - **CAD**
      - Added missing top joints for Threaded rods as reminded by a user in Slack.
      <p align="center"><img width="1031" height="637" alt="image" src="https://github.com/user-attachments/assets/fc598405-0e91-4d9f-8fd9-8fb67c557ac2" /></p>

  - ### Day 7 (4 August, 2025) (Journal 1) (7 hrs) (Fix after Review)
    - **CAD**
      - Fixed gantry, pulley levels, fixed hotend extruder cover, added belts and fixed heatbet support.
        <p align="center"><img width="849" height="551" alt="image" src="https://github.com/user-attachments/assets/cb9a9801-42d4-4d02-a115-09b587cc2979" /></p>
        <p align="center"><img width="922" height="475" alt="image" src="https://github.com/user-attachments/assets/be9b51e5-62f3-442c-ad1c-7195854f1f79" /></p>  
   
