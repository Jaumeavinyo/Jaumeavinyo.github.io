# Jaume Avinyo: Gameplay Programmer & Technical Designer


<img src="/images/YO.jpg" alt="Profile Picture" width="200">

I am a gameplay and animation programmer specializing in creating responsive, character-driven systems. My passion lies at the intersection of movement, combat, and animation—crafting the moment-to-moment feel that defines a game's identity.

I recently completed my Master's in Game Design, focusing my expertise on advanced animation systems and character control. My portfolio showcases this through projects like a full Souls-like combat framework in Unreal Engine 5 and a movement-based magic system prototype.

I thrive on technical challenges that directly shape player experience: implementing data-driven animation graphs and motion-matching systems, designing physics-informed movement, and building animation state machines that are both powerful and designer-friendly. My technical toolkit includes C++, C#, Unreal Engine 5, Unity, and expertise in 3D content pipelines (Maya/3DS Max, ZBrush, Substance).

My background includes production experience on a VR title, giving me a keen understanding of full development pipelines.

I am actively seeking a gameplay or animation programming role where I can contribute my technical skills and design sensibility to a team passionate about character control and game feel.

## Profesional Experience

### Hexomancer (public project)
- **Description**: Full Time Producer.
- **Technologies**: Unity, Notion, HackNPlan
- **Features**: VR Singleplayer game. Mix between crafting your troops in a laboratory and making them fight in an autobatler type combat where you help them with potions and magic habilities
[Game trailer coming soon](https://www.youtube.com/watch?v=tlbSwPsO1Ss&t=1s&ab_channel=Hexomancer)
[![Game Preview](/images/hexomancer.jpg)](https://www.youtube.com/watch?v=tlbSwPsO1Ss&t=1s&ab_channel=Hexomancer){: width="50%"}
---

## 💻 Personal Projects

### Souls like combat system UE 5.4
Video 1: Combat system https://youtu.be/ZePPMSU4fWk
- **Weapon-Dependent Animation System**
Engineered combat around weapon Actors in UE5.4, enabling dynamic weapon spawning for enemies and data-driven animation definition via structs (S_AttackAnims), separating logic from the character for scalability.
- **Combo system**
 Implemented a responsive combo system driven by character state and a timing-based input buffer, designed intentionally without priority to maintain high-stakes, commitment-based gameplay.
- **Camera targetting**
Built a camera targeting system using dot-product for centered enemy selection, with smooth switching between targets and automatic break conditions to keep combat focused and readable.

[![Game Preview](/images/CameraLockSystem.gif)](https://youtu.be/ZePPMSU4fWk){: width="50%"}

- **AI & Feedback**
Developed reusable enemy AI with Behavior Trees, incorporating physics-based directional hit reactions and anim-notify-controlled attack commitment to create fair, telegraphed enemy behaviors.

[![Game Preview](/images/HitReactions.gif)](https://youtu.be/ZePPMSU4fWk){: width="50%"}
[![Game Preview](/images/Feedback.gif)](https://youtu.be/ZePPMSU4fWk){: width="50%"}

Video 2: Boss fight WIP https://youtu.be/RqMU2L2y1io
- **Spline-Based Patrol & AI State Machine**
  Implemented a modular patrol system where the boss autonomously navigates along a user-defined spline path in the game world, providing a dynamic and customizable setup phase for the encounter. Architected a multi-phase AI state machine (Patrol -> Investigate -> Combat) to create a structured and dramatic boss introduction, controlling distinct behaviors and animations for each phase.
- **Progressive Player Detection**
  Designed an "Investigate" state triggered by player proximity, where the boss ceases patrolling, focuses on the player, and begins a cautious approach, building tension before combat initiation. Programmed a threshold-based combat trigger, where reaching a specific distance prompts a distinctive scream animation, formally signaling the transition to the combat phase and enhancing narrative pacing.
- **Dynamic Combat Behaviors**
  Created a chase-and-attack combat loop with unique "unblockable" attack properties, enforcing specific player responses like dodging, and increasing the encounter's difficulty. Prototyped a responsive damage-reaction system where the boss actively creates space by jumping backward (currently a teleport placeholder) upon taking significant damage, preventing player stun-locking and forcing engagement re-evaluation.
  
[![Game Preview](/images/BossWIP.gif)](https://youtu.be/RqMU2L2y1io){: width="50%"}
[![Game Preview](/images/BossBT_WIP.gif)](https://youtu.be/RqMU2L2y1io){: width="50%"}

### MistBorn Game Prototype 
- **Description**: Movement based third person game prototype in wich i'm adapting the book's magic system to a videogame. C++ gameplay programming, design and level design. 
- **Technologies**: Unreal Engine 5.4, C++, Motion Matching, ABP state machines
- **Features**: Custom modular Ability system, Camera system, Ability design, movement design, level design.
- Code:
  - Relevant code in: UAllomanticAbility.cpp,PullAbility.cpp, AllomancyComponent.cpp
  - Code base here: [Github project](https://github.com/Jaumeavinyo/MB_Project/tree/b91dc1833abdbc8efff48860ad8ef2c4875e101b/MB_Project/Source/MB_Project)
  
[![Game Preview](/images/MotionMatching2.gif)](https://youtu.be/Ta7l_7wt_lU){: width="50%"}
[![Game Preview](/images/MistBornLevelGif.gif)](https://youtu.be/NfB75_VGf1M){: width="50%"}
[![Game Preview](/images/MistBornPlayGroundGif.gif)](https://youtu.be/rH3wEdMCtkY){: width="50%"}
  
### 3D Shader
- **Description**: Explores shader mathematics with ray intersections to render 3D shapes, hard shadows, and reflections and refractions in real-time.
- **Technologies**: ShaderToy, GLSL
- **Features**: 3D ray intersections, ambient/diffuse/specular lighting, hard shadows, reflections, refractions and distance fog.
- [View the Shader](https://www.shadertoy.com/view/DdV3Dz)
[![Shader Preview](/images/ShaderGif.gif)](https://www.shadertoy.com/view/DdV3Dz){: width="50%"}

### 2D Character Movement, Attack System and enemy AI
- **Description**: A Unity project showcasing character movement and attack systems, AI enemy with FSM-driven state management.
- **Technologies**: Unity, C#
- **Features**: Finite State Machine for character and enemy states, camera movement, parallax backgrounds and fight collision system. Everything done in C#, no use of Unity Build in tools for this prototype
- [Watch Demo](https://youtu.be/xEKoS6ZLFqs)

[![FSM Character Preview](/images/fightPrototype.gif)](https://youtu.be/xEKoS6ZLFqs){: width="50%"}

---

## 🏫 Student Projects

### Myrmica
- **Description**: Done in Unreal Engine, Myrmica is an investigation and puzzle game with an isometric camera where you explore a petrol station while being chased by a time anomaly. To achieve this, manipulate the routine of 5 characters for your needs and create your situations on a time loop. And discover the truth of Complex B13B
- **Role**: Designer, Gameplay and animations programmer, producer.
- **Technologies**: Unreal Engine 5
- [Watch the Video](https://www.youtube.com/watch?v=ShOjy29skAk) | [Visit Studio LinkedIn page](https://www.linkedin.com/company/paranoia-studios/posts/?feedView=all)

[![Myrmica preview](/images/MyrmicaGif.gif)](https://www.youtube.com/watch?v=ShOjy29skAk){: width="50%"}

### The Witcher: Ties of Destiny
- **Description**: A four-month project developed by a team of 20 students using a custom C++ OpenGL engine.
- **Role**: Designer and Gameplay Programmer
- **Technologies**: Our own c++ game engine, lua
- [Watch the Video](https://www.youtube.com/watch?v=m5PS3PCTRs0) | [Visit the Website](https://tiesofdestiny.com/)

[![Ties of Destiny Preview](/images/GifWitcher.gif)](https://www.youtube.com/watch?v=m5PS3PCTRs0){: width="50%"}

### Mercury Engine
- **Description**: A 3D game engine with importing, animation playback, and real-time rendering capabilities, developed in four months from scratch.
- **Technologies**: C++, OpenGL, SDL, DeviL, Assimp, ImGui
- **Features**: Importing and rendering of FBX models, file system, camera culling, and skeletal animation support.
- [Watch the Video](https://www.youtube.com/watch?v=qAw3V35vyvA) | [GitHub Repository](https://github.com/knela96/Mercury-Engine)

[![Mercury Engine Preview](/images/mercuryengine.png)](https://www.youtube.com/watch?v=qAw3V35vyvA){: width="50%"}

### Order 227: Not a Step Back
- **Description**: A only c++ RTS game developed by a seven-member team using SDL. I served as C++ programmer and team manager, overseeing gameplay mechanics and strategic decisions.
- [Watch the Video](https://www.youtube.com/watch?v=2uebz2vIlOg) | [GitHub Repository](https://cutt.ly/Dh0o84m)

[![Order 227 Preview](/images/Order227Gif.gif)](https://www.youtube.com/watch?v=2uebz2vIlOg){: width="50%"}

### Almost Hero
- **Description**: A only C++ rhythm game inspired by Guitar Hero, completed in three weeks.
- [Watch the Video](https://youtu.be/vuUG-xygVik) | [GitHub Repository](https://cutt.ly/8h0o4MY)

[![Almost Hero Preview](/images/AlmostHeroGif.gif)](https://youtu.be/vuUG-xygVik){: width="50%"}

### Last Resort
- **Description**: A only C++ recreation of a level from NeoGeo’s "Last Resort," completed with a team of three.
- [Watch the Video](https://cutt.ly/2h0o5U4) | [GitHub Repository](https://cutt.ly/Dh0pqJL)

[![Last Resort Preview](/images/LastResortGif.gif)](https://cutt.ly/2h0o5U4){: width="50%"}

### Easy Neural Networks
- **Description**: A prototype tool enabling to create a neural network from scratch to understand its internal functioning
- **Technologies**: C++ (prototype stage)
- [Watch the Video](https://www.youtube.com/watch?v=vVJ6H56kYGs)

[![Easy Neural Networks Preview](/images/Screenshot_1.png)](https://www.youtube.com/watch?v=vVJ6H56kYGs){: width="50%"}

---

## 🎮 Game Jam Projects

### Project Rebirth
- **Description**: A resource management game developed in a 24-hour game jam. Players balance production and pollution to gain resources without damaging planets.
- [Watch the Promo Video](https://www.youtube.com/watch?v=ZdIgT6x-kOo&t=75s&ab_channel=RogerLeonBorras) | [Play on Itch.io](https://lostsignalstudio.itch.io/project-rebirth)

[![Project Rebirth Preview](/images/ProjectRebirth.png)](https://www.youtube.com/watch?v=ZdIgT6x-kOo&t=75s&ab_channel=RogerLeonBorras){: width="50%"}

---


## 🛠 Skills

**Programmer and Game Designer**

- **Programming Languages**: C++, C#, Lua
- **Game Engines**: Unity, Unreal engine 5, Custom-built 2D/3D engines
- **3D software**: Pipeline workflow and basic use knowledge about 3DStudio Max, Maya, ZBrush and substance painter


---

## 💼 Work Experience
- **Junior Producer** Pandora's Box VR studio
  -  VR strategy and crafting game
- **Quality Assurance Intern** - [Cirsa](https://www.cirsa.com/) (June 2019 - September 2019)
  - Industry leader in Spain's gaming and betting sector.
  
- **Customer Service & Computer Repair Technician** - [OfertasPC](https://www.ofertaspc.com/) (January 2020 - September 2022)
- **Producer**
- Producer at Pandora's Box, indie company developing VR games. 
---

## 📘 Education
- **Master's Degree in Video Game Design**  
  - U-Tad, Madrid (2023 – 2024) 
    
- **Bachelor's Degree in Video Game Programming**  
  - CITM/UPC, Barcelona (2017 – 2021) – Degree in English
  
- **Scientific Bachillerato**  
  - Institut Pare Manyanet, Les Corts, Barcelona (2015 – 2017)

- **Language Studies**  
  - Cambridge (England),
  - International School of Languages in San Diego (USA)
  - Aston School (Barcelona)

---

## 📫 Contact: Jaume, Barcelona, Spain
- **Phone**: +34 671507035
- **Email**: [jaume.avinyo.sedano@hotmail.com](mailto:jaume.avinyo.sedano@hotmail.com)
- **LinkedIn**: [LinkedIn Profile](https://linkedin.com/in/jaume-avinyó-sedano-b13b17183)
- **GitHub**: [GitHub Profile](https://github.com/Jaumeavinyo)

---
