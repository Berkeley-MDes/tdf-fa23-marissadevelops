# Weekly Report 7: 10/6 - 10/12

## Thursday Lecture Reflection 10/5 📚

With a majority of the class time being dedicated to group work, I appreciated that we were expected to begin our shared Figma file amongst the group and explore its documentation capabilities. Although we had already began a shared Google Docs file, it was nice to easily transfer over all of the comments we had related to intial ideation. TJ had checked in on us during the process and I showed him all of the various categories I included on our file, including: expected project learning outcomes, our submitted project specs, materials inventory, ideation meetings with TDF faculty, and our experimentation process across software and hardware. He told me I would be a great project manager -- I agree. It brings me great joy to organize an overwhelming amount of information and summarize it into concise categories.

<img width="668" alt="figma file overview" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/29d858b0-259b-4a2c-a1a8-c73e2396388d">

## Pre-Lecture DiWire Testing 10/10

Although we want to find a much more minimal wire feeder, our first accessible testing point was the DiWire machine in the Jacob's Hall Makerspace. It is about 12" x 6" x 6", rather sturdy, and can support 1/16" - 1/8" wire. Our first test (from last weeks report) showed that it can bend very thick 1/8" wire, but there were limitations on manipulating the wire to curve since only sharp angles were possible. Consider the interface of the DiWire software (reference following image): the functionality is only through the use of arrow keys on a keyboard, providing a very limited scope of movement for the wire, in addition to the speed the wire is fed.

<img width="400" alt="DiWire User Interface" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/5762584e-7797-4ba1-9a58-bd61f4fdadc6">

For our second test, we obtained 1/16" wire to feed through the DiWire machine. We knew it was thin enough to be manipulated to a sharp angle, but wanted to explore malleability for curves. Using a single chisel (x: 0, y:0, z: 45) we provided a "wedge" in which to test how well the wire would follow a guide.

<img width="400" alt="DiWire test, single chisel" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/b7947c83-644e-4109-ba80-b3ceb12685c2">

It worked well and the result was what we expected. This guaranteed that, given the proper power of our next wire feeder, alongside a movable "arm" or "wedge", we could manipulate wire into a curved form.

Next we tested the 1/16" wire using two chisels ((x: 0, y:0, z: 45), (x:45, y:90, z: 45)) to see if we could guide the curve at an angle in order to produce a spiral.

<img width="400" alt="DiWire test, double chisel" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/0229645f-f0b1-4d0d-838a-808c718c74cf">

Success! It was a smooth process and provided better insight into the quality of our wire, as well as contributing to the project scope of creating an interactive, kinetic-sensory wire sculpting installation.


## Post-Lecture Monday Night Work Session 10/9

In trying to manage all 3 of our schedules to find a working session, we ended on 7-9 PM after lectures, as well as working mid-afternoon on Wednesdays, and updating documentation on weekends. So after lecture on Monday, we all headed to the Jacob's Hall Makerspace to collectively test out our first Photon 2 prototype using a Continuous Rotation Servo Motor with an accelerometer to test ways that we could correlate interactive movement with the rotation of the motor. We all worked on our own laptops alongside eachother and helped whenever the other one got stuck on a certain step. It made the experience of working past 9 AM much easier when it was with friends. We all got ours working and felt comfortable in exploring low-fidelity prototypes using the servo motor going forward!

<img width="400" alt="Photon 2 Accelerometer tutorial" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/16a674de-9238-48a2-a452-62c4d28c2ab2">

Additionally, I finally know how to read diagrams for connecting wires across a breadboard and microcontroller!!! It was very cool. :-)

<img width="333" alt="Photon 2 circuit diagram" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/be84602b-14f3-4292-8a7b-267de71a0236">

## Mid-day Wednesday Work Session 10/11

The goal of this meeting was for the group to reach a consensus on our structural approach to the robotic arm. We ended up deciding to start with a lo-fi prototype using a 3d printed gear that fit with our servo motor, as well as attaching it to a base plate and hinging the "wedge" along that. Reference the lo-fi diagram by our in-house artist, Matthew:

<img width="400" alt="lo-fi prototype diagram" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/01bcd219-72e9-4f08-84c1-6d3370800f39">

Here was our plan of action:

- Buying cabinet hinge (@Matthew), bringing metal-binding apoxy
- Obtain metal plate (1” x 3”; bigger plate can make different alterations)(@ Divya)
- attaching to base with rivet gun and fasteners
- 3d printing gear mechanism (@Marissa)

And yes, I went through a crash course in 3d-printing yesterday using the Prusa machines and Cura software. Here are the various gear components we are printing for our mini prototype:

<img width="400" alt="Cura software gear components" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/46b1085c-74d3-46f0-a044-4a05261252b8">

It was *awesome* and I'm going to be checking out my print before class today (10/12). Fingers crossed that my quick research on the in-fill will leave us with a decent amount of resistance as we test the prototype with 1/16" wire.

# Reflections

📌 I love project planning and updating the collaborative Figma document! Lists, action items, and process timelines make the world go 'round.

📌 It has been interesting to collaborate in a team for a rather intimidating project. Although we are all a bit nervous, we are more curious and optimistic than anything. Collective mindsets truly make a difference in the integrity of shared work.

# Speculations

📌  Based on my interactions with various Photon2 and kinetic-sensory components, I have started reflecting on what I'll do for my final TDF project. With my love for academia and modern learning methods in the classroom, I am curious of the ways in which I could represent student perspectives of learning through an interactive art installation in order to trigger valuable conservations on education.

---
**Back to [README.md](../README.md)!**

---
