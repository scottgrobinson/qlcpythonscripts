# QLC+ Python Scripts
Python scripts to make QLC+ a little bit easier!

### Requirements
* python3 (With following modules)
	* csv
	* collections
	* json
	* os
	* click
	* xml.etree.ELementTree
	* mutagen.mp3
	* xml.dom.minidom
	* re

## CSVtoCueList.py
Takes a CSV of functions (Chasers, Scenes, Shows) and generates a cue list to run through in the virtual console.

## CSVtoShow.py
Takes a CSV of timecode and functions, and generates a show

### To-do
* Tidy up error checking, and detect if multiple functions share the same name
* Just... Tidy it up! It works nicely now, but we can tidy allot of this up