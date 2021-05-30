# EAGLE

**E**asily **A**pplicable **G**raphical **L**ayout **E**ditor is a PCB design and electrical schematic software.

## ULP
User Language Programs (ULP) are scripts that are run from within EAGLE to accomplish tasks that would be tedious to do by hand or have to be repeated frequently.

## Installation
**Option 1:**<br />
Place the file "WedgeShapedCoils.ulp" anywhere and navigate to it via file selection dialog box 

**Option 2:**<br />
Put the ULP-file in the folder with all the other ULP inside the EAGLE installation in $EAGLE_INSTALL_DIRECTORY$\examples\ulps\examples

**Option 3:**<br />
Put the ULP-file in the folder with all the other ULP inside the user directory in $USER$\Documents\EAGLE\ulps

## Usage
Launch the script inside EAGLE via the ULP Button.
![](images/ULP_Button.png)
<br />
<br />

Select the installation path (1) and select the ULP from the list or navigate to the script via the browse option (2) 
![](images/EagleSelectULP.png)
<br />
<br />

Input the desired parameters in the UI.<br />
![](images/UI_Screenshot2.png)
<br />
<br />

Confirm the pop-up with the number of windigs. <br />
![](images/WindingsConfirmation.png)
<br />
<br />

Wait for EAGLE to draw the coils.<br />
![](images/ExampleLayout.png)
<br />

Done!


## Close up of a single coil
![](images/ExampleLayout2.png)
