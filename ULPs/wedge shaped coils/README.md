<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#EAGLE">EAGLE</a></li>
    <li><a href="#ULP">ULP</a></li>
    <li><a href="#Installation">Installation</a></li>
    <li><a href="#Usage">Usage</a></li>
    <li><a href="#Close-up-of-a-single-coil">Close up of a single coil</a></li>
    <li><a href="#Some-examples">Some examples</a></li>
    <li><a href="#Known-issues">Known issues</a></li>
  </ol>
</details>


## EAGLE  <a name="EAGLE"/>

**E**asily **A**pplicable **G**raphical **L**ayout **E**ditor is a PCB design and electrical schematic software.

## ULP  <a name="ULP"/>
User Language Programs (ULP) are scripts that are run from within EAGLE to accomplish tasks that would be tedious to do by hand or have to be repeated frequently.

## Installation <a name="Installation"/>
**Option 1:**<br />
Place the file "WedgeShapedCoils.ulp" anywhere and navigate to it via file selection dialog box 

**Option 2:**<br />
Put the ULP-file in the folder with all the other ULP inside the EAGLE installation in $EAGLE_INSTALL_DIRECTORY$\examples\ulps\examples

**Option 3:**<br />
Put the ULP-file in the folder with all the other ULP inside the user directory in $USER$\Documents\EAGLE\ulps

## Usage  <a name="Usage"/>
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


## Close up of a single coil  <a name="Close-up-of-a-single-coil"/>
![](images/ExampleLayout2.png)

## Some examples  <a name="Some-examples"/>
![](images/Example1.png)
![](images/Example2.png)
![](images/Example3.png)

## Known issues <a name="Known-issues"/>
### #1
During DRC you get a bunch of Airwire errors.

Some wires between 'Arcs' and 'Wires' aren't connecting properly.
I've created a [thread](https://forums.autodesk.com/t5/eagle-forum/wires-not-connecting-with-command-line-function-calls/td-p/9889741 "thread") in the EAGLE Forum but no replies. I've contacted the support - no reply either. ¯\_(ツ)_/¯

I didn't have any problems creating CAD-files and PCBs since the wires overlap more than enough.
