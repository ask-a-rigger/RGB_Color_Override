# RGB_Color_Override
Author:  Allen C. Paul
	 askarigger@gmail.com


Description:
	"RGB Color Override" is a wonderful tool to help users become organized by easily changing their colors of their objects, locators, joints and much more in both the Outliner and Viewport in Maya. This Python script uses the built in color feature in Maya with a few simple scripts I built to easily change the colors without going through multiple steps.

Version: 1.0.0


.- .--- .- -.-- / -.- ..- -- .- .-.   Features  .- .--- .- -.-- / -.- ..- -- .- .-. / ...- . .-. -- .-

"RGB Color Override" currently has 3 main features: You can apply a color of your choice to the Outliner, Viewport or Both.

You will see three color options. Outliner, Viewport, and Both. In a color of Red, Green, and Blue. Next to them you will see "Apply..." to each of the colors. Follow these steps to choose a color and apply them to the object you selected
		
	1. Click over the color next to your choice of Outliner, Viewport, or Both. 
  	  A. "Single Click" will open the small Color Wheel Ui
  	  B. "Double Click" will open the big Color Wheel Ui
	2. After selecting your color with the big Color Wheel Ui, hit done.
	3. Once you have chosen your color, select your object
  	  A. You object can be Joints, Geometry, Groups, Locators, Constraints... etc.
  	  B. You can have multiple objects selected.
	4. Then hit the "Apply..." button corresponding to your choice.
	5. You may keep the window open or close the window by hitting the "Close" button or the "X" in the upper right corner
		
Bonus Feature:
  You can use the eye drop tool with the Color Wheel Ui to color current color choices on the screen or "RGB Color Override" options

	

.- .--- .- -.-- / -.- ..- -- .- .-. How to Install & Run  .- .--- .- -.-- / -.- ..- -- .- .-. / ...- . .-. -- .-

EXTRACT "RGB_Color_Override" zip folder and copy the "RGB_Color_override" folder into your Maya Scripts folder then restart Maya.

MAYA_SCRIPT_PATH = 'C:/Users/'username'/Documents/maya/scripts/'

LOAD: To load up "RGB_Color_Override" use the following command in your script editor (Make sure your script editor is set to Python)

import RGB_Color_Override.rgb_color_override_ui
reload (RGB_Color_Override.rgb_color_override_ui)
RGB_Color_Override.rgb_color_override_ui.color_change_main()
	
SHELF SHORTCUT: You can go a step further and put it on a shelf.
	1. Take the three lines of code above and place them into your script editor
	  *Make sure the script editor is on Python
	2. Select the entire code
	3. Middle mouse drag the code to the shelf you would like it to be on
	4. Once it is on the shelf, right click and select edit
	5. Select the tab "Shelves"
	6. Go to "Icon Label" and name it "RGBco"
	7. Click "Save All Shelves"	
	
For any bug, query or assistance please email @  askarigger@gmail.com



.- .--- .- -.-- / -.- ..- -- .- .-.  Warnings  .- .--- .- -.-- / -.- ..- -- .- .-. / ...- . .-. -- .-

*** No bugs found at the time of Version 1.0.0 ***
