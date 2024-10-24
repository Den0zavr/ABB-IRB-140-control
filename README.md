Hi, thanks for stopping by. This is a simulation of the ABB IRB 140 industrial robot.
Those are the steps you should take to run it successfully:
1. Make sure you have both products needed to run the simulations, which are MATLAB and SIMULINK;
2. download the zip archive from this repo if you haven't done it yet, extract all the files in one folder and place it wherever you like;
3. change your current MATLAB working directory to the one you've acquired in the previous step. Anotherwords, make the simulation folder your current folder;
4. whilst in matlab, open the "IRB140Rigit.mat" file. Notice that your workspace now has a variable, named "AssemBinzel" and its value is 1 by 1 rigitBodyTree;
5. we're all set to jump into the simulation. Open the "ABBIRB140.slx" and wait for simulink to load the model;
6. when the model is loaded, press Ctrl+D to update it to ensure that no errors pop up;
7. There are two options on how to drive the robot: by pretty much any analog controller that supports USB protocol or by the trajectory planning. Whatever your option is, make sure that the second is fully commented, otherwise you'll uncover the secret feature of this simultaion;
8. Note that in order to control the robot via analog controller you have to maintane the connection to your device or the simulation will stop;
9. hit the f5 button or the green arrow and have fun with it.
10. when the simulation begins, right click on the simulation window and change convention such that the Y-axis facing upwards (Y-up XY front). Also consider selecting isometric view as the standard view. 

E-mail me at gorindenis2k@gmail.com for your feedback is greatly appreciated.
I've added the "AssemBinzel.slx.r2020b" simulink file just in case you have older version.
