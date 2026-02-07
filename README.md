# MATSCI465-Qianruitong
In this assignment, we used 4D-STEM data to explore how virtual detectors can be used to generate different imaging contrasts after data collection.In a 4D-STEM experiment, a full diffraction pattern is recorded at every scan position,which preserves both real-space and reciprocal-space information in the dataset.

Because the diffraction information is saved for each probe position,detector do not need to be fixed during the experiment.Instead, virtual detectors such as Bright Field (BF) and Annular Dark Field (ADF) can be defined in software after the data has been collected.By integrating different regions of the diffraction pattern, multiple imaging modes can be reconstructed from the same dataset.

In this work,BF and ADF images were generated from the Si/SiGe dataset using software-defined detector masks.The BF image highlights diffraction contrast related to crystal orientation and thickness,while the ADF image shows Z-contrast associated with atomic number and mass-thickness.This demonstrates how virtual detectors allow the experiment to be effectively re-analyzed,with different detector configurations without acquiring new data.

