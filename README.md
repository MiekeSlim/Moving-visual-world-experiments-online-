# Moving visual world experiments online? 

Experiment scripts accompanying the paper *Moving visual world experiments online? A web-based replication of Dijkgraaf, Hartsuiker, and Duyck (2017) using PCIbex and WebGazer.js* by Mieke Sarah Slim and Robert J. Hartsuiker.

Note that there are two branches in this repository: One for the fixation task (Experiment 1 in the paper) and one for the web-based replication of Dijkgraaf, Hartsuiker, and Duyck's experiment (Experiment 2 in the paper). You can easily import the files of each experiment into the PCIbex Farm by syncing one of the branches in the Farm ([see the how-to on the PCIbex website](https://doc.pcibex.net/how-to-guides/github/)) using this link: [https://github.com/MiekeSlim/Moving-visual-world-experiments-online.git](https://github.com/MiekeSlim/Moving-visual-world-experiments-online.git). 

This experiment is programmed and implemented in *PennController for IBEX* (*PCIbex*, Zehr & Schwarz, 2018) and uses the *[WebGazer.js](https://webgazer.cs.brown.edu/)* algorithm to track the participants' eye-movements using the webcam. Some knowledge of how PCIbex works is required to understand these scripts. If you want to use this script, it is highly recommended to first study the PCIbex documentation ([https://doc.pcibex.net/](https://doc.pcibex.net/)), go through both the [basic](https://doc.pcibex.net/basic-tutorial/) and [advanced](https://doc.pcibex.net/advanced-tutorial/) tutorials, and study the [how-to guide on collecting eye tracking data](https://doc.pcibex.net/how-to-guides/collecting-eyetracking-data/) written by the PCIbex developers.

The scripts in this repository are most recently tested in PCIbex 2.0. Note that the calibration procedure in this newer version of PCibex is slightly different than described in the paper. However, the underlying logic of the calibration is similar. I cannot garantuee that I will maintain the script up-to-date to be used in the later versions of PCIbex. Nevertheless, if you have any questions or spot any bugs, please get in touch via <mieke.slim@ugent.be>, and I will try to make the time to troubleshoot.
