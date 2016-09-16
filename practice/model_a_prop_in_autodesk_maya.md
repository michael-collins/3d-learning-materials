# Model a prop in Autodesk Maya

### Assignment Brief:
In this assignment, you are a product designer for the premiere mega lamp company, Schmapple Lights Inc. Schmapple Lights is wants its designers to produce never-before seen concept lamps. You're design objective is to design a concept lamp using polygonal modeling techniques and to render an image using RenderMan. You will produce at least one image shows your design in the best light.

### Learning resources
[Getting started with RenderMan for Maya](https://www.lynda.com/Renderman-tutorials/Welcome/442861/461592-4.html)

### Steps to completion
1. Download the project folder: [USERID-renderman-proj.zip](https://github.com/michael-collins/3d-learning-materials/blob/master/downloads/USERID-renderman-proj.zip?raw=true)
2. Rename the project folder to include your user id.
3. In the scenes folder, locate the file called ```USERID-renderman_project.ma``` and replace 'USERID' with your user id.
4. Double-click on the scene file to open Maya. Go to **File** -> **Set project**. Choose the project folder you just renamed in step 2.
5. In the project file, you will see an example polygon model with RenderMan materials applied. If you do not have RenderMan, go to **Windows** -> **Settings/Preferences** -> **Plug-in Manager**.
6. When ready, delete the example model and start modeling your own object.
7. Scene requirements
  - RenderMan lights (you can use the existing ones in the scene or create your own)
  - At least two RenderMan materials must be applied to your model in the scene. The PxrDisney material is a good starting point.
  - A final rendered image at 1080HD resolution or higher.
  - To reduce graininess of the final render, the Min. Samples in the Sampling tab under RenderMan Controls should be set to 32 or higher. Max. samples can be left as default 512.

### Deliverables
1. Your Maya project folder: ```USERID-renderman-project/```
 - Scenes folder: ```USERID-renderman_project.ma```
 - Images folder: A single openEXR image called  ```USERID-lamp-render.exr```
2. Compress the project folder.