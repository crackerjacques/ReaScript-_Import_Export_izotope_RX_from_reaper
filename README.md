# ReaScript_export_markerlist_by_izotope_RX_format
This script set will export iZotope RX Markerlist from Reaper project.

# Requirements

Python 3.x
argparse

'''pip install argparse'''


# HOW TO USE

Please clone or download this repo.

'''git clone https://github.com/crackerjacques/ReaScript-Export_izotope_RX_from_reaper.git'''

and copy scripts to your Reascript dir.

Select　__MarkerList4RX.lua__　 and Hit Start.

Then Open dialogue, You must name file and done.

# __DO NOT Touch csv2rx_action.py__
Because this Python script uses TKinter, some environments may crash when trying to run it from Reaper.
,,python csv2rx_action.py -i foo.csv,,,
It will work if run from a command prompt or terminal like this, but so far, on both my Windows and Mac, it crashes when run from Reaper.

First in Lua, output temp.csv to the script directory, then to avoid crashes, start Python on the OS side, not on the Reaper side, and convert it to RX text data.
This is a very barbaric approach.


This is a problem I hope to solve soon.

# Import RX Marker List to Reaper 

Please visit my other repository

https://github.com/crackerjacques/IzotopeRX_MarkerList_to_Reaper_CSV


