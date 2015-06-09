# NRE Earplugs
*Arma 3 - Earplugs script*

####Description:
Adds action to insert/remove Earplugs (toggles).
Inspired by A3Wasteland132DSOv14.Altis kopfh script

####License:
```
Copyright (C) 2015 Steven "NemesisRE" Köberich

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
```

####Manual:
* Create a "scripts" folder in your mission and put the main script in there (or update init.sqf and NreEarplugsPath variable in the main script)
* Add following to your stringtable.xml:
```XML
<?xml version="1.0" encoding="UTF-8"?>
<Project name="NRE Earplugs">
	<Package name="NREEarplugs">
		<Key ID="STR_NREEP_IN_HINT">
			<Original>You have insert the earplugs!</Original>
			<English>You have insert the earplugs!</English>
			<Russian>Беруши вставлены!</Russian>
			<German>Du hast die Ohrstoepsel eingesteckt!</German>
			<Spanish>¡Te has puesto los tapones!</Spanish>
		</Key>
		<Key ID="STR_NREEP_OUT_HINT">
			<Original>You have removed the earplugs!</Original>
			<English>You have removed the earplugs!</English>
			<Russian>Беруши вытащены!</Russian>
			<German>Du hast die Ohrstoepsel rausgenommen!</German>
			<Spanish>¡Te has quitado los tapones!</Spanish>
		</Key>
		<Key ID="STR_NREEP_IN_ACTION">
			<Original>Insert earplugs</Original>
			<English>Insert earplugs</English>
			<Russian>Вставить беруши</Russian>
			<German>Ohrstoepsel einstecken</German>
			<Spanish>Ponerte los tapones</Spanish>
		</Key>
		<Key ID="STR_NREEP_OUT_ACTION">
			<Original>Remove earplugs</Original>
			<English>Remove earplugs</English>
			<Russian>Вытащить беруши!</Russian>
			<German>Ohrstoepsel rausnehmen</German>
			<Spanish>Quitarte los tapones</Spanish>
		</Key>
	</Package>
</Project>
```
* Call from init.sqf via:
```SQF
execVM "scripts\NRE_earplugs.sqf";
```
