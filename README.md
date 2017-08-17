Propulsion Raw Data
===================

This repository contains the files from the wheelchair propulsion experiment conducted at UFABC.

<img src="https://raw.githubusercontent.com/fei-nta/Propulsion-Raw-Data/master/images/readme_pic1.JPG" height="300" align="right" alt="Location of anatomical markers on front side" />

<img src="https://raw.githubusercontent.com/fei-nta/Propulsion-Raw-Data/master/images/readme_pic2.JPG" height="300" align="right" alt="Location of anatomical markers on front side" />

The first day of trial out was just focused in capturing the 3D position of the markers. The folder "propulsion raw data-01" contains all four propulsion experiments.

**./propulsion raw data-01/**
* propulsion1.trc
* propulsion2.trc
* propulsion3.trc
* propulsion4.trc
  
The second day of trial out was focused in collecting the following information:
* Force and moment signals during the propulsion from the whelchair wheel;
* EMG signals from a variety of muscles during the propulsion;
* 3D position of the markers. 

Therefore, the experiments were divided in:

* 1-2: warm-up
* 3-5: Normal velocity during the propulsion;
* 6-8: Maximal velocity during the propulsion;
* 9 and 10: Descaleration experiment;
* 11 and 12: Sustained static maximum voluntary contraction to propel the wheelchair.

**./propulsion raw data-02/trial-0X**
* *SW1-0**X**.csv* : Force and moment data for the left wheel; 
* *SW2-0**X**.csv* : Force and moment data for the right wheel;
* *mw**X**.anc* : Analog signals to syncronize the SmartWheel and motion capture analysis;
* *wc**X**-Delsys 1.csv* : EMG data;
* *wc**X**.trc* : Position of markers placed on a subject at different times during a motion capture trial;

./images
* Contains the position of the location of anatomical markers and an ilustrated video of the experiment.

Equipment used
--------------
* System with 12 cameras with 4 Mb of resolution at 200 Hz from [Motion Analysis](https://www.motionanalysis.com/)
* Instrumented wheelchair wheel from [SmartWheel](http://www.out-front.com/smartwheel_overview.php)
* Wireless EMG system with 10 sensors from [Delsys](http://www.delsys.com/products/wireless-emg/)

Refereences
===========
> [BMClab](http://demotu.org/) Biomechanics and Motor Control Laboratory of the Biomedical Engineering program at the Federal University of ABC. 

> Jaimes, Kristy Alejandra Godoy, and Marcos Duarte. Avaliação Biomecânica De Usuários De Cadeira De Rodas Manual. 2016.

> Wu, Ge, et al. "International Society of Biomechanics. ISB recommendation on definitions of joint coordinate systems of various joints for the reporting of human joint motion—part II: shoulder, elbow, wrist and hand." J Biomech 38.5 (2005): 981-92.
