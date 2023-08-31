# Weekly Report 1: 08/24 - 8/31

I must inform you, with my PhD goals lingering in the back of my head, I am often viewing my educational experience through two lenses as both a student and future educator. I think MDes is the perfect case study for looking at a brand new program, seeing what it means to give students autonomy and flexibility in their curriculum, and to challenge the status quo of common andragogical standards at a renowned research institution. What tools are we using, how were they introduced to us, what feedback have I heard from peers, how extensive is documentation for the course, do students *use* that documentation, etc... **This goal may prove to be exhausting, but I want to build my tolerance for discomfort early on if I want to write a dissertation, so here I go.** 📚💪

<details><summary>Class Orientation Reflections 📑 </summary>
Considering my background is in STEM education: yes, the syllabus is my holy grail. I love the first day of class because we get to go over course expectations and curriculum! There are also motivational breadcrumbs sprinkled throughout the seminar. Here are some of my written notes from our lecture on 8/24. 

>[!NOTE]
>Transcribing hand-written notes (although I love analog) will not be conducive to contributing towards our personal AI model at the end of the semester. I'll be transitioning to my macbook because time is of the essence. I'll make sure to still experiment with physical sketching/ideation methods and submit them here though.📝

- We're here to build competencies in emerging technologies.
- There's no guidebook with emerging technologies, be a fast learner.
- Reflection is valuable and there are many mediums available to document ideas.
  - A concept I never considered: **documentation contributes to preserving intellectual property** (wow!).
  - The world is our oyster: decisions, calculations, designs, ideas, research, inspiration, changes, modifications, iterations, reflections, sketches, diagrams, schematics, images, video, GIFs, Figma, web links, and more!
  - This means: WRITE! We are here to develop our voices in design.
- An instructional method I've never seen before: offering difficulty levels for projects.
  - This ties back to student autonomy and letting them determine how intense they structure their semester.
- This class trains us to cultivate a prototyping mindset and take risks! I am honestly not used to this, I used to write math proofs that were due twice a month and I had weeks at a time to perfect them. I recognize now that there was a level of complacency I grew accustomed to in my math courses over the years, but now it's time to be curious and nervous and feel all of the feelings!
</details>

---

## Project 1: Computational Design
The initial onboarding for the class did feel a bit overwhelming, but I expected that and it is probably the natural reaction towards the transition into graduate school. Once I got everything set up with my Wiki page I felt better prepared to start the journey of documenting my progress.

We were introduced to a sample problem: constructing a phone stand. My mind immediately went to this thought: how can I use this for my YouTube videos and Instagram reels? I felt guilty at first when wanting to meet my own needs, but I suppose I am also an end-user for products? 

From there, I tried to switch gears and consider a more general population of users beyond myself: Gen Z content creators. Something that both they and I have in common is needing a product that supports multiple formats for holding a phone. Different social platforms require different parameters.

- YouTube
  - Video format is typically horizontal orientation for long-form videos
  - Still shots (AKA b-roll) for transitions
- Instagram reels/YouTube Shorts/TikTok
  - Video format is typically vertical orientation for short-form videos
  - Often recording at different angles, need to be able to hold the phone in place without it slipping
  - Users are often on-the-go and can't afford something clunky -- especially for younger generations, it may even be *embarassing* to look like they're doing anything that isn't nonchalant
 
**Let's consider accessibility!**
One of the lecturers mentioned how although there are a lot of online resources available for learning emerging technologies, they may have implicit biases that we then inherit. So in terms of the phone stand prototype, are we, as designers, assuming...

- User environment
- Physical attributes (height, range of motion, accessibility features)
- Cultural background
- Product experience and social cues

The provided visuals for the slides were informative too. The 3-dimensional plotted graph that tracked range of motion for a user really caught my eye. There are geometric capabilities beyond free range sketching during the ideation process. There are computational tools that can contribute to the design as well (all of my years in math and I finally get to see a technology application!)

There was a great anecdote mentioned as well. Architects know they're going to create a building, but we, as designers, cannot guarantee the tangible form of a design process like they can. Our job title does not promise an outcome, our actions do.

### Now for the scary part: Rhino + Grasshopper. 

It only feels intimidating because I've never worked in a CAD software before, but I'm going to make sure to explore some general Rhino tutorials to at least feel comfortable navigating the program. The next step is checking out the prototype documents that were shared with us and tinkering with them. 

Foresight as I prepare for this step: I want to do more than just print the original design. I don't have the skills to build something from scratch in Rhino, but I *really* want to try out Grasshopper because messing with parameters that automatically update the design seems more manageable. I also recognize that as I prepare for my own prototype, I keep thinking about my lacking skillsets in CAD software to 3D print and lack of know-how for Adobe Illustrator to laser cut.😓 This makes me want to shy away from building my own design, but I must conquer the anxiety in order to try out cool ideas!

