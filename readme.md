# mst_foil_density

**Overview**

This repo contains the psychopy script - mnemonicproj.py - and the stimulus set script - build_stim_sets.py - necessary for running the foil density experiment. The foil density experiment's overarching aim is to evaluate how changing the density of foils during recognition memory modifies the discriminability of lures (items that are similar to targets but not identical). To run this experiment you need to follow the two steps below:

**Step1**
After seting your environment or ensuring you have python3 and the relevant dependencies established you need to first run the build_stim_sets.py script from the terminal command line.  You do this by opening a terminal window, navigating to the appropriate directory, and then on the command line typing the following:

python build_stim_sets.py --subj ####

This will then run the build_stim_sets.py script and create a subject specific directory sub-#### in the data folder that should be in the same directory as the psychopy and stimulus set scripts.  Inside that directory you'll find the following files:

encoding.xlsx (which also has columns for encoding1, encoding2, encoding3, encoding4)
retrieval1.xlsx
retrieval2.xlsx
retrieval3.xlsx
retrieval4.xlsx

**Step2**
Once the subject specific encoding and retrieval stimulus sets have been created you need to open in psychopy the mnemonicproj.py file and run from the coder view.  This script is built to read the created files from the first step to present stimuli and foil density in a randomized way across participants.


