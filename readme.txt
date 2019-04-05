========================================================================
Created by Ivan Bukreyev on 3/8/2019
========================================================================

Old (legacy) altium footprints and libraries are avaliable on this repo
https://github.com/butterwick/AltiumLibrary
or
https://techdocs.altium.com/display/ADOH/Download+Libraries

Footprint/Schematic source:
https://designcontent.live.altium.com/

Default altium home directory (specified during install):
	ALTIUM_HOME = (C:\Users\Public\Documents\Altium)


------------------------------------------------------------------------
Altium Preferences AD19, non-default
------------------------------------------------------------------------

System -> Default Locations:
	Document Path: ALTIUM_HOME
	Library Path: ALTIUM_HOME\AD16\Library
	OutputJob Path: ALTIUM_HOME\AD16\OutputJpbs	

System -> File Types
	Uncheck all "Code" and "VHDL" associations ??

System -> Installation
	Zoom with wheel, scroll with Ctrl (V) and Shift (H)

System -> Installation
	Set desired update frequency

System -> Product Improvement
	Do not participate

System -> Network Activity
	Disable: Altium Cloud, Sending Crash Reports, Product Improvement

Data Management -> Version Control
	Disable SVN - Subversion

Data Management -> Backup
	Use Path = ALTIUM_HOME\AD19\Backup
	Autosave every 30 mins, keep 10 versions

Data Management -> Local History
	Add autosaved documents to history
	Use Path = ALTIUM_HOME\AD19\History

Data Management -> Templates
	Use Path = ALTIUM_HOME\AD19\Templates\

Data Management -> SVN Libraries
	Use Path = ALTIUM_HOME\AD19\SVN

Schematic -> General
	Set default sheet size to "letter"

PCB Editor -> General
	Increase undo/redo limit ??