Since the *CD_files* folder contained a lot of file formats, I googled what [files are supported in Rhino 7](https://3danz.com/pages/supported-file-formats-in-rhino-7) to figure out what the files contained. I started with opening the *CellPhoneStandModel_All.gh* document.

**Tinkering with the files:**

- Lots to explore! Started at the top left of the document.
- Started with the floor model for the activity; inputs included: xyz orientation for camera, width/length, panels for processing iamges, and number types.
- Similar construction for the student model; inputs included: xyz orientation for camera, width/height, viewpoint, cloud point activity (possibly related to tracked range of motion that was mentioned in lecture?)
- More parameters for construction of the phone model; inputs included: xyz orientation for camera, width/length/corner radius/thickness/tolerance, phone table offset, phone camera lens, phone camera view, 
- Tinkered with the settings for phone dimensions; the phone stand outline turned red if I changed settings that didn't meet the parameters of the stand. It was sort of awkward having to re-orient the camera whenever I changed the dimensions though. Also messed with the phone viewing angle parameters.
- Hey! Changing the viewing orientation to landscape moved the phone to the direction I needed for my prototype (ie, having different orientations based on the social media platform the video was being shared to). The stand became red though since the phone was outside of the parameters.
<img width="437" alt="Vertical phone orientation" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/5ef8620b-f78e-446b-a38f-6a91ff46e4a4">

❗The parameters visible in this image are called the frustum: the portion of a cone or pyramid which remains after its upper part has been cut off by a plane parallel to its base, or which is intercepted between two such planes. This is why we defined the dimensions of the camera lens/view. *This made my math brain very happy.*

- From all of those inputs, there's a tree that merges the phone components together!
- I may have found the switches for the model to indicate any errors: `if(x=0,inside,if(x=1,intersecting,outside))` defines the swatch colors for the phone stand.
- After a long journey, there are functions for bool statements relating to errors and such, assumingly leading to the final output of the generated CAD model in Rhino.

That was a lot, but I feel better having explored Grasshopper for myself. Looking forward to lecture on Monday!😄

### Into Jacob's Hall to try out the laser cutter!

I tried to modify the file in Rhino + Grasshopper, but there are some incompatibilities with my laptop to use the remote control panel. My reservation appointment was coming up very soon so I decided to modify the phone stand directly in Adobe Illustrator.

- I knew my phone was too wide for the phone insert based on testing out the prototypes in lecture last week, so I widened the phone insert.
- I wanted the design to allow for orienting the phone horizontally and vertically (initially did not have time to modify the prototype for this).

1. I made my first prototype using deep engraved acrylic! Since the material was 1/8" instead of 1/4", the gaps on the prototype were too wide once I put the phone stand together.
<img height="400" alt="phone stand prototype 1 issue" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/e660af2f-8c8d-415d-abbe-bd2d5b65d053">
<img height="400" alt="phone stand prototype 1 issue (2)" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/83e74c92-dbb0-419a-9907-362d3230f794">

2. I didn't have any more of this beautiful material available, so I wanted to just fill the gap with black electrical tape to make the prototype useable. I asked Gary about different solutions and he told me I should modify the file and try again. Cody also told me that adding the black electrical tape is just a band-aid to a larger structural problem. Although I wanted the path of least resistance, I made another attempt!
3. After running into Chris and telling him my process as well -- mainly that I didn't want to mix wooden material with the acrylic for my prototype -- he said that there is nothing wrong with mixing materials and it's a part of the process. I told him I wanted to paint the wooden material black if I made it again, to which he told me *paint is for protection*. Dor has said something similar in her lectures. So I will accept not having an aeshthetically-driven prototype.
4. Chris recommended that I minimize the gaps of the phone stand in Adobe Illustrator by about half the width.
   - Collecting measurements:
     - PHONE HOLDER DEPTH: 0.8" ➡️ Make phone holder depth 0.7" (my phone is 0.5" and I want room to adjust angles)
     - SEGMENT SLOTS: 0.5" ➡️ Make slots 0.25"
     - SEGMENT HEIGHT: 0.5" ➡️ Make segments 0.25"
5. I also removed the overhang of the phone holder in the Illustrator file so I could hold my phone vertically!😄

Here are my adjustments to the Illustrator file:

<img height="573" alt="Phone Stand components" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/b9b775d1-695d-4cb5-86a8-8702ae5767c3">

>[!NOTE]
> Deeply hoping I corrected the measurements right the first time for my next laser cut session!!!

Some issues/improvements with the second print:

- Due to only using Illustrator, I didn't have leveled segment slots for one of the pieces; Grasshopper would've provided more accuracy.

<img height="400" alt="phone stand prototype 2 component issue" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/0ea46bbd-191d-450f-9ba3-898b9b7d4c31">
<img height="400" alt="phone stand prototype 2 component issue" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/e6730d41-3d1a-44f0-8931-eeac2aaad1f9">

- Despite the level issue, the slots fit much tighter to the base components though :-)
- I removed the overhang of the original phone stand design so that I could have vertical phone orientation.

I did one more round to fix the uneven base component and it went great!

<img height="400" alt="phone stand prototype 3" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/90bfebb8-9597-4d24-8ffc-106502e6e774">

And here is the prototype comparison! I am so proud of my progress.🙂

<img height="400" alt="phone stand prototype comparison" src="https://github.com/Berkeley-MDes/tdf-fa23-marissadevelops/assets/143042473/8e69d11d-db59-4d03-9c43-31c1f3fd9bc3">

---
**Back to [README.md](../README.md)!**

---
