# Template for Godot4
This is a template for developing games in Godot 4 as well as learning more about the Engine itself.

### Usage
To use this project you would have to have installed a dependencies.
+ Godot Mono 4.0+ - The engine that this is developed on
+ .NET Core 6.0+ / Mono - Might include C# code in the future(Is required for godot-mono)
+ Git w/ LFS - Git with LFS(Large File Support) since it uses LFS for storing assets
+ *Linux w/ GLibC - Non standard distribution such as void would not work as the physics engine requires GLibC.*

Then you can start working by with these commands(If on Windows then use powershell and have git installed)
```bash
git lfs clone https://github.com/OpenNullanoid/godot4-template1.git
cd godot4-template1
export MANGOHUD=0 # Only neccessary if you're using Linux
godot4 ./project.godot # replace `godot4` with the path of your actual godot4 mono installation.
```

### Plugins shiped
It has these plugins already pre-installed with the project and available in the source tree as well.

+ **[Jolt Physics](https://github.com/godot-jolt/godot-jolt)** - A multi core friendly rigid body physics and collision detection library suitable for games and VR applications, used by Horizon Forbidden West. Ported to Godot 4 
+ **[Proton Scatter](https://github.com/HungryProton/scatter)** - A MultiMesh Based mass scatterting tool. Used for mainly distributing foliage
+ **[Debug Menu](https://github.com/godot-extended-libraries/godot-debug-menu)** - Displays performance metrics, Inspired from ID Tech performance overlay
+ **[Godot Git Extention](https://github.com/godotengine/godot-git-plugin/)** - The official git vcs extention for godot engine.
+ And more probably being added...

### Licensing
This project would be mainly licenced under MIT but the plugins do have thier respective licenses, thats why we are going for a full REUSE-compliance in the future.

