# CS330
Comp Graphic and Visualization 

Approach to Designing Software
How do I approach designing software?
I began by outlining the project requirements: creating a 3D scene with a teddy bear and candy elements. I broke the project into components (teddy bear, environment, lighting, camera) and prioritized foundational elements first (e.g., OpenGL setup, mesh loading). This modular approach allowed me to tackle complexity incrementally.

New Design Skills Crafted

Modular Design: Created reusable functions like CreateGLTexture() and SetTransformations(), reducing redundancy.

Resource Management: Reused meshes (spheres, cylinders) for multiple objects (teddy bear limbs, candy elements).

Lighting and Material Systems: Defined OBJECT_MATERIAL structs to manage surface properties (e.g., fur vs. glossy candy).

Design Process Followed
An iterative, agile-like process:

Milestone 1: Basic scene setup (meshes, camera).

Milestone 2: Texture loading and transformations.

Milestone 3: Lighting and material integration.
Each phase involved testing and refinement, such as adjusting UV scaling for textures.

Future Application of Design Tactics

Modularity: Separating texture handling from rendering logic can streamline future projects.

Iteration: Incremental testing (e.g., tweaking camera FOV) ensures robustness in complex systems like VR applications.

Approach to Developing Programs
Development Strategies

Object-Oriented Practices: Encapsulated texture loading and material management.

Leveraging Libraries: Used GLM for matrix math and stb_image for texture loading.

Version Control: Git tracked changes, enabling safe experimentation (e.g., testing blending modes).

Role of Iteration
Iteration was critical for refining:

Camera Controls: Adjusted mouse sensitivity for smoother navigation.

Texture Mapping: Tuned SetTextureUVScale() values to avoid stretching on curved surfaces.

Evolution of Coding Approach
Transitioned from linear scripting to modular code:

Early Milestones: Monolithic code for rendering.

Later Milestones: Organized into PrepareScene() (asset loading) and RenderScene() (drawing), simplifying debugging.

Role of Computer Science and Future Applications
How CS Helps Achieve Goals
CS fosters problem-solving (debugging lighting issues) and systematic thinking (optimizing OpenGL’s state machine). These skills are vital in fields like game development or data science.

Educational Pathway Applications

Graphics Pipelines: Understanding matrices and shaders aids in advanced courses (e.g., GPU programming).

3D Math: Vector/matrix operations are foundational for simulations or machine learning.

Professional Pathway Applications

Industry Demand: Skills in OpenGL and real-time rendering are sought in gaming, AR/VR, and architectural visualization.

Emerging Tech: Expertise in optimization (e.g., texture memory management) is crucial for metaverse platforms.

Examples from the Project
Challenge: Debugging alpha blending for the river texture.
Solution: Switched to PNGs with transparency and enabled glBlendFunc(), reinforcing attention to asset preparation.

Skill Growth: Learning OpenGL’s state machine improved my ability to manage low-level APIs, a key skill for engine development.

Conclusion
This project honed technical skills (texturing, lighting) and soft skills (iteration, modular design). These experiences directly align with industry trends like VR and real-time rendering, positioning me to contribute to cutting-edge fields in both education and industry.
