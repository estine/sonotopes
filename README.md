
# Sonotopes

[UNDER MAJOR CONSTRUCTION]

Ecologically informed Plug-ins for sound creation and manipulation. 

Extensions of Eli Stine's 2019 dissertation, [*Modeling Natural Systems in Immersive Electroacoustic Music*](http://www.elistine.com/diss).

## Author

- [@estine](https://www.github.com/estine)

## Testers

- [@composingcap](https://www.github.com/composingcap)
- [@jschuett](https://www.github.com/jschuett)
- [@s3g](https://github.com/s3g)
- [Kevin Davis](http://kevindavismusic.com/)
- [Kramer Elwell](https://www.kramerelwell.com/)

## Plug-ins

- ### Crystal Wave Series
- #### IRidesce - Prismatic Stereo-IR Ambisonic Reverb
- #### Polytide - Ebb & Flow Note Generator
- #### Vitriform -  Bowed Glass Orrery
- #### Recolalia -  Gesture Recombination Engine
- ### Field Series
- #### Field Contrast - Spatially Adaptive Dynamics Processor
- #### Field Dynamic EQ - Spatially Adaptive Dynamic Equalization
- #### Field Resynth - Ambisonic Field Resynthesis
- #### Field Orchestrator - Auditory Scene Transcription


## Installation

### REAPER (Native)

Open REAPER, in the menu bar go to Options->Show REAPER resource path in explore/finder..., which opens the REAPER resources folder with Effects and Data subfolders.

Then place the downloaded files into these locations:

.../REAPER/Effects
	IRidesce.jsfx
	Polytide.jsfx
	Vitriform.jsfx
	Recolalia.jsfx

.../REAPER/Data
	IRidesce (required, folder with IRs)
	Recolalia (optional, folder with samples that can be loaded)

Then re-scan plug-ins in REAPER (or open the FX-adding window and hit F5) and they will show up as FX.

### YSFX

Install as above (or at least somewhere with the same Effects and Data folder hierarchy).

Then install YSFX via https://github.com/JoepVanlier/ysfx/releases

Open the ysfx-instrument or ysfx-fx plug-in in your DAW, and load the .jsfx file you'd like to load into YSFX. This is definitely in-progress, expect issues!
