# Practical 3.2: Narrative Environments
You will notice that in this repository I have provided a prebuilt indoor environment with a controllable FPS character. The asset files also include some objects and various textures and materials. You can choose to use the prebuilt environment or your environment that you built in Tuesday’s practical. You may wish to copy over the provided objects and textures to your project. 

**Your goal for this practical is to come up with a narrative and then make the environment communicate this narrative through use of props, textures, decals etc.** 

## Task 1: Narrative
Take some time to think of a narrative that you want the player to experience. This does not have to be too complete or too detailed! It can be as simple as the scenario that I gave you in the last practical. Consider the following questions: 

- What’s the story?
- Where do we start?
- Where do we finish?
- What happens and where?
- How tight is the structure? 

While you may be able to rely on some text at the start of your experience, the environment should be able to set the scene and provide players with enough information about the narrative as it unfolds. 

## Task 2: Objects
Once you have a narrative, start off by placing objects in the indoor environment. You can use the objects provided to you, find other assets on the Unity Store or make your own. 

You can find a set of furniture objects in this repository (Assets > Models > Furniture). *Note, you will have to unpack the furniture prefab if you want to use individual pieces.* 

Consider how to lay out the space so that it’s both convincing and interesting to explore. 

## Task 3: Textures
Next, think of the textures and colouring of both the objects in the space and the corridors and rooms. You will find a set of textures that you can use to add detail to the objects in your scene. New materials can be created by going to Assets > Create > Material. You can then apply different textures or colours to your materials. 

As with the objects you can use the textures provided to you, find texture packs on the Unity store, or make your own. 

## Task 4: Test it out!
Ask the person next to you or one of the teaching team to walk/play through your environment. They should be able to figure out most of the narrative from their playthrough alone. 

## Optional extensions:

- Decals: Decals allow you to add detail to environments, planes called decals can be added to walls and floors, to add features such as cracks, dirt, stains or graffiti. To make a decal:
  - Make a PNG or TGA in Photoshop with a clear background. 
  - Import it as a texture into Unity
  - Make sure it is marked as alpha transparent (select in the asset window and check its properties in the inspector.
  - Make a material that supports alpha transparency: experiment with different materials from Unity’s built in shaders. 
  - Make a quad object (GameObject>3D Objects>Quad) and apply the material to it.
  - Move that object until it’s flat on the floor or against walls.
  - You can also find premade decals in the Unity store.
- Motion: Using some of the simple scripting techniques taught in previous weeks. Can you add some simple motion to objects to further communicate your narrative? 
- Extend the narrative to include an outdoor scene. You can import your indoor environment to previous terrain practicals or create a new outdoor scene to follow your narrative plan. 


