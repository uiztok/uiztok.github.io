---
title: "Super-resolution microscopy / nanoscopy / nanospectroscopy"
date:  2021-07-01
collection: resources
header:
  teaser: 'lab_STED.jpg'
---

The state-of-the-art modular 2-photon super-resolution 3D STED microscope, custom-built by [Abberior Instruments](https://abberior-instruments.com/), is equiped with several exciation and detection modalities for live-cell imaging of supramolecular structures on the scales down to 30 nm. 

![STED](/images/lab_STED.jpg)

Technical details:  

Inverted microscope:
* Olympus IX83 body with several objectives (10x/0.4, 60x/1.2 water, 100x/1.4 oil)  
* motorised stage
* stagetop incubator controlling temperature, humidity, and CO2  
* 4-colour LED widefield illumination  

Modular fully automated *Abberior Instruments Expert Line* 2D/3D STED equipped with:  
* 5 excitation lasers: 405 (cw), 485, 518, 561, 640 nm (pulsed: 40/80 MHz, 100 ps)  
* STED depletion laser: 775 nm (pulsed: 40/80 MHz, ns)  
* high-power Ti-Saph laser: tunable 800-1300 nm (pulsed: 80 MHz, 150 fs)  
* fast galvanometric scanning (up to 2 kHz)
* 4 single-photon-counting detection: avalanche photodiodes (APDs; deadtime <25 ns) 
* spectrally-resolved detection: 16-channel PMT with diffraction grating by Becker&Hickl  
* FLIM: time-correlated single-photon-counting (TCSPC) electronics by Becker&Hickl
* transmission detection: PMT for simultaneous acquisition with confocal scanning

The flexible setup enables:
* acquisition of any combination of the coordinates x,y,z,t,tau,lambda 
* acquisition with any combination of the following modalities: confocal, 2D/3D STED, FLIM, spectral   
* automation of complex experiments through python scripts  
* addition of new laser sources, detectors, optics, ...  
