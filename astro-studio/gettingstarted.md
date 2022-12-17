# Getting started

After a successful launch, the welcome window will appear on the screen.

![](<../.gitbook/assets/Astro_Studio_Install_13.png>)

From this window you can create a new project, open an existing one or select one of the last projects you have been working with. 
If the "Show on startup" checkbox is unchecked, this window will no longer appear.

After closing the welcome window, the main Astro Studio window will be available.

![](<../.gitbook/assets/Astro_Studio_Install_14.png>)

To experience Astro Studio, let us create a simple "Hello World!" robot. 
Click on "Create project" in the middle of the screen and the project creation window will pop up: 

![](<../.gitbook/assets/Getting_Started_1.png>)

Type in the project name, for example "My_First_Project":

![](<../.gitbook/assets/Getting_Started_2.png>)

And click "OK" to create the project.
Now you can see that the new project was created and you can start buiding your first robot. 

The main Studio window contains multiple panels. Let us review the main ones: 

![](<../.gitbook/assets/Getting_Started_3.png>)

Project panel helps you navigate the project and its components: libraries, folders and files. 
In our first project we have one Main.ltw sequence file. 

![](<../.gitbook/assets/Project_Panel.png>)

In the bottom of this area you can switch from Project panel tab to Elements panel. 
Elements panel contains all the basic scritp building blocks - elements, which you can combine to create your robot. Primo RPA platform includes hundreds prebuilt elements, so to find the right element you may use search. Let us look for "Message box" element:

![](<../.gitbook/assets/Getting_Started_4.png>)

In the center you see the Main panel - the primary working area where you design your robot. 
The panel may contain multiple tabs with individual sequences and workflows for complex automations. 

![](<../.gitbook/assets/Main_Panel.png>)

On the right side of the screen there is a Properties panel that shows parameters of the entire sequence or each selected object on the Main panel. 

![](<../.gitbook/assets/Properties_Panel.png>)

There is another important section - Variables panel, under the Main panel. It represents and helps to manage variables as well as other important aspects of robot execution. They are described in separate articles. 

![](<../.gitbook/assets/Arguments_Panel.png>)

After we introduced the key panels, let us continue building the first bot. 
Take "Message box" element and drug it into the Main panel and drop it in the sequence. 
Then go to the Properties panel, find Text property and type Hello World! 

![](<../.gitbook/assets/Getting_Started_5.png>)

We've created an element that will show a message box with "Hello World!". However, there is an exclamation sign on the sequence. It means there is an error. 

![](<../.gitbook/assets/Getting_Started_12.png>)

This happens because of the syntax error, in the LOW-CODE mode String type requires text in quotation marks - "Hello World!" You can either add quotes or you may change the mode to simplified NO-CODE mode by clicking on the bottle icon next to Hello World!" text in the Parameters panel. 

![](<../.gitbook/assets/Getting_Started_7.png>)

The bottle turns green and the error disapears. The robot is ready!  

![](<../.gitbook/assets/Getting_Started_8.png>)

Now you may click Playback button on the Control panel:

![](<../.gitbook/assets/Getting_Started_9.png>)

Astro Studio will compile the robot, load necessary resources and execute it. You should see the message window: 

![](<../.gitbook/assets/Getting_Started_10.png>)

Congratulations, you built your first Astro RPA robot! 

