# FYP-ECHOSCAPE_VR

Basmah Arif | CMP6200/DIG6200 Individual Honours Project A AYR 2024/5 | Student ID:21159823

Individual Honours Project
To Access the project, navigate to the compressed zip folder > Unity > **“Assets”** and open it via Unity Hub Editor version 2022.3.58f1. The Export folder contains the .apk build file of the VR project.

# Overview
This project presents "Echoscape VR," a Virtual Reality (VR) based environment developed using Unity and C# with extensive testing on Meta Quest 3 VR Headsets. Echoscape VR is a 3D pathfinding environment designed to study how visual and auditory cues impact users' spatial memory and navigation skills. The project focuses on immersive environmental design, cognitive engagement, and task-based interaction to enhance memory recall and spatial awareness in VR.

# Description of the Game
In Echoscape VR, players are immersed in a dynamic 3D environment with barriers and dead-ends rather than a traditional maze. Players must complete a series of pickup and delivery tasks across two different city-style environments. Visual cues (color-coded trees) and auditory cues (directional popping sounds and ambient environment sounds) guide players through the world.
Players perform eight specific tasks, such as collecting bread from a bakery shop and delivering it to a house, picking up a suit from the dry cleaner, finding car keys, and returning a pet to a home location. Each task is time-limited between 7 to 10 minutes depending on task distance. Players are evaluated based on memory recall, task completion time, and pathfinding effectiveness.


# Virtual Reality Game Mechanics

**Single-Player Pathfinding Tasks:**

1) Explore two city environments.

2) Complete 8 pickup and delivery objectives in a environment with barriers. 

3) Explore areas with visual (red/blue trees) and auditory (popping and ambient) cues.

4) Avoid dead-ends and wrong paths using environmental hints.
   
5) Visual Progress Tracker and Objective Tracker (HUD-based) continuously show task completion and exploration percentage.


**Tasks Include:**

- Picking up bread and delivering to a house.

- Collecting a suit from laundry and delivering it.

- Collecting car keys from a garbage area and giving them to a car owner.

- Picking up a dog from a pet shop and returning it to a house.

Each objective tracks completion status, and progress is measured via live HUD elements.


**Environmental Features:**

- **Red Trees:** Indicate wrong paths.

- **Blue Trees:** Indicate correct paths.

- **Auditory Cues:** Popping sound grows louder as players approach their objective.

- **Environmental Sounds:** Waterfalls, birds, ambient city noises help with orientation.


**Teleportation and Special Mechanics:**

- Players have teleportation points at major city intersections for faster backtracking to previously visited checkpoints.

- After staying over 30 seconds in the garbage area, a sound-based warning appears to signal time wastage, encouraging players to reorient towards the objective.

- Incorrect path detection triggers red trees and eerie sounds to notify players they need to change direction.


# VR Controls

**Hand Controllers:**

- Right Thumbstick for Player Movement and Turning.
- Left Thumbstick for Camera Rotation. (The UI will move with the camera rotation). 
- Trigger Button A to pick up and drop objects.
- Holding Button R1 + Button R2 enables Teleporting function.  

**Interaction System:**

- Proximity-based grabbing for object interaction.
  
- Wrist-mounted HUD showing current objective, task progress, Distance, Time Limit.

**Visual and Audio Feedback:**

- Visual task confirmations and audio chimes when objectives are completed.


**Power-ups:** 

- When a player completes a task and reaches the Checkpoint, they get coins which they can use to obtain extra time to complete next task during the game.
- The functionality of a Diamond powerup is more advanced which freezes the time of the objective. 


# Background/Motivation

The inspiration for Echoscape VR came from research in spatial memory rehabilitation, gaming environments, and educational VR applications. Combining the cognitive challenge of memory-based navigation with immersive sensory feedback, the project aims to understand how multi-sensory cues aid in improving spatial cognition.
Building this VR application bridges entertainment and research, offering both a challenging experience and practical insights into spatial awareness enhancement techniques. The motivation was to design an engaging, research-driven VR environment that simulates real-world navigation challenges in a safe, controlled, and scientifically measurable setting.


# Technologies Used

- Visual Studio: https://https//code.visualstudio.com/ (Code Development)
- Unity: https://unity.com/ (Game Engine used for development)
- GitHub: (Version control and collaboration)
- Unity Asset Store: https://assetstore.unity.com/ (Asset Store used for 3D Models, Characters, Tools, Visual Effects in the game)
- C#: (Programming Language for scripting and game mechanics)

