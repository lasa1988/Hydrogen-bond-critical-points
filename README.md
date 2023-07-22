# Electron density at the hydrogen bond critical point
DFT directory: Gaussian 16 input for single point calculations with B3LYP, starting from the structures optimized with MP2. For the rest of the DFAs it is the same input, you just have to change the name of the DFA in the third line. The wfx file is printed, needed to get the hydrogen bond critical points.

G16 directory: Gaussian input 16 to optimize the geometry, obtain the frequencies and print the wave-function file (wfx). The wfx file is needed to get the hydrogen bond critical points.

GPAUM directory: GPUAM inputs that reads the mgf and wfx files from MOPAC 2016 and Gaussian 16 respectively. These inputs are valid to search for bond critical points.

MOPAC2016 directory: MOPAC 2016 inputs to optimize only the hydrogen atoms with PM7(H), and single point calculation, starting from the structures optimized with MP2. The mgf file is printed, needed to get the hydrogen bond critical points.
