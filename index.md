<a href="http://www.youtube.com/watch?feature=player_embedded&v=VOPyBHsjI6g" target="_blank"><img src="http://img.youtube.com/vi/VOPyBHsjI6g/0.jpg" alt="SMRL tool" width="540" height="380" border="10" /></a>

<a href="http://www.youtube.com/watch?feature=player_embedded&v=9kx6u9LsGxs" target="_blank"><img src="http://img.youtube.com/vi/9kx6u9LsGxs/0.jpg" alt="SMRL tool" width="540" height="380" border="10" /></a>

## Overview 

Security testing detects vulnerabilities in software systems and verifies that their data and resources are protected from attackers. However, it suffers from the well-known oracle problem, which refers to the challenge, given an input for a system, of distinguishing correct from incorrect behavior. In many situations where potential vulnerabilities are tested, a test oracle may not exist, or it might be impractical due to the many inputs for which specific oracles have to be defined.

We propose a metamorphic testing approach that alleviates the oracle problem in security testing. It enables engineers to specify a workable number of metamorphic relations that capture security properties of the system and automatically test the system to detect vulnerabilities based on those relations. In addition, we provide a catalog of 22 system-agnostic, metamorphic relations to automate security testing in Web systems. The approach automatically detected 100% and 75% of the targeted vulnerabilities affecting an industrial system and a leading open source system (Jenkins), respectively.

The approach will be presented at IEEE International Conference on Software Testing, Verification and Validation (ICST) 2020. Our replicability package and the toolset are available at https://zenodo.org/record/4752931 (https://doi.org/10.5281/zenodo.4752931).

## Download


### SMRL Toolset

We provide the whole SMRL toolset in a replicability package available at https://zenodo.org/record/4752931 (https://doi.org/10.5281/zenodo.4752931).

A newer replicability package is available at https://zenodo.org/record/7702754#.ZCrt1_bMKUk (https://zenodo.org/record/7702754#.ZCrt1_bMKUk).

We suggest to follow the replicability script to install SMRL.

The replicability package includes a version of Eclipse for Linux with SMRL already installed in it. 



### SMRL Eclipse Plugin

You can install the SMRL Eclipse plug-in in your current Eclipse configuration.

The SMRL Eclipse plug-in depends on XText 2.17+

It can be installed following the standard plugin installation procedures, from the zip archive reachable at the following URL [https://zenodo.org/record/5562254/files/SMRL-Eclipse-Plugins.zip?download=1](https://zenodo.org/record/5562254/files/SMRL-Eclipse-Plugins.zip?download=1).

### Source code

SRML source code is available on github.

SMRL Library: [https://github.com/SNTSVV/SMRL_Library/](https://github.com/SNTSVV/SMRL_Library/)

SMRL Eclipse plug-in: [https://github.com/SNTSVV/SMRL_EclipsePlugin/](https://github.com/SNTSVV/SMRL_EclipsePlugin/)



