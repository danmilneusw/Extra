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
**Measurement tools:**
- Unity Profiler - GPU Usage Module
- Unity Memory Profiler
- Profiling a build

**Optimisation Techniques:**
- General LOD (the material discusses texture compression as a General LOD example)
- Discrete LOD
- Continuous LOD (aside from mentioning Nanite, we didn't discuss this, but it is fairly similar to DLOD)
- LOD - Fog (also works for other view-blocking elements)


### Week 4 - [04-Draw-Calls](https://github.com/danmilneusw/04-Draw-Calls)
**Measurement tools:**
- Frame Debugger
- Overdraw Detector

**Optimisation Techniques:**
- GPU Instancing
- Occlusion Culling

## Tips
- You don’t have to use like-for-like examples we covered in these sessions, you can make up your own too, time slicing is fairly generalisable for example.

- You should say why you are using these techniques. You must show your understanding of the optimisation technique. What is the theory behind it? Why would it improve your project?

- Profile in the editor for quick fixes, but you will get the best marks for optimising the build too at the end of each section.

- A few of these techniques you may find are so simple that you may want to group them together in the report. Also, you can consider having a general optimisations section, for a group of more obvious or straightforward techniques, like removing console print statements. Although consider that it might not be worth prioritising this section, as it will probably give you less opportunity to discuss theory, which less chance to gain marks.

- You can also research your own optimisation techniques and profiling tools.

- The starred links in the Extra Resources part of each repository are certainly worth checking out.
