# Neuromorphic Auditory Visualizer (NAVIS Tool)

This software presents diverse utilities to perform the first post-processing layer taking the neuromorphic auditory sensors (NAS) information. The used NAS implements in FPGA a cascade filters architecture, imitating the behavior of the basilar membrane and inner hair cells and working with the sound information decomposed into its frequency components as spike streams. The well-known neuromorphic hardware interface Address-Event-Representation (AER) is used to propagate auditory information out of the NAS, emulating the auditory vestibular nerve. Using the information packetized into aedat files, which are generated through the jAER software plus an AER to USB computer interface, NAVIS implements a set of graphs that allows to represent the auditory information as cochleograms, histograms, sonograms, etc. It can also split the auditory information into different sets depending on the activity level of the spike streams. The main contribution of this software tool is that it allows complex audio post-processing treatments and representations, which is a novelty for spike-based systems in the neuromorphic community and it will help neuromorphic engineers to build sets for training spiking neural networks (SNN).

Copyright © 2015 Juan P. Dominguez-Morales
jpdominguez@atc.us.es
