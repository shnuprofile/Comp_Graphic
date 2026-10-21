# Computational Graphics and Visualization — Project Reflection

## 1. How Do I Approach Designing Software?

### What new design skills has your work on the project helped you to craft?
Building the 3D scene improved my ability to turn a visual concept into an organized software design. I stopped treating the scene as a single monolithic object and started decomposing it into separate shapes, transforms, materials, textures, and lighting needs. I developed stronger spatial reasoning about how coordinates, scale, rotation, and camera placement shape the final output. Working in OpenGL forced me to care about both correctness and whether objects looked proportional and recognizable.

### What design process did you follow for your project work? 
I began by listing the objects I wanted to depict and choosing the basic 3D primitives that could build them. I then mapped out their positions and proportions and worked through the scene in small, manageable pieces. After the geometry was in place, I improved the look with transforms, materials, textures, lighting, and camera tweaks. After each significant change I reviewed the rendered result against my intended design to spot areas for improvement.

### How could tactics from your design approach be applied in future work? 
Decomposing a complex visual problem into smaller reusable parts is a strategy that transfers to almost any software project. Planning architecture up front, separating concerns, and checking design decisions early reduces rework. The same ideas apply to full-stack apps, data visualization tools, and AI systems, where clear design makes complex features easier to build, test, and maintain.

## 2. How Do I Approach Developing Programs?
### What new development strategies did you use while working on your 3D scene? 
The scene introduced visual debugging. Beyond compile and runtime errors, I had to examine what OpenGL actually drew and trace unexpected results to geometry, transforms, camera settings, textures, or lighting. I also built objects from simpler primitives and made focused changes to isolate issues. This reinforced modular code and a deliberate troubleshooting approach.

### How did iteration factor into your development? Iteration drove the project. 
Each milestone let me add functionality, run the app, inspect the scene, and refine it. Tiny tweaks to placement, scale, color, lighting, or camera motion could dramatically change appearance. Frequent testing caught problems early and made it easier to understand the impact of individual changes.

### How has your approach to developing code evolved throughout the milestones, which led you to the project’s completion?
Initially I focused on getting individual objects to appear correctly. Over time I became more deliberate about how components fit together into a cohesive scene, treating geometry, rendering, lighting, and interaction as interconnected parts of a larger system. My workflow shifted toward smaller verifiable changes, consistent testing, and incremental refinement. By the final milestone I could diagnose visual problems systematically and balance functional code with presentation quality.

## 3. How Can Computer Science Help Me in Reaching My Goals?
### How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future educational pathway? 
Computational graphics connected programming, math, and software design. Working with 3D coordinates, transformations, and rendering showed how mathematical ideas become practical applications. It also expanded my C++ and graphics API experience with a problem-solving mindset different from web development. These skills will support future courses and projects on algorithms, simulations, interactive interfaces, and data visualization.

### How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future professional pathway? 
My professional aim is to grow as a software engineer toward AI and machine learning. Even if I don’t do graphics programming directly, the ability to visualize complex information is valuable. I can apply these lessons to dashboards, interactive analytics, simulations, and tools that explain model outputs or large datasets. The project strengthened transferable engineering skills — decomposition, debugging, iterative development, and user experience focus — and showed that strong software development means creating systems that communicate clearly and work as intended.
