# Massive-Loop-Template-Worlds-Bowling-Alley
Template Game World for creators in Massive Loop

![BowlingAlley](BowlingAlleyGif.gif)

## Unity Editor Requirements
Please Navigate to the package manager and ensure that the following two Unity packages, these are dependents :
* Post Processing
* ShaderGraphs

Please also make sure that your editor is using the Built-In Renderer.

## Seeing Pink Textures? No worries!
Sometimes, when exporting shadergraphs from the Unity Editor, shadergraphs can sometimes lose their active target locations. 

Luckily for us it is a very easy fix.

Navigate toward the Shaders folder found in the Times Square subfolder in the asset. You will want to click on the **"Open Shader Editor"** button

![Shaders_1](Shaders_1.png)

Next, where you see the **"Active Targets"** section in your graph inspector, simply click the plus button and select **"Built-In"**

![GraphInspector](GraphInspector.png)

Next, click on the **"BultIn (Unknown)"** Active target and remove it by pressing the minus button. Press **CTRL + S** on your keyboard and it should fix itself! 

If it does not reimport itself, right click on the shader and click **reimport**

And there you have it! 

Times Square will be restored to its glory, all thanks to you and the handy Shadergraph toolset!

![Shaders](Shaders.png)
*(Looks like I missed a couple billboards!)*
