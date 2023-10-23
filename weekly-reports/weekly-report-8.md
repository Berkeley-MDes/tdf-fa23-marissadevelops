# Weekly Report 5: 10/13 - 10/19

## The Remaining Timeline

For this weekly report I will just be covering the action items I went through over the final week of the TDF project, along with some general comments from each day. :-)

### October 12, 2023, Thursday

- Update: the 3d print was not successful, major L, but alas, will try again with different infill settings.
- Will be reprinting only the larger gear box for the sake of time constraints and knowing that we’ll be testing the larger motor anyways.
- Additionally... should’ve added a skirt to the model. Sorry to the first Prusa printer we used.

Skills gained:

✅ 3d-printer Prusa machine

✅ understanding correct print settings based on file

### October 13, 2023, Friday

- 2nd iteration of 3d printed gear box for the MG92B Micro Servo
- had an issue with the skirt of the print impacting the gear teeth, used a dremel to sand it down (too tedious, learned my lesson)
- overall, worked enough for low fidelity testing
- will be redesigning the file to alter where supports need printed

<img width="400" alt="dremel" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/1a977020-1d13-4860-ae87-8c3ded603c53">

### October 14, 2023, Saturday

- Soldered the Featherwing Doubler

<img width="400" alt="learning to solder" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/04ef6fd1-5455-4561-bd64-ec60733ac5a0">
  
- Divya redesigned the CAD file for linear servo actuator, then I reprinted it. Happy to say I feel much more comfortable using the Prusa printers now. :-)
- Initial testing with the (green) distance sensor: very limited range; pivoted to the (black) IR distance sensor, had a range of at least 5'

<img width="491" alt="green IR sensor data output" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/1e57211f-8571-4c33-ae53-f8f09ad8cb5f">

Skills gained:

✅ Learned how to solder a microcontroller (and unsolder... pay attention to which side the pins should face)

### October 16, 2023, Monday

- 3d print was a success!
- Measurements: Gear is 1.5” (full rotation covers 4.71" = 3.14 x 1.5"); pinhead in 4.5” length.
- Attached servo to 3d printed mechanism; had to drill holes where the screws were going to go, there was print support that blocked the entry point.

<img width="400" alt="servo motor with gear" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/eea34383-f6a4-4c8f-8ce5-c378f0e6c24a">

<img width="400" alt="servo motor with gear and actuator" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/efa3a8b3-a7d8-4d1b-a344-335230834de7">

Skills gained:

✅ Learned how to change out drill bits and drill holes in 3d-printed and plywood materials

### October 17, 2023, Tuesday

Since I was the team member who focused on documentation the most, I woke up at about 6 AM to start editing the video in preparation for the final project due date on Thursday. I used Canva; it has decent UI and let me collaborate with my team easily. 

Mechanical:

- Drilled cabinet hinge to board
- Attached 3d printed gear actuator to board; this required more drilling

<img width="400" alt="clamps and drilling" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/0e02328e-61bc-43a2-bdea-190998f2ff35">

Meanwhile, Matthew was working on coding some functions to provide control over when we turn the motor on and off for the wire feeder, as well as determining the range of input from the distance sensor to the movement of the servo gear.

Skills gained:

✅ Video editing in a new software, Canva

✅ Information management across multiple platforms (Google Docs, Shared Google drive, Figma)

✅ More experience in the woodshop navigating drill bits, screws, and cutting scrap wood

### October 18, 2023, Wendesday

Mechanical:

- Screwed cabinet hinge to board
- printed and added 3D printed nozzel to wire feeder; goal was to provide more guidance to the wire as it's being fed out

<img width="400" alt="3d-printed precision nozzel" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/b4a7d874-67a5-4543-82cf-16d56f001e66">

<img width="400" alt="3d-printed precision nozzel" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/ee678b79-a742-4918-9ac7-a52b93674deb">


Testing:

- Angle of plate: decided on screwing in a 1/2" block to raise the hinge of the "arm" a bit more to meet the angle that the wire came out
- Servo strength to lift/lower plate: there were no problems with the linear servo motor providing power to the 3d-printed actuator in lifting the plate

<img width="400" alt="wire feeder, 3d actuator, motor attached to board" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/7fcb3be0-ea68-4797-8dca-88a460654f24">

Knowing that our demo was the next day, we headed up to the lecture hall before leaving to scope out where we'd place our wire feeder.

<img width="400" alt="robotic prototype process" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/ac4c40b8-f01b-405a-91a7-3fe0e9899b19">

### October 19, 2023, Thursday

By Thursday, I was just waiting to add the final prototype and my peers voiceovers to the video. Somebody took our 1/32" wire (with our names on it) that we left in the makerspace, so we improvized and found good copper wire to get the job done! Due to schedule conflicts, I wasn't able to get all of the video components until right before class, but we got it done!

# Reflections

📌 In the last week, I learned how to use a dremel, impact drill, hand saw, and 3d printer. I am super happy with how many skills I got to build while toiling away in the makerspace as our deadline got closer. I feel so much more comfortable in the woodshop now and have a better intuition around which tools can get the job done fastest based on project specs.

# Speculations

📌 At this point I am just ideating on what I'm capable of for the remainder of the class! I am curious in what ways I can utilize more digital outputs (such as the OLED displays) to communicate input/output of the user through kinesthetic emerging technology pieces.

---
**Back to [README.md](../README.md)!**

---
