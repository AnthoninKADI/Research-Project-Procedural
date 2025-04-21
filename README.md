# <ins>__Introduction__:</ins>

In this research project, I will explore procedural level generation, starting with the creation of a grid system using randomly assigned colors to simulate diverse zones. This first step will help me experiment with visual variety and spatial layout. Then, I will move on to generating procedural mazes, which will introduce structure and navigation challenges. Finally, I aim to combine these systems with biome management to generate coherent environments with distinct visual and gameplay characteristics.

The goal of this project is to design a flexible system that can generate structured and varied levels through procedural techniques and biome logic.
<br>
<br>
<br>
# <ins>__State of the Art__:</ins>

<ins>__Existing Solutions and Projects__:</ins>

Games like Minecraft or Terraria integrate biome systems to enhance variety and immersion in their worlds.

These systems often combine noise functions (e.g. Perlin Noise) with rule-based logic to create distinct zones.
<br>
<br>
<br>
<ins>__Technologies Commonly Used__:</ins>

Level generation techniques often use tools like Wave Function Collapse, Cellular Automata or more for layout generation.

Biome assignment is typically managed by analyzing environmental parameters such as temperature, humidity, or altitude.

These systems aim to create organic transitions between biomes while maintaining gameplay coherence.
<br>
<br>
<br>

# <ins>__Approach__:</ins>

<ins>__Personal Testing and Learning Phase__:</ins>

Before using more advanced tools, I built a basic grid system where each cell was assigned a random color.

This helped me experiment with visual variety, neighborhood checking, and tile-based logic.
<br>
<br>
As an initial experiment, I implemented a simple maze generator to better understand procedural techniques.

While not used in the final version, it helped me explore algorithm basics such as recursive backtracking and grid manipulation.
<br>
<br>
<br>
<ins>__Tools Used in the Final Version__:</ins>

For the final level generation system, I use the PCG Biome plugin, which provides advanced biome generation logic.

This tool allows for efficient management of terrain types, blending rules, and biome-specific parameters.

It serves as the foundation upon which I build my custom features and experimentation.
<br>
<br>
<br>
# <ins>__Analysis__:</ins>

<ins>__Initial Challenges and Learning Curve__:</ins>

At the beginning, I faced difficulties with grid generation logic and the coordinate systems.

I had to learn how to use noise functions, how to structure grid data and how to manage randomness in a controlled way.

![[Uploading Menu_Image.PNG…]()](https://raw.githubusercontent.com/AnthoninKADI/Research-Project-Procedural/refs/heads/main/BPGrid.PNG)

![[Uploading Menu_Image.PNG…]()](https://raw.githubusercontent.com/AnthoninKADI/Research-Project-Procedural/refs/heads/main/GridGenerator.PNG)
<br>
<br>


This simple snippet helped me start visualizing the base for biome zones, even if they were randomly placed at first.
<br>
<br>

<ins>__Testing Concepts — Maze and Colored Grid__:</ins>

I created a maze generator using recursive backtracking to better understand spatial constraints and connectivity.

Even though I didn't use the maze for the final implementation, it taught me how to structure data in a 2D space and handle recursive algorithms.

![[Uploading Menu_Image.PNG…]()](https://raw.githubusercontent.com/AnthoninKADI/Research-Project-Procedural/refs/heads/main/MazeGenerator.PNG)
<br>
<br>

<ins>__Implementing PCG Biomer Plugin__:</ins>

The biggest step was integrating the PCG Biome plugin. At first, it was challenging to understand how it handles layers and biome distribution because i never use it before.

I had to dig into its documentation and experiment with blending settings to get satisfying results.

![[Uploading Menu_Image.PNG…]()](https://raw.githubusercontent.com/AnthoninKADI/Research-Project-Procedural/refs/heads/main/BiomeColorMap.png)
<br>
<br>

![[Uploading Menu_Image.PNG…]()](https://raw.githubusercontent.com/AnthoninKADI/Research-Project-Procedural/refs/heads/main/ProcedBiomeColor.PNG)
<br>
<br>

![[Uploading Menu_Image.PNG…]()](https://raw.githubusercontent.com/AnthoninKADI/Research-Project-Procedural/refs/heads/main/ProcedBiomeEdit.PNG)
<br>
<br>

![[Uploading Menu_Image.PNG…]()](https://raw.githubusercontent.com/AnthoninKADI/Research-Project-Procedural/refs/heads/main/ProcedBiomePlay.PNG)
<br>
<br>

<ins>__Successes and Failures Along the Way__:</ins>

✅ <ins>Success:</ins> Once I understood how to manipulate the input parameters of PCG Biome like the noise scales, seed values or the biome placement with the color, I was able to generate visually distinct zones.

❌ <ins>Failure:</ins> I initially tried to combine my old maze logic with biome generation, but it created inconsistencies and rigid layouts that didn’t feel natural.

Rollback: I decided to abandon that approach and fully embrace the node-based logic from PCG Biome instead.
<br>
<br>

<ins>__Outcome and Reflection__:</ins>

The implementation now allows me to create levels with clearly separated biomes, each with its own aesthetic and rules.

The process taught me a lot about procedural logic, data structuring, and tool integration in a game engine context.  
<br>
<br>

 # <ins>__Bibliography__:</ins>

 - Minecraft Generation Explanation | [Minecraft Wiki](https://fr.minecraft.wiki/w/G%C3%A9n%C3%A9ration_du_monde)
   
 - PCG Biome Reference | [Unreal Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/procedural-content-generation-pcg-biome-core-and-sample-plugins-reference-guide-in-unreal-engine)
   
 - PCG Biome Quick Start | [Unreal Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/procedural-content-generation-pcg-biome-core-and-sample-plugins-quick-start-guide-in-unreal-engine)

 - PCG Framework Node Reference | [Unreal Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/procedural-content-generation-framework-node-reference-in-unreal-engine)

 - PCG Overview | [Unreal Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/procedural-content-generation-overview)
   
 - Base Landscape Generation | [Unreal Documentation](https://dev.epicgames.com/documentation/fr-fr/unreal-engine/creating-landscapes-in-unreal-engine)
   
 - Procedural Content Generation Base Video | [Youtube](https://www.youtube.com/watch?v=jMdHOKJuOiA)
<br>
<br>
<br>

   

