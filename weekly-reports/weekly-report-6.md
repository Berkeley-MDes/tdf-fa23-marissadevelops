# Weekly Report 5: 9/28 - 10/5

## Thursday Lecture Reflection 9/28📚

The process of information overload when being presented all of the proposed ideas for Project 2 was unique, but I feel I was very naive in my approach. My sense of curiosity overpowered my considerations for feasability. And although I proposed the Health of Graduate Students idea, I did not end up being assigned it -- which is fine, because I realize now I may have been very defensive over the process since it was my brainchild. 

Instead, I am working in the Robotics Wire Sculpting group. I was so focused on the notion of building a digital ecosystem to create art installations that I never once considered feasability when voting for the project! It is scary to begin interacting with all of the required components across motors, robotics, microcontrollers, and sensors, but I knew that if I were in my Graduate Student Health project, that would've been well within my comfort zone. I am always obsessed with my niche topic from an educator lens, but sometimes I want to step away and just be a student in STEM. I believe that from experiencing the highs and lows of prototyping, it may actually teach me *more* about the learning experience of students than if I simply view it from a meta perspective.

When I got together with my group (Matthew, Stephanie, Divya, Yoojin, Yanru), we were all generally nervous to actualize this idea, besides Matthew, who proposed the idea in the first place! 

### Some immediate challenges:

- There is already a wire bender in the makerspace, *but* it has limited mobility and user interaction (ie, "Oh no, did we just sign up to re-invent the wheel?")
- Only one of us had coding experience, one had mechanical engineering experience, and the rest of us were mainly digital designers.
- Six people is a lot, and we'd have to break up into groups eventually, but we needed to figure out where to atleast start first.
- Our ideation process kept coming back to focusing on a single artifact to be wire wrapped, instead of building a digital ecosystem regardless of the artifact.

We all decided to ferment on the idea over the weekend and search for inpsiration. Some people wanted to completely stray away from the initial concept and do an entirely different project (with less workload), but eventually we all still committed to the idea after having a group meeting. 

## The Group Meeting:

The ideation was all over the place (in a good way)! We began reflecting on orientation of the wire feeder, how sensors could be used to sculpt wire, the possibility of sculpting other materials, and the item we'd use to apply pressure to the wire itself (to mold it).

**Ideas:**

Goal: Approachable installation using sensors that alters the angle at which wire exits a wire feeder, leading to a curvature-based wire sculpture. 

Robotic wire sculpting ideation:

- Motivation:
  - crystal wire wrapping: having a sculpting model that could wrap any object the user inserts into the space
  - 2D wire sculpting: Application: consider an etch-a-sketch that alters x-y aspects
- Sensors:
  - using values from sensors (distance of user from sensor) to determine x-y-curvature coordinates
- Possible formats:
  - Etch-a-sketch inspiration: grid of pins, tying string to magnet on top, back has magnet that is controlled similarly; user interactions with sensors alter design that is constructed
  - 3D pen, plastic-based (PLA)?
  - Wire feeder with interactive robotic arm to guide shape of wire ⭐
- Orienting angle of wire to guide curves:
  - Tube-like structure (macaroni noodle shaped)
  - Wedge-like structure (small linear arm)

Splitting into two groups:

- One team
  - Half focus on sensors and digital mechanisms
  - Half focus on robotics mechanisms
  - *Would have issues with working asynchronously with physical/digital*
- Two teams ⭐
  - Creation (interactive mechanism to build the structure): Matthew, Marissa, Divya
  - Destruction (interactive mechanism to destroy the structure): Stephanie, Yanru, Yoojin
  - *Don’t have to do the same idea, but can coordinate in the future about our contrasting projects*

We landed on doing two teams that could approach the same project from two different perspectives. Although we're workign seperately, we'd like to see how they could have a symbiotic relationship when we reach a point of tangible prototypes!

# Monday Lecture Reflection 10/2📚

My passion for note taking in class always leaves me with gems of wisdom from our faculty.⭐📚 

TJ's lecture on his experience with digital ecosystems gave me hope for my projects. Beyond the overaraching goal of viewing digital ecosystems as a collections of many tiny experiments, his metaphor for the "digital ecosystem toybox" was inspiring. I love the idea of having monthly iterations of testing cool technology, vetting it through research tasks, then adding it to the inventory of cool-things-to-be-built. 

Additionally, Jeff's lecture on types of gesture recognition was amazing! I finally saw an example of machine learning through Edge Impulse and could see the ways in which a Photon2 sensor could contribute to recognizing the kinetic movements of a user.

# Robotic Wire Scultures: Creation Group

I would like to pat myself on the back for how much I take organized notes (only because I love to). It has been awesome to see everybody collaborate on the documents I build! Anyways... 😎

After a meeting at the makerspace on Wedneday morning and one divergent thinking exercise later, we finally decided on our materials and the general approach to the project. Here they are:

- Wire feeder
- 0.8” copper wire
- Photon 2 microcontroller with distance sensors (Closer to sensor > bigger spiral; farther from sensor > smaller spiral)
- Curvature-inducing mechanism to guide wire and sculpt into specific shape
  - Mechanism can rotate to change spiral diameter based on numerical input from sensors
 
While in the makerspace, Matthew and I tested out the current wire feeder that Jacob's Hall owns. It is heavy duty, but definitely had limitations due to only having the ability to make sharp angles, but not curves. Additionally, it was not very transportable, nor could it feed wire from any orientation other than the x-axis.

![wire feeder in Jacob's Hall](https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/d686f78c-af4b-4dea-96ea-e92d0c4609bf)

We also consulted with Jeff over a shared Slack message and he had possibly the best feedback I could've expected (which largely helped to address any last technical issues before our project submission), alongside half a dozen resources and references for us to peruse through. 

My favorite pedagogical statement that Jeff told us was: In this phase of a project, I try to ask more questions than giving answers. Failure is the key.

Now *that* is a good teaching style and will always stick with me as I guide students one day in their work. Independence of the learner is so valuble, while also being able to guide them towards their goal with revelant resources. It provides an environment rooted in both autonomy and collaboration.

Lastly, he shared a cool resource with us that was a published thesis from MIT in 2001 on "Behavioral Kinetic Sculptures" that inspired a unique perspective in which to view our audiences interaction with the sculpture. Despite it's mechanical structure, the immediate responsive feedback with a user and their movement (ie, kinetics) enables a symbiotic relationship. I then viewed the installation as an anthropomorphic interpretation of passing the creative labor from the user to the robot, but still maintaining the users involvement by means of sensory input. Very neat.

> Reas, Casey. “Behavioral Kinetic Sculpture.” Massachusetts Institute of Technology, 2001.

# Reflections

📌 If we are asked to propose project ideas, and we vote on what we're interested in, we will absolutely have to bring that idea to fruition. Tread lightly. 

📌 My stark introduction to digital ecosystems has provided me a much broader insight to the amount of effort that goes on behind-the-scenes for interactive art installations. 

# Speculations

📌 I am curious in the ways that digital ecosystems could translate to introductory-level STEM projects for undergraduate students to explore creative expression and technological literacy. Both at an aesthetic and functional level, it challenges students to consider the audience they're serving and digging deeper into the reasoning behind their prototypes. 

---
**Back to [README.md](../README.md)!**

---
