# Quadrupole-Mass-Spectrometry

This repository aims to implement Signal Processing of Quadrupole Mass Spectrometry data from Cross-beam ion sources used to study electron-beam-induced chemical processes in argon clusters, and single molecules, in the context of thin films, and new materials for semiconductors applications.

For this purposes, the codes are developed, mainly in Python R. And allow us to analyze different experimental processes such as:

 1) Electron Stimulated Desorption (ESD)
 2) Thermal Stimulated Desorption (TSD)
 3) Cross-section (as a function of Electron Energy)
 4) Mass spectra identifying the peak positions

The developed codes works reading files in .csv, .txt and .asc format files.

## Example

![alt text](https://github.com/renecartaya/Quadrupole-Mass-Spectrometry/blob/main/Plots/MS_sample.png)

## Notes

The code is able to identify peaks positions for itslef though the identity of them in the current stage should be done for the user, being able to label the peak identification in txt over the plot.

The sensitibity of the peak detection could be tailored for those spectrums with big concentrations of peaks. Nevertheless, the peak positions could be also shifted by the user in the cases that the user want to highligh a more specific positions. 

