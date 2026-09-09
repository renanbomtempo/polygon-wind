# Polygon Wind Shader
In 2017 I was looking for a wind shader to use on a low poly tree model. I couldn't find one that provided the visual I was looking for, so I started to develop the Polygon Wind Shader. 

It is designed to generate a more suttle and organic wind movement on trees. But it's not great for heavy wind effects.
**Lately I haven't had much time to work on it, so I decided to publish the source code here and make it available so that anyone can use and modify it.**

Here are some videos of what I achieved using it:

### [Using on individual model](https://youtu.be/nG-dmBiyHXc)

https://github.com/user-attachments/assets/fdd2befc-0be3-472e-bc42-8e3417b668dd

### [Using on a Unity Terrain](https://youtu.be/CGLFoZXgCKA)

https://github.com/user-attachments/assets/f6c2d1b5-8de8-4bc4-a9c1-dbd24872b000

## How to use it:

Just apply the shader to a material and apply the material to your asset. The ideal tree asset is one with a single mesh.

The shader has various parameters for you to tweak:
  - Wind Wave Size;
  - Tree Sway Displacement;
  - Foliage Wiggle Amount;
  - Branches Up/Down;
  - Foliage Wiggle Speed;
  - Tree Sway Stutter;
  - Tree Sway Speed;
  - Wind Direction;
  - Red Vertex Influence;
  - Blue Vertex Influence.
  
It uses a series of inputs to calculate the final vertex position, one of them being the vertices colors of the mesh:

  - Red - Use on the branches to enable the up/down movement;
  - Blue - Use it on the leaves to get that organic wiggle.

# Known applications using the shader
### Star Wars Galaxies' Mod.
This shader was used by Borrie BoBaka to make the mod [**Borrie's Swaying Trees**](https://modthegalaxy.com/index.php?resources/borries-swaying-trees.72/)
<img width="461" height="327" alt="compressed_polygon_wind-starwars3" src="https://github.com/user-attachments/assets/d3f180c1-0d66-416c-a3f8-c325aa91b73f" />
<img width="457" height="332" alt="compressed_polygon_wind-starwars2" src="https://github.com/user-attachments/assets/0f9c1771-3b74-409a-8337-0f330f60bec5" />
<img width="455" height="331" alt="compressed_polygon_wind-starwars" src="https://github.com/user-attachments/assets/ba60ba2f-88df-4d61-beeb-52e7183be213" />

### Master's Thesis on VR
I also discovered that PolygonWind was used by students Malte Lindholm Hølledig and Rikke Katrine Petersen on their master's thesis [**ZenVR: A biofeedback virtual reality experience for assisting meditation**](https://projekter.aau.dk/projekter/files/281492006/zenvr.pdf) at Aalborg University.
<img width="1191" height="1170" alt="image" src="https://github.com/user-attachments/assets/734054e6-d117-442d-9421-3ef2eaade354" />


