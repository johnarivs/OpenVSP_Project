# OpenVSP_Challenge_Project
## Cessna 172 Superhawk VSP Model

### Challenge Rules:
1. Install the vsppytools conda environment, which requires that you have anaconda or miniconda.  README files are distributed with openvsp and can be found in the python directory
2. After you have activated vsppytools conda environment, import openvsp package w/o error
3. Using the OpenVSP Python API you just set up, create a python script that automatically creates a fuselage, a wing, a horizontal tail, and a vertical tail, and have it place them in reasonable locations.
4. Using the api, create a prop component and rotate and place it in a reasonable location
5. Using the api, change the number of blades from the default value to another value (say from 3 blades to 5 blades)
6. Using the api, change the blade twist, chord, and thickness distribution (exaggerate them to prove it is working)
7. Write out the openvsp file to disk

I decided to add my own twist to the challenge by modeling the the fuselage, wings, tails, and propeller after the Cesna 172 SuperHawk Model

I managed to model it via the (cessna.png) seen in the attached file which are also publicly available

This Cessna 172 Skyhawk Model is based off of some design publicly available in which I overlayed using the background tool and roughly sketched the Fuselage, Wing, Tails, and propeller
