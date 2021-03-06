ModelViewer 0.6
----------------
1. Overview
With this program you can open 3D models and render them in OpenGL.
If your model has textures attached they get automatically loaded.

To open a model just right click on it, "Open with" and then navigate to the ModelViewer
or type in the absolute path to the desired model.

2. Supported Files
    3DS
    ASE
    DXF
    HMP
    MD2
    MD3
    MD5
    MDC
    MDL
    NFF
    PLY
    STL
    X
    LWO
    OBJ
    SMD
    Collada
    LWO
    Ogre XML
    partly LWS

3. Controls
Left Mouse Button 	- Rotate Light
Middle Mouse Button - Scale Model
Right Mouse Button	- Rotate Model around the local Y-Axis
				W   - Toggle Wireframe
				S	- Toggle Shading Mode (Smooth, Flat)
				H 	- Toggle GUI
				T 	- Toggle Textures
The rest is controlled by the GUI.
				
4. FAQ
Q: My model is just black and the light does not work, why?
A: The modelLoader-AddOn from OpenFrameworks is a bit buggy. Try to open one of the example objects, they should work.

Q: AHH! My GUI is gone!
A: You probably have hidden the GUI, press H ;)

Q: Lights/Model keeps rotating after I released the mouse button
A: There is a bug in GUI where the "mouse release" does not get recognized when you are inside the GUI.
	Just click the "faulty" mouse button again and release it outside of the GUI.

Q: Why does my model don't have any textures?
A: When you have exported your model with Blender this could be the reason.
	I was not able to export a model out of Blender and load it with textures into de ModelViewer.
	
5. Credits
Thomas Fischer (if13b023)
