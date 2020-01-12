**Hello!**   
This page is meant to help you find your way through [TheGoldLab](https://github.com/TheGoldLab) GitHub organization.
This organization contains the public code from the [Gold Lab](https://www.med.upenn.edu/goldlab/).

# Code related to publications
The [Analysis_Archived](https://github.com/TheGoldLab/Analysis_Archived) repository contains code associated with the following publications:
- [The Relative Influences of Priors and Sensory Evidence on an Oculomotor Decision Variable During Perceptual Learning](https://doi.org/10.1152/jn.90629.2008)
- [Relationships between Pupil Diameter and Neuronal Activity in the Locus Coeruleus, Colliculi, and Cingulate Cortex](https://doi.org/10.1016/j.neuron.2015.11.028)
- [Arousal-related adjustments of perceptual biases optimize perception in dynamic environments](https://doi.org/10.1038/s41562-017-0107)
- [A bias–variance trade-off governs individual differences in on-line learning in an unpredictable environment](https://doi.org/10.1038/s41562-018-0297-4)

# Code related to ongoing projects
## Auditory change-point task
- Code to run the experiment lives in [Task_Audio2AFC_ChangePoint](https://github.com/TheGoldLab/Task_Audio2AFC_ChangePoint). This task uses [ToolboxToolbox](https://github.com/ToolboxHub/ToolboxToolbox).
- Code to run simulations and analyze the data lives in [Analysis_Audio2AFC_ChangePoint](https://github.com/TheGoldLab/Analysis_Audio2AFC_ChangePoint) and its documentation is accessible [here](https://thegoldlab.github.io/Analysis_Audio2AFC_ChangePoint/index.html).

## Single change-point dots-reversal task
- Code to run the experiment lives in [Task_SingleCP_DotsReversal](https://github.com/TheGoldLab/Task_SingleCP_DotsReversal). This task uses [ToolboxToolbox](https://github.com/ToolboxHub/ToolboxToolbox).
- Code to analyze data from experiment resides in [Analysis_SingleCP_DotsReversal](https://github.com/TheGoldLab/Analysis_SingleCP_DotsReversal). 

## Databases of _random dots stimuli_ (Python 3)
The [dotsDB](https://github.com/TheGoldLab/dots_db) Python module is currently under development. Its goal is to provide a comprehensive API to create, edit and query from [HDF5](https://www.hdfgroup.org/solutions/hdf5/) databases containing our random dots stimuli.

# Data-collection utilities and tutorials
Our in-house, Matlab-based utilities for controlling psychophysical experiments are found in the repository [Lab_Matlab_Control](https://github.com/TheGoldLab/Lab_Matlab_Control) and typically referred to collectively as _SnowDots_. 

The available documentation for _SnowDots_ is organized according to this [Table of Contents](https://thegoldlab.github.io/SnowDotsDocumentation/index.html) and includes [full, automatically generated documentation from the class definitions](https://thegoldlab.github.io/SnowDotsDocumentation/DoxyDocs/index.html) plus tutorials.

Because _SnowDots_ requires several other dependencies to run properly, it is most conveniently used with [ToolboxToolbox](https://github.com/ToolboxHub/ToolboxToolbox). _SnowDots_ is listed in the public [ToolboxRegistry](https://github.com/ToolboxHub/ToolboxRegistry). Click [here](https://github.com/TheGoldLab/SingleCP_DotsReversal_Task/tree/psychophys_tests) for an example task code that uses _SnowDots_ in this way.

# Repositories not listed above
- [Lab_Matlab_Utilities](https://github.com/TheGoldLab/Lab_Matlab_Utilities): mainly used as a dependency of Lab-Matlab-Control. It is listed in the [ToolboxRegistry](https://github.com/ToolboxHub/ToolboxRegistry).
- [dotsStimExperiments](https://github.com/TheGoldLab/dotsStimExperiments): this is a deprecated repository created to run a few tests on our random dots stimuli.
- [Dots-Reversal-Task-MT](https://github.com/TheGoldLab/Dots-Reversal-Task-MT): _description to come_
- [Oddball](https://github.com/TheGoldLab/Oddball): _description to come_
- [test_repo](https://github.com/TheGoldLab/test_repo): deprecated repository used for tests about our GitHub organization.
- [Rex](https://github.com/TheGoldLab/Rex): _description to come_
