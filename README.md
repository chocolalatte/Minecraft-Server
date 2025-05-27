# This is a copy of the minecraft info google doc found [here](https://docs.google.com/document/d/1aVOYEOftEsvlVb9I2s22hSNT7qydCiJFhffJJZ50Q-k/edit?usp=sharing)

1. Install the modpack[^1].  
   1. Download the [modpack](https://github.com/chocolalatte/Minecraft-Server/blob/main/base/pack.mrpack). Open the link then click the download icon (or press ctrl+shift+s)  
   2. Open modrinth and import the modpack file.  
2. Allocate memory.  
   1. Find the modpack in modrinth.  
   2. Open the modpack settings and go to “Java and memory”.  
   3. Where it says “Memory allocated” click on “Custom memory allocation” and change this value depending on how much memory you have (see below)[^2].  
3. Customize java installation (optional).  
   1. Download the .msi file from [here](https://adoptium.net/temurin/releases/?version=17&package=jre&arch=x64&os=windows).  
   2. Run the file and install Adoptium.  
   3. Go back to the modrinth “Java and memory” settings.  
   4. Click on “Custom Java installation” and replace the text in the box with  
      “C:\\Program Files\\Eclipse Adoptium\\jre-17.0.14.7-hotspot\\bin\\javaw.exe”.

## Optimization

### Java installation

If you haven’t already, using a custom java installation should increase performance. Ask me for assistance if needed. This could be done because you either want as much performance/fps as possible or as a last resort for being able to run the game.

### In game settings

**Simulation distance:** Set to the lowest possible value.  
**Entity distance:** If you don’t care if you can see mobs when they are far away I would suggest setting this to half your render distance.  
**Particles:** Set to decreased as this will reduce the amount of particles rendered, it does not affect what particle effects you can actually see.  
**Chunk update threads:** You should set this to 4 (depending on how many cpu threads you have I assume everyone can but idk)

### Shader information

**Performance:** VanillAA.  
**Performance \+ Quality:** Proton.  
**Lowest performance:** Rethinking Voxels.  
**Recommendation:** Most of the shaders are very similar in performance–which is why most aren’t listed–so pick the one you like the best and if needed try the two listed performance shaders if you are having issues.

[^1]:  If you are using a different launcher please ask me for help.

[^2]:  If you have 8 GB of memory set this to 5120, if you have more than 8 GB set this to 8192\.
