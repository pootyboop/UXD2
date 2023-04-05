---Specs---
Run the project/executable on Windows if possible. A decent graphics card will probably be necessary.
This project was built and tested on Windows 10 with a AMD Radeon RX 5600 XT.
------



---VR---
This project is not a standalone VR project. You will need to run the executable on your PC with a headset connected.
There should be support for input from any headset you use. If VR controller input does not work for whatever reason, use the PC controls (listed below).
If you want to run the Unreal project in VR, press the 3 dots icon next to the Play In Editor button and select "VR Preview". If this is greyed out, make sure your headset is properly connected and restart the project.
If you cannot run the executable in VR, run it without a VR headset. There is standalone PC support.

PC controls are as follows:
Mouse - look around
WASD - move
Space - start/stop the train (same in VR)
------



---Project---
This project is built in Unreal Engine 5.1. Sanjit has approved using non-Unity game editors such as Unreal Engine and Godot for this assessment.

The project uses VRExpansionPlugin. You do not need to install this plugin, it's included in the project files.
If you are prompted to rebuild modules on launching the project, do so.
If you get a "failed to compile" error, you will need Visual Studio with the C++/Unreal Engine installation.
Right click the project and click "Generate Visual Studio project files".
After this is completed, open the .sln in Visual Studio and run Unreal Engine from there by clicking Attach.
------