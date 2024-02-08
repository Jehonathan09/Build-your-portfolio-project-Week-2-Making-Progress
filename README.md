# Build-your-portfolio-project-Week-2-Making-Progress

## Progress:
Rating 7/10

This week, progress has been made across various aspects of the project. I successfully implemented some features and conducted productive testing sessions. However, some unexpected complexities arose during digital differential analysis algorithm implementation, requiring additional time for refinement. 

### Completed as Planned:

> Maze Generation Algorithm Enhancement: The dynamic difficulty system has been successfully integrated, allowing for the generation of mazes.

> Incomplete Aspects:
>> - Parser
>> - Map
>> - Enemies 

## Challenges:

### Technical Challenge:
Optimizing a game to fit different screen sizes while managing computer memory efficiently involves several technical changes and considerations:

Responsive Design: Implementing a responsive design approach ensures that the game adapts seamlessly to various screen sizes without compromising usability or visual quality. This involves using flexible layout grids, relative sizing units (such as percentages or ems), and media queries to adjust the game's layout and content dynamically based on the device's screen size.

 - Dynamic Asset Loading: Instead of loading all game assets (such as images, sounds, and scripts) upfront, a dynamic asset loading mechanism can load resources on demand based on the user's interactions or current game state. This helps conserve memory by only loading assets when needed, reducing the initial memory footprint of the game.

- Texture Compression: Utilizing texture compression techniques reduces the memory footprint of graphical assets without sacrificing visual quality. Compressed textures consume less memory and load faster, making them ideal for mobile devices with limited resources. Techniques like texture atlasing and mipmapping can further optimize memory usage by consolidating textures and reducing redundant data.

- Memory Management: Implementing efficient memory management techniques, such as object pooling and garbage collection optimisation, helps minimize memory fragmentation and prevents memory leaks. Object pooling reuses game objects instead of instantiating and destroying them repeatedly, reducing memory overhead. Garbage collection optimization ensures timely release of unused memory to prevent memory bloat.

- Level of Detail (LOD) Optimization: Incorporating LOD optimization techniques for 3D models and environments dynamically adjusts the level of detail based on the player's distance from objects. This helps reduce the number of polygons rendered on screen, thereby conserving memory and improving performance, particularly on devices with lower processing power.

- Code Optimization: Optimizing game code for performance and memory usage involves identifying and eliminating bottlenecks, unnecessary computations, and memory-intensive operations. Techniques like code refactoring, data structure optimization, and algorithmic improvements can significantly reduce memory usage and improve overall game performance.

### Non-Technical Challenge:

The most difficult non-technical challenge faced in the second week was fully comprehending the raycasting tutorial and SDL2 tutor.  To overcome these non-technical challenges, I went back to the tutorial and used other external resources to understand the Digital Differential Analysis algorithm.

Screenshots



