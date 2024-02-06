# Extra
## This Repo
- **README.md**: Lots of helpful info (this page).
- **Unity Project - Completed DLOD Tutorial**: The completed tutorial from week 3 (just excluding the large monkey mesh due to its high file size).
- **Unity Project - Performance UI**: A part of the [Catlike Coding - Measuring Performance](https://catlikecoding.com/unity/tutorials/basics/measuring-performance/) tutorial that includes an FPS and frame duration UI.

## Techniques and Profiling Tools Taught
Use this to locate where we discussed optimisation techniques and measurement tools.

### Week 1 - [01-Measuring-Game-Engine-Performance](https://github.com/danmilneusw/01-Measuring-Game-Engine-Performance)
**Optimisation Techniques:**
- Time Slicing: Can be used in a range of scenarios (like seen in the demo Unity project), including AI (like Behavior Trees, pathfinding algorithms, perception systems), animations, and general systems like check mechanisms, such as checking player position for event triggering
- Using a predictive system instead of a collision detection system

**Measurement Tools:**
- The Unity Profiler (Timeline view, Hierarchy view, CPU Usage Module)
- Profile Analyzer (used for comparing two profile recordings)

### Week 2 - [02-Audio](https://github.com/danmilneusw/02-Audio)
**Optimisation Techniques:**
- Audio management (streaming from disk)
- Audio compression (Using OGG Vorbis and Nyquist-shannon)
- Audio culling (reducing the total number of voices and setting priorities)
- Synthetic audio generation (in our example we made a clip of lots of footsteps a single footstep and added random pitch and volume variation)

**Measurement Tools:**
- Unity Profiler - Audio Module

### Week 3 - [03-Level-of-Detail](https://github.com/danmilneusw/03-Level-of-Detail)
**Optimisation Techniques:**
- General LOD (the material discusses texture compression as a General LOD example)
- Discrete LOD
- Continuous LOD (aside from mentioning Nanite, we didn't discuss this, but it is fairly similar to DLOD)
- LOD - Fog (also works for other view-blocking elements)

**Measurement tools:**
- Unity Profiler - GPU Usage Module
- Unity Memory Profiler
- Profiling a build

### Week 4 - [04-Draw-Calls](https://github.com/danmilneusw/04-Draw-Calls)
**Optimisation Techniques:**
- GPU Instancing
- Occlusion Culling

**Measurement tools:**
- Frame Debugger
- Overdraw Detector

### Week 5 - [05-Garbage-Collection](https://github.com/danmilneusw/05-Garbage-Collection)
**Optimisation Techniques:**
- Object Pooling for GC Allocation reduction

**Measurement tools:**
- Unity Profiler (again)

## Assessment 1 Tips
- You don’t have to use like-for-like examples we covered in these sessions, you can make up your own too, time slicing is fairly generalisable for example.

- You should say why you are using these techniques. You must show your understanding of the optimisation technique. What is the theory behind it? Before you implement it, explain why it should improve your project.

- Profile in the editor for quick fixes, but you will get the best marks if you optimise using the build tool at the end of each section.

- A few of these techniques you may find are so simple that you may want to group them together in the report. Also, you can consider having a general optimisations section, for a group of more obvious or straightforward techniques, like removing console print statements. Although consider that it might not be worth prioritising this section, as it will probably give you less opportunity to discuss theory, which means less chance to gain marks.

- You can also research your own optimisation techniques and profiling tools.

- The starred links in the Extra Resources part of each repository are certainly worth checking out.

- Duplicate the intitial version of your project before making any changes. Once you have implemented one technique, then duplicate that and implement a second technique into the duplicate. Repeat this process so you can easily monitor the progress you make; you can easily go back to previous versions to take in-game or profiling screenshots. This would also be useful for a future portfolio (read below).

## Advice for Outside of the Module
Both assessments are designed so that you have something you can showcase as part of your portfolio. Once the module is over, I'd recommend you use your GitHub to store a portfolio (or setup a new one if you want a fresh slate) that contains your project at different levels of optimisation and the report too. The assessment is a report as this is what a client or your team might request of you. GitHub is great as there's no costs to it, unlike a website, and it's easily navigable and understandable by game dev professionals. Like the front page of [github.com/danmilneusw](github.com/danmilneusw), you can show a markdown file that has links to all of your repositories and put what you value most highly at the top. I can help you set this up if you'd like or show you my personal GitHub for some ideas, although mine is Machine Learning focused currently (please ask in-class and I can show you).

## Game Dev Resources
These are some resources I have used, highly recommend and think you'll find interesting:
- [Catlike Coding](https://catlikecoding.com/unity/tutorials/) - Excellent Unity tutorials from someone who is clearly an industry professional. Includes basic to more advanced tutorials.
- [Acerola](https://www.youtube.com/@Acerola_t) - Entertaining and educational graphics programming and general game development YouTube channel.

Acerola has recently announced a new game jam. Unlike other game jams it runs for two weeks (so no stressful 48 hour time limits) and is intended for individuals (so you're not disadvantaged by difference in team sizes). You can learn more in his [YouTube video](https://youtu.be/uqI9EoAWeUE?si=tj7oBPkEfZ6_aO0T). I will be taking part😁. It starts on February 28th.
