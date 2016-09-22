# ssto_launch
<br />
KSP-Mod required (you can also install it via CKAN):<br />
https://github.com/KSP-KOS/KOS<br />
<br />
(written for kOS v 1.0.0)
<br />
<br />
File location (just the file 'ssto_launch', not the .zip version of the repo!):<br />
Kerbal Space Program\Ships\Script
<br />
##Usage
####Easy way:
Open kOS Termin in your spaceplane and type:
<br />
<br />
switch to 0.<br />
run ssto_launch.<br />
<br />
This runs the script on your ship while it is stored in the KSC
<br />
####Realistic way:
Open kOS Termin in your spaceplane and type (w/o quotes):
<br />
<br />
switch to 0.<br />
copypath("ssto_launch", "1:/ssto_launch").<br />
switch to 1.<br />
run ssto_launch.<br />
<br />
This copies the script to the internal storage of your plane before executing it.
If you are using RemoteTech this might make a difference (easy way will not work without an active connection)


#### Tested with:

**LR-133 'Sabertooth':**<br/>
    https://kerbalx.com/Fulgora/SSTO-LR-133-Sabertooth<br/>
    Mods: FAR + kerbalx modlist
