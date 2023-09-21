Hi, this is just a simple little application I made to help me setup flights with Volanta, Navigraph, Addonlinker, Simbrief and microsoft flight sim.

### INSTALLATION AND SETUP

1. Extract the Flight Setup folder to wherever you'd like
2. Within the Flight Setup folder open the "config.ini" and amend the paths for Volanta, Charts(Navigraph), Addons(Addon Linker) and you Checklists folder.
		
_volanta = "YourPathToVolanta.exe"
_Charts_ = "YourPathToNavigraph Charts.exe"
_Addons_ = "YourPathToAddonsLinker.exe"
_Checklists_ = "YourPathToYourChecklistsFolder"_

**To** Easily get the path:
- Navigate to where the .exe is located (If a shortcut, right click on it and select 'open file location')
- Hold Shift and Right click on the exe
- Select 'Copy as Path'
- Paste into the .ini

3. Open and Edit the Aircraft list:
-   The included "Database.xlsx" can be edited with your own aircraft and tail numbers.
-   The first Tab / Sheet can be edited with you own aircraft.
-   The second is used to look up the airlines and shouldnt need editing.

Its optional but for me I created all the aircraft I use in Volanta with my own Tail numbers so i could see how many hours and flights etc I'd done in each aircraft. 
I gave chatgpt a list of all the aircraft i use and asked it to create random GB themed tail numbers but thats just me :D

### HOW TO USE

1. Open the FlightSetup.exe
2. Click the "Pick a Flight" button, to open Volanta and find a flight via the Schedules tab (This requires the paid version of Volanta sorry) 
_If you dont own the paid version of Volanta you could also use FlightRadar to find a reference flight number._

3. Type in the flight number you found into the "Ref Flight Number Field"
4. Enter the departure and destination ICAO's into the corresponding fields. So EGSS for London Stanstead.
5. Select which of your Aircraft you'd like to use for the flight from the dropdown list next to aircraft.
6. Hit Generate to create a summary of your flight
_This_ summary I've found is really handy to copy and paste from into Simbrief, MSFS, etc

7. Click the Departure, Destination, Aircraft buttons to open their corresponding searches in flightsim.to. This should help you find liveries for your plane based on the airline / flight number you selected and free addon scenery / gsx profiles. 
8. Use the SimBrief, Charts, Addons and Checklist buttons to open the relevant apps and tools.


**Hope you find this useful :)** 

### Download the Zip here and not from the Assets / source bit
[Flight Setup.zip](https://github.com/Squeak-y/FlightSetup/files/12685047/Flight.Setup.zip)

