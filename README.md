# KSP|kOS-Script that will take any* SSTO to space!
*given that there is enough lift, control and deltaV of course ;)
<br />
<br />
KSP-Mod required (you can also install it via CKAN):<br />
https://github.com/KSP-KOS/KOS<br />
<br />
(written for kOS v 1.0.3)
<br />
<br />
File location (just the file 'ssto_launch', not the .zip version of the repo!):<br />
Kerbal Space Program\Ships\Script
<br />
##Usage
Launch the craft like any other SSTO to the runway. (I like to turn on the brakes but its not a must)<br/>
How to open the terminal: Click on the kOS mod icon and then click the computer icon in the window that pops up.

####Easy way:
Open the kOS Terminal in your spaceplane and type:
<br />
<br />
switch to 0.<br />
run ssto_launch.<br />
<br />
This runs the script on your ship while it is stored on the 'harddrive' in the KSC
<br />
####Realistic way:
Open the kOS Terminal in your spaceplane and type (w/o quotes):
<br />
<br />
switch to 0.<br />
copypath("ssto_launch", "1:/ssto_launch").<br />
switch to 1.<br />
run ssto_launch.<br />
<br />
This copies the script to the internal harddrive of your plane before executing it.
If you are using RemoteTech this might make a difference (easy way will not work without an active connection)

##Vessel requirements:
- All engines in first stage

#### Tested with:
###### v0.1:
**LR-133 'Sabertooth':**<br/>
    https://kerbalx.com/Fulgora/SSTO-LR-133-Sabertooth<br/>

###### v0.3:
**CT-32 LKO Crew Transporter:**<br/>
    https://kerbalx.com/katateochi/CT-32<br/>
    
###### v0.4:
**CT-32 LKO Crew Transporter:**<br/>
    https://kerbalx.com/katateochi/CT-32<br/>
**Astraios 2:**<br/>
    https://kerbalx.com/Fulgora/Astraios-2<br/>
