# selection_via_PS

supporting material for the paper "Sequence self-selection by cyclic phase separation"
by G. Bartolucci, A. Calaça Serrão, P. Schwintek, A. Kühnlein, Y. Rana, P. Janto, D. Hofer, C. Mast, D. Braun, and C. Weber.

multicomponent_theory contains a python script, selection.ipynb, used for generating the data in Fig. 1 and the input for the mathematica code, selection.nb. The latter is used to produce Fig 5 and the SI figure.

data_analysis contains three folders:
1) Labview VI - Sedimentation analysis contains “sedimentation analysis.llb” containing the VI used to analyse fluorescence images for Figure 2 as well as for Figure 4. Working principle and screenshot are provided in Supplementary Section 7. 

2) Labview VI - Particle Tracker contains “Particle Tracker.llb” with the VI used to measure the sedimentation speed of DNA aggregates using fluorescence images for Supplementary Section 9.

3) Labview VI - Melting Curves contains the VI used to generate Melting curves from the fluorescence data obtained at varying temperature, measured with a thermocycler with read-out.
