# Getting started

After a successful launch, the welcome window will appear on the screen.

![](<../.gitbook/assets/Astro_Studio_Install_13.png>)

From this window, you can create a new project, open an existing one or select one of the last projects you have been working with. 
This window will no longer appear if the "Show on startup" checkbox is unchecked.

After closing the welcome window, the main Astro Studio window will be available.

![](<../.gitbook/assets/Astro_Studio_Install_14.png>)

To experience Astro Studio, let us create a simple "Hello World!" robot. 
Click on "Create project" in the middle of the screen, and the project creation window will pop up: 

![](<../.gitbook/assets/Getting_Started_1.png>)

Type in the project name, for example, "My_First_Project":

![](<../.gitbook/assets/Getting_Started_2.png>)

And click "OK" to create the project.
Now you can see that the new project was created, and you can start building your first robot. 

The main Studio window contains multiple panels. Let us review the main ones: 

![](<../.gitbook/assets/Getting_Started_3.png>)

The Project panel helps you navigate the project and its components: libraries, folders, and files. 
In our first project, we have one Main.ltw sequence file. 

![](<../.gitbook/assets/Project_Panel.png>)

At the bottom of this area, you can switch from the Project panel tab to the Elements panel. 
The Elements panel contains all the basic script building blocks - elements you can combine to create your robot. Astro RPA platform includes hundreds of prebuilt elements, so you may use search to find the right element. Let us look for the "Message box" element:

![](<../.gitbook/assets/Getting_Started_4.png>)

In the center, you see the Main panel - the primary working area where you design your robot. 
The panel may contain multiple tabs with individual sequences and workflows for complex automations. 

![](<../.gitbook/assets/Main_Panel.png>)

On the right side of the screen, there is a Properties panel that shows the parameters of the entire sequence or each selected object on the Main panel. 

![](<../.gitbook/assets/Properties_Panel.png>)

There is another essential section - the Variables panel, under the Main panel. It represents and helps to manage variables and other important aspects of robot execution. They are described in separate articles. 

![](<../.gitbook/assets/Arguments_Panel.png>)

After introducing the key panels, let us continue building the first bot. 
Take the "Message box" element, drag it into the Main panel, and drop it in the sequence. 
Then go to the Properties panel, find Text property and type Hello World! 

![](<../.gitbook/assets/Getting_Started_5.png>)

We've created an element that will show a message box with "Hello World!". However, there is an exclamation sign on the sequence. It means there is an error. 

![](<../.gitbook/assets/Getting_Started_12.png>)

This happens because of the syntax error. The default LOW-CODE mode requires String-type text to be placed in quotation marks - "Hello World!" You can either add quotes or change the mode to simplified NO-CODE by clicking on the bottle icon next to the "Hello World!" text in the Parameters panel. 

![](<../.gitbook/assets/Getting_Started_7.png>)

The bottle turns green, and the error disappears. The robot is ready!  

![](<../.gitbook/assets/Getting_Started_8.png>)

Now you may click the Playback button on the Control panel:

![](<../.gitbook/assets/Getting_Started_9.png>)

Astro Studio will compile the robot, load necessary resources, and execute it. You should see the message window: 

![](<../.gitbook/assets/Getting_Started_10.png>)

Congratulations, you built your first Astro RPA robot! 