# Testing Summary

- Device: Meta Quest 3
- Participants: 22 participants tested the application.
- Evaluation: Task completion times, memory skills, and pathfinding efficiency were recorded.
- Additional Feedback: Visual and auditory cue effectiveness and overall immersion experience were rated post-session.

# Folders / Structures of GitHub Repository

- [.github] (contains configuration files, such as workflows for CI/CD pipelines)

- [documentation] (contains weekly logbook, consent forms, Post-Quiz, Participants' Images, Participants' List, Powerpoint presentation, Videos/Tutorial)

- [Unity] (contains the main Unity project files, including assets, scenes, scripts and prefabs necessary for the game's development)

- [.gitignore] (contains untracked files to ignore in Git such as Build files, logs)

- [README] (this file contains complete documentation)


# Folders / Structures of Final Submission

Basmah_Arif_21159823

[bin] (contains compiled binaries)

[code] (contains source code with build files)

[Readme] (this file contains complete documentation)

[video] (this file contains gameplay and project demo video with h264/aac explaining key concepts)

# Installation

Clone the repository to your local machine:

git clone https://github.com/Birmingham-City-Uni/FYP-ECHOSCAPE_VR.git

Open the project using Unity Hub Editor version 2022.3.58f1.

Connect Meta Quest 3 via Link Cable or Wireless.

Build and Run the project for Android VR platform.


# Visual Studio

TODO:

Download Visual Studio from the "https://visualstudio.microsoft.com/downloads/"
Run the installer
Selected recommended workloads
Open Visual Studio from application folder


# Development Methodology

- Agile-based task management (weekly sprints + Gantt Chart).

- GitHub Projects used for progress tracking.

- Regular code commits, reviews, and version control.

- Participant feedback loops for iterative improvements.

# Quality Assurance

- Code linting and best practices followed.

- Manual QA testing across multiple participants and sessions.

- Weekly feedback-driven iterations.

- VR-specific user experience testing (comfort, motion sickness reduction).


# Contributors

Basmah Arif - Lead Developer


# Weekly Logbook

Throughout my time studying, this weekly logbook documents the skills, methodologies, feedback and achievements I acquire and accomplish during my Semester 2 Individual Honours Project Module. I will record this information on a week-to-week basis, offering detailed insights into the tasks I undertake. 

# September, 2024

**Week 1 – W/C 30th September 2024**

**Keywords:**

Spatial cognition, digital simulation, wayfinding (training), maintain spatial cognition, Virtual Reality, sound used in spatial cognition, sound affect to spatial cognition
features in crossing –What is good for your memory 

**Themes**

•	What is VR?

•	What is Spatial cognition (difference between wayfinding) and why it is important? 

•	How sound element play a role in spatial cognition
Or any other objects could affect the memory 
•	Related project using digital media to help spatial cognition 

**Papers Read:**

•	Klencklen, G., Després, O. & Dufour, A. (2012). What do we know about aging and spatial cognition? Reviews and perspectives. Ageing research reviews, 11(1),123-135. https://doi.org/10.1016/j.arr.2011.10.001 [Accessed 19 October 2024].
•	Marshall, J.C., & Fink, G.R. (2001). Spatial cognition: Where we were and where we are. NeuroImage, 14(1), S2-S7. https://doi.org/10.1006/nimg.2001.0834 [Accessed 21 October 2024].
•	Spence, I., & Feng, J. (2010). Video games and spatial cognition. Review of General Psychology, 14(2), 92-104. https://doi.org/10.1037/a0019491 [Accessed 21 October 2024].
•	Lee, E.A.L., & Wong, K.W. (2014). Learning with desktop virtual reality: Low spatial ability learners are more positively affected. Computers & Education, 79, 49-58. https://doi.org/10.1016/j.compedu.2014.07.010 [Accessed 21 October 2024].
•	Gardony, A.L., Martis, S.B., Taylor, H.A., & Brunyé, T.T. (2021). Interaction strategies for effective augmented reality geo-visualization: Insights from spatial cognition. Human–Computer Interaction, 36(2), 107-149. https://doi.org/10.1080/07370024.2018.1531001 [Accessed 24 October 2024].
•	Chang, Y.L. (2003). Spatial cognition in digital cities. International Journal of Architectural Computing, 1(4), 471-488. https://doi.org/10.1260/147807703773633482 [Accessed 24 October 2024].
•	Kim, B., Pack, Y.H., & Yi, S.H. (2017). The effects of presented media types on spatial cognition task performance in preschool children. Child Studies in Asia-Pacific Contexts, 7(1), 27-38. https://doi.org/10.5723/csapk.2017.7.1.027 [Accessed 25 October 2024].
•	Golledge, R.G. (2002). Spatial cognition and converging technologies. In Converging technologies for improving human performance (p. 122). National Science Foundation. https://books.google.co.uk/books?id=hH4iCQAAQBAJ [Accessed 26 October 2024].


**Assigned Tasks:**

Read Rowan’s paper 
Supervisor – send paper to Basmah 
-- How to test on VR 

# October, 2024

**Week 2 – W/C 07th October 2024**

**Discussion**

**Key words:** 
- spatial cognition, immersive digital simulation for way finding, Web based

- Think about how to identify different visual features to help people to enhance their memory of the location/space. 

**Action:**

- Find more paper for spatial cognition (way finding), 
- Read Aframe https://aframe.io/examples/showcase/sky/
- Write proposal
  

**Week 4 – W/C 14th October 2024**

**Progress:**

- Web based VR 
- Eye tracking – Xi find out 

**Action:**

•	What is spatial cognition?
•	Outdoor environment/ indoor environment visual/audio elements that affect the memory
•	Crossing –what elements will affect /help the memory/decision making process
•	Research on how to implement VR in Unity. Simulator 


**Week 5 – W/C 21st October 2024**

**Progress & Action:**

•	Researched on Features in Crossing:

I found that certain features in crossing areas can improve memory. These include clear landmarks, directional signs and consistent visual cues, which help users recognize paths and make it easier to remember routes and decisions they’ve made along the way.

•	Researched VR and what it is? 

It is a technology that creates a simulated, immersive environment which is used with a headset and sensors to track movement and provide interactive experiences. It is widely used in training, simulations and educational settings due to its ability to replicate real-world scenarios.

•	Researched about Spatial Cognition and its significant:

From my research, I’ve learned that spatial cognition is all about how people understand and mentally arrange the space around them. It’s essential for activities like finding our way, staying aware of our surroundings, and remembering specific locations or paths. This skill is very important in real life and plays a key role in various applications, especially in VR research, where it can help us understand how people navigate and remember virtual spaces.

•	Related Project Using Digital Media to Aid Spatial Cognition:

This study investigates whether people build and use spatial knowledge in virtual reality in the same way they do in real-world environments. Through immersive VR, researchers found that while virtual environments are effective in supporting spatial memory and wayfinding, they don’t completely match physical environments. Some differences were noted, especially in the depth of spatial awareness and the role of sensory cues, which are more limited in VR than in the real world. 

Reference: 

Zhao, H. & Montello, D.R. (2021). Wayfinding Behavior and Spatial Knowledge Acquisition: Are They the Same in Virtual Reality and in Real-World Environments? Annals of the American Association of Geographers, 111(3), 667-682. https://www.researchgate.net/publication/351659000_Wayfinding_Behavior_and_Spatial_Knowledge_Acquisition_Are_They_the_Same_in_Virtual_Reality_and_in_Real-World_Environments [Accessed 27 October 2024]. 

•	Outdoor/Indoor Environment - Visual/Audio Elements That Affect Memory: 

I found that different elements in outdoor and indoor environments, like visual cues (such as landmarks, colors and layout) and audio signals (such as background sounds and directional audio hints), are crucial for helping people remember spaces. In VR, we can modify these elements to see how they affect memory retention, allowing for a controlled study of their impact on how well users remember virtual spaces.

•	Researched on VR Implementation in Unity and Simulator Use: (References)

1.	Introduction to VR in Unity - PART 1: VR Setup. Available at: https://www.youtube.com/watch?v=gGYtahQjmWQ
2.	How to Make a VR Game in Unity - PART 1. Available at: https://www.youtube.com/watch?v=HhtTtvBF5bI
3.	Learn VR Development in 3 Hours - Unity VR Tutorial Complete. Available at: https://www.youtube.com/watch?v=YBQ_ps6e71k
4.	VR Robotics Simulator: How to Create a VR Scene in Unity. Available at: https://www.youtube.com/watch?v=Wxwl9Efv3KM
5.	Build a VR Driving Simulator in Unity3D. Available at: https://www.youtube.com/watch?v=d_AEmOWGuJ8


**Week 6 – W/C 28th October 2024**

• Focus on reading paper on 
•	What is Spatial cognition (difference between wayfinding) and why it is important? 
•	How sound element play a role in spatial cognition

**Progress & Action:**

•	Read the Sample Papers instructed by Dr.Xi in our last meeting. (Papers Read)

1.	Xu, T.B., Mostafavi, A., Boot, W.R., Czaja, S. and Kalantari, S. (2024). Assessing the Feasibility, and Efficacy of Virtual Reality Navigational Training for Older Adults. arXiv preprint arXiv:2407.12272. https://arxiv.org/abs/2407.12272 [Accessed 29 October 2024].
2.	Hegarty, M., He, C., Boone, A.P., Yu, S., Jacobs, E.G. and Chrastil, E.R. (2023). Understanding differences in wayfinding strategies. Topics in Cognitive Science, 15(1), pp.102-119. https://doi.org/10.1111/tops.12609 [Accessed 29 October 2024].
3.	Chen, J., Li, N., Shi, Y. and Du, J. (2023). Cross-cultural assessment of the effect of spatial information on firefighters’ wayfinding performance: A virtual reality-based study. International Journal of Disaster Risk Reduction, 84, p.103486. https://www.sciencedirect.com/science/article/abs/pii/S2212420922007051 [Accessed 30 October 2024].
4.	Fialho, L., Oliveira, J., Filipe, A. and Luz, F. (2023). Soundspace VR: spatial navigation using sound in virtual reality. Virtual Reality, 27(1), pp.397-405. https://link.springer.com/article/10.1007/s10055-021-00597-0 [Accessed 30 October 2024].
5.	Yang, W. and Jeon, J.Y. (2023). Effects of lighting and sound factors on environmental sensation, perception, and cognitive performance in a classroom. Journal of Building Engineering, 76, p.107063. https://www.sciencedirect.com/science/article/abs/pii/S2352710223012421 [Accessed 01 November 2024].

•	Researched on the difference between Wayfinding & Spatial Cognition and its significant: 

From my research, I found that spatial cognition is how we understand and remember the space around us, including how we interpret layouts, distances and the relationships between objects. It’s different from wayfinding, which is specifically about navigating from one place to another. While spatial cognition is about knowing and understanding space in general, wayfinding is more focused on using that knowledge to choose directions and reach a destination.
Spatial cognition is important because it helps us interact with our surroundings, remember locations and plan routes in both real and virtual environments. In VR, it’s essential for creating immersive spaces that feel natural to explore, which is useful in fields like urban planning, architecture and training simulations.

•	Researched about how the Sound Elements are used in Spatial Cognition:

I also looked into how sound influences spatial cognition. Sound elements, like ambient noise or directional cues, can make environments feel more realistic and aid in understanding spatial layouts. For example, in VR or real-world navigation, sounds like footsteps, echoes or specific noises tied to landmarks can help people better judge their position and make decisions about direction. 
Another example is background sounds (like birds or traffic) help us orient ourselves, while sounds from specific directions can guide us in navigating spaces. Sounds linked to certain areas also help reinforce memory, making it easier to remember locations and paths.


# November, 2024


**Week 7 – W/C 04th November 2024**

Continue literature review based on the feedback. 
Or any other objects could affect the memory


**Progress & Action:**

This week, I focused on refining my literature review following the feedback received on my A1 Proposal. Dr. Xi’s feedback highlighted areas where my proposal could be strengthened, especially regarding the foundational theories of spatial cognition and the role of sensory elements in VR environments. 
I explored additional papers on sensory impacts in spatial cognition, particularly how objects, textures, lighting and other visual markers could enhance memory formation in VR simulations. This expanded my perspective on how spatial cognition is influenced not only by sound but by a combination of environmental factors, which could lead to a more holistic approach in my research.

•	Reflection: Receiving feedback was beneficial as it clarified areas for improvement and focused my attention on more specific aspects of spatial cognition. Enhancing my literature review has provided a stronger theoretical foundation for my project, which will guide future design decisions.

•	Milestone: Completed a revised literature review addressing feedback and identified additional research papers that explore non-auditory elements in VR-based spatial cognition.



**Week 8 – W/C 11th November 2024**

**Themes**

1.	Spatial Cognition Fundamentals
   
•	Keywords: Spatial cognition, cognitive mapping, spatial memory

•	This theme examines the basic principles of spatial cognition, including how individuals perceive, interpret, and remember spatial relationships. It provides a theoretical foundation for understanding how VR can be used to support spatial memory and navigation.

2.	Virtual Reality and Spatial Cognition Enhancement
   
•	Keywords: VR training, immersive simulations, spatial learning

•	This theme focuses on how VR is used to improve spatial cognition, especially in training applications. Studies such as those by Xu et al. (2024) and Zhao & Montello (2021) explore VR's potential to simulate realistic environments for spatial learning and memory enhancement.

3.	Wayfinding and Navigation in VR (change it to spatial cognition)
   
•	Keywords: Wayfinding, VR navigation, cognitive mapping in VR

•	Wayfinding involves navigating from one location to another, which is a crucial subset of spatial cognition. This theme reviews studies on VR-based wayfinding and compares it with real-world navigation strategies, drawing on work by Hegarty et al. (2023) and Chen et al. (2023).

4.	Role of Visual Cues in Virtual Environments (change it to spatial cognition for virtual cue)
   
•	Keywords: Visual cues, lighting, object contrast, landmark positioning

•	Visual elements such as lighting, contrast, and landmarks are essential for effective spatial navigation in VR. Research by Spence & Feng (2010) and Gardony et al. (2021) shows how visual cues impact memory retention and orientation within digital spaces.

5.	Impact of Sound on Spatial Cognition
   
•	Keywords: Auditory cues, spatial audio, sound in VR

•	Sound plays a significant role in enhancing spatial awareness. Studies like Fialho et al. (2023) and Yang & Jeon (2023) investigate how audio elements aid spatial memory and improve immersion in VR, providing insights into how sound can reinforce spatial understanding.

6.	Evaluation Techniques for VR-Based Cognitive Training (related project)
    
•	Keywords: Eye tracking, user feedback, cognitive assessment in VR

•	This theme focuses on how researchers evaluate VR's effectiveness for cognitive training, particularly through user interaction analysis and eye-tracking technology. This includes a review of techniques for measuring spatial cognition, as highlighted in studies by Klencklen et al. (2012) and Golledge (2002).

**Progress & Action:**

This week, I made progress in writing the literature review of my project. I managed to thoroughly review 35 academic papers focused on themes such as spatial cognition, visual and auditory cues in VR and evaluation methodologies for VR-based cognitive training. From these papers, I critically analyzed and synthesized key insights, ensuring they were effectively linked to my project objectives. I also highlighted gaps and limitations in existing studies, which will help shape the design and evaluation framework for my VR platform.


**Actions Completed:**
•	Reviewed 35 academic papers related to spatial cognition and VR.
•	Wrote a detailed literature review linking research findings to my project goals.
•	Identified gaps in the literature to address in the next phase of my project.


**Week 9 – W/C 18th November 2024**

This week, I successfully completed and submitted the literature review section of my project within the designated deadline. I ensured that the review was comprehensive, organized and thematically structured, with each theme supported by relevant references. During the process, I also identified additional academic papers to enrich the review and incorporated them into the appropriate sections. By refining the structure and ensuring all references were correctly attributed, I made the literature review more cohesive and aligned with the project objectives.

**Actions Completed:**

•	Completed the writing of the literature review and submitted it on time.
•	Identified additional papers to support each theme, further strengthening the analysis.
•	Accurately referenced all sources within the review, ensuring alignment with academic standards.


**Week 10 – W/C 25th November 2024**

- Has talked Ben and Jieling
- Unity or Web—you need to make a decision
- Finish the Ethic form
- Please think about your design

This week, I discussed project details with Ben and Jieling to refine my approach. After careful evaluation, I made the decision to proceed with Unity as the platform for developing the VR prototype, prioritizing its advanced features and flexibility over web-based alternatives. Additionally, I made progress on completing two forms required for the project ethics approval. However, I still need to finalize the project declaration form, which I plan to complete and submit to Dr. Xi soon.

**Actions Completed:**

•	I have consulted with Ben and Jieling regarding the project.
•	I chose Unity as the primary development platform for the VR prototype.
•	I managed to complete two forms for ethics approval and prepared to finalize the project declaration form.


# December, 2024

**Week 11 – W/C 2nd December 2024**

**Progress & Action:**

This week, I finalized and submitted all ethics approval forms, including the project declaration form, to Dr. Xi. With the ethics process complete, I began planning the initial design for the VR prototype, focusing on features like visual landmarks and sound cues to support spatial cognition. I also sketched a basic layout of the VR environment and researched Unity’s tools for integrating sound and dynamic lighting. 


# January, 2025

**Week 14 – W/C 27th January 2025**

**Progress & Action:**

After the holidays, we discussed the deadlines for our next milestones regarding our Project and Dr.Xi showed us examples of the posters which we will be making for our viva. She has demonstrated the requirements needed for the poster making process along with that she also conducted individual meetings in which I discussed with her about my questions regarding the final year project. I have also borrowed the VR headsets from Dr.Xi to use for my research project. I have started working on my Design part for which I will be using Unity, and this will be completed by Week 3.

# February, 2025


**Week 15 – W/C 03rd February 2025**

1.	Xi will send assets – garbage, house, interior 
2.	Experiment on mobile/VR platform and make a choice 
3.	Start level design, game mechanics design 

**Progress & Action**

This week, I made significant progress in multiple aspects of my project. I created a state diagram using Creately to outline the game flow and interactions. Additionally, I hand-drew a prototype draft for the environment maze and game UI and HUD, which helped visualize the core layout and user experience. I also started working on the UI mock-up and began implementing the level design in Unity.
Dr. Xi provided assets related to garbage, house exterior, and interior which I will include in my project. My plan is to design a house where players can enter and complete missions within the game.
To determine the best platform for the project, I experimented with both Unity’s VR and mobile functionalities. After testing, I decided to proceed with VR as the primary platform, as it aligns better with the immersive experience I aim to create.
Additionally, I emailed several potential participants for my study and received consent forms from a few. I updated my Excel document to keep track of the participants who have agreed to take part in my project.


**Week 16 – W/C 10th February 2025**

11th Feb.
Progress.  
Added keywords in dissertation 
Added concept design 
Have evaluation plan 
Have mockup. 

**Action:**

- In door navigation vs outdoor navigation—please match your literature.
- Test on VR


**Week 17 – W/C 17th February 2025**

**Progress:**

This week, I have implemented the feedback which I got in Semester 2, Week 3 Submission Point from Dr. Xi. I resketched and redesigned my implementation ideas based on my literature review as it had to be outdoor navigation instead of indoor navigation. I updated my dissertation document with the new designs and tried to work out the VR testing in Unity editor to check if it is successfully working on VR. I still need to borrow the VR headset from university to test it thoroughly if it works with the actual VR headsets and I also need to work on the pre-questionnaire for my project’s participants. I will also be communicating with more participants over the previous years to participate in my project as this week, my focus was on my implementation. 

**Action:**

Implementation – focus on level design and game mechanics 
Game design – how to use the game to achieve your goal?
Make decision: the purpose of the project: Is it for maintenance or assessment. 


**Week 18 – W/C 24th February 2025**

**Progress & Action:**

This week, I started the implementation of the city outdoor navigation environment in Unity. I inserted buildings and streets to create a realistic virtual cityscape that aligns with my project’s objective of enhancing spatial cognition through outdoor navigation. To enable VR interactions, I utilized the XR Toolkit plugin for implementing VR controls within the Unity editor. I also began drafting the questionnaire for participant evaluation, focusing on usability, spatial cognition effectiveness and overall user experience. 
After considering the questions posed by Dr. Xi, I have made the following decisions for my project:

•	The game design approach is to assess and enhance spatial cognition using navigation tasks, memory challenges and cognitive load measurements with the use of visual and auditory cues to evaluate navigation accuracy, memory recall and decision making. 

•	The project is Assessment Based, and its primary purpose is to measure and evaluate cognitive performance, focusing on spatial memory, navigation accuracy and cognitive load. It also enhances cognitive abilities through repetitive cognitive tasks and adaptive learning. 


# March, 2025

**Week 19 – W/C 03rd March 2025**

**Progress & Action:**

This week, I focused on preparing for the Week 6 checkpoint while continuing the implementation of my artefact. I structured the virtual environment into a realistic cityscape, including buildings, houses and streets to enhance immersion and align with my project's objectives.

Additionally, I worked on adding functional elements within the Unity project, ensuring that key interactions and features operate effectively. A major milestone this week was testing the project using a VR headset, which confirmed that the system is functioning as expected within a virtual reality setting.

To further progress towards participant evaluation, I prepared for pilot testing by developing pre- and post-experiment questionnaires. I also began the process of gathering participants for the upcoming testing phase, which will assess spatial cognition, navigation accuracy and user experience.


**Week 20 – W/C 10th March 2025**

**Progress & Action:**

Last week, I had a supervisor checkpoint in which I got very positive feedback along with some ideas suggested by both of my supervisors regarding my project. I started to further work on my implementation and planned to complete it by the upcoming week so I can have time for evaluation and testing. I worked on the object tracking functionality in my implementation and along with that I changed some ideas and reflected towards the feedback I got in which I removed the thoughts of dead ends in a maze and changed auditory cues to real life scenarios such as birds chirping, wind and music in the background. I also thought of the interview questions which I will be asking participants while conducting pilot testing. Overall, this week, I have been working on my implementation for the project but the only concerning bit is testing it on VR headset which I still need to figure out. 


**Week 21 – W/C 17th March 2025**

**Progress & Action:**

This week, I discussed the evaluation phase with my supervisor and planned a small test with 2–4 participants to validate the project and test methodology. Each session is expected to take 30–45 minutes, including VR navigation and questionnaires. 
We discussed the data collection process, which will include a pre-questionnaire, post-questionnaire, and a short quiz. As an example, my supervisor shared the Immersive Experience Questionnaire (IEQ) to guide the structure of evaluating immersion, focusing on areas like cognitive involvement and emotional engagement.


**Week 22 – W/C 24th March 2025**

**Progress & Action:**

This week, I made key progress in both implementation and preparation for participant testing. I successfully exported the .apk file and tested it on the VR headset. The Controls worked smoothly, and the system is ready for testing, which begins on Wednesday.
I also refined the tasks to be realistic and context-based, including:

•	Picking up bread and returning home
•	Delivering a suit from the laundry
•	Finding a lost key near garbage and returning it
•	Retrieving a pet and bringing it home

Additionally, I implemented gamified elements like coins and diamonds, which users earn at checkpoints. Coins extend the time limit, while diamonds freeze time and clarify tasks. I confirmed with my supervisor that using gamification is acceptable as long as it’s logically linked and I will include relevant review papers on gamification in my literature review to support this.


**Week 23 – W/C 31st March 2025**

**Progress & Action:**

This week, I prepared for the first round of participant testing, scheduled for tomorrow with 3–4 testers. The test will be a partial trial of the project, focusing on how different visual and sound elements affect spatial memory and pathfinding. I will use the Immersive Experience Questionnaire (IEQ) matrix to evaluate immersion levels.

I also made very good progress on my dissertation, integrating feedback and refining the structure.

Testing setup includes:
•	2-minute project introduction
•	10-minute improved pre-questionnaire
•	3–5-minute tutorial session
•	5-minute break
•	15-minute gameplay session (record number of tasks completed, total time and player interactions)
•	10-minute post-questionnaire
I received feedback on my questionnaire design and reviewed how to adjust Unity's developer mode and settings to support smooth testing and data recording. 

# April, 2025


**Week 24 – W/C 07th April 2025**

**Progress & Action:**

This week, I conducted testing with 4 participants for the pilot test and an additional 4 for Stage 2 testing. During both sessions, I kept a record of the tasks each participant completed, as well as their responses to the questionnaires.
I used a 5-point Likert scale across questionnaires to assess user experience, immersion, and the effect of visual and sound elements on memory and navigation. I also recorded gameplay sessions and will share the videos as part of the evaluation materials.
An important reflection discussed this week was how my literature review directly informed my design choices, such as the use of realistic audio cues, visual landmarks, and task-based navigation, all grounded in findings from research on spatial cognition and VR-based training.



**Week 25 – W/C 14th April 2025**

**Progress & Action:**

This week, I completed final testing with a total of 20 participants, including those from previous pilot and stage testing phases. I ensured that all data including task completion, immersion levels, and feedback was properly recorded and organized for analysis. I also began applying final touches to my dissertation, focusing on refining key sections and ensuring consistency across the document.



****Week 26 – W/C 21st April 2025**

**Progress & Action:**

This week, I focused on finalizing all project components. I organized and cleaned up my project folder and GitHub repository, ensuring all assets, code and documentation were complete and clearly structured. Additionally, I made further refinements to my dissertation based on detailed supervisor feedback, strengthening the clarity, analysis and connection between my implementation and research findings.


# References
