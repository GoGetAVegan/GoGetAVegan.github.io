## Maximus Lorah Portfolio

### Diagetic UI

In this project I have made a UI system that makes a Diagetic menu that the player can interact with much like how Dead Space has their diagetic UI system.

![HoloWatch](https://user-images.githubusercontent.com/54685877/153337999-712e5b08-1df1-42d8-8c66-68290842b3df.png)

In this image it is a small watch that the player is holding showing them their current health and a little message welcoming them. I made it very small to still give the player ample room to see their surroundings.

![HoloWatchClosed](https://user-images.githubusercontent.com/54685877/153338176-a287f5e5-230a-402a-a252-7254a4529e2f.png)

The player can close the watch allowing them to have full view of their environment.

![HolographicMaterial](https://user-images.githubusercontent.com/54685877/153338386-a8df2213-3cf0-4a35-8f6d-fc2989c43658.png)
![HealthBar](https://user-images.githubusercontent.com/54685877/153338513-9cb2030e-33ad-4c57-bae7-d1e13875c70e.png)

I made the materials used on the watch where the first image shows the background where I was going for a holographic look and the second image is the healthbar that changes color depending on your health state where full is green and near death is red (pictured below).

![image](https://user-images.githubusercontent.com/54685877/153338699-87c82709-1d71-402d-aa16-1218cd300067.png)


### OnlineFPS

In this project I wanted to make an online FPS that way I would have some experience with the online features that the unreal engine has. 

![image](https://user-images.githubusercontent.com/54685877/157775723-3c95b670-d093-4b20-a0aa-4609e1eaa66c.png)

I was able to get two players spawning in the world and could add more if needed and both can shoot and move around and both update correctly with their positions in the world.

![image](https://user-images.githubusercontent.com/54685877/157775879-b8e6cfd5-f6a3-44e1-9c4f-b5fd065b486e.png)

The players had a parkour component attached to them and could do their movements with this allowing them to Wall Climb, Slide, Sprint, and event Mantle. This was a little harder to get working as I had to replicate it to both characters since the component needs specific things from the character movement allowing them to execute the parkour.

This component also has a queue system in place so it can be seemless when going from sliding to sprinting and from sprinting to sliding. This works with other parkour moves as well making the transition between them not feel jittery.



### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/GoGetAVegan/GoGetAVegan.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.
