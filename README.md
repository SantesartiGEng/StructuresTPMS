# StructuresTPMS
An algorithm implemented in a MATLAB script to optimize via the functional grading the mechanical properties of TPMS structures (e.g. stiffness). Structures are generated through TPMS Designer toolbox (ref. Jones, A., Leary, M., Bateman, S., &amp; Easton, M. 2021. TPMS designer: A tool for generating and analyzing triply periodic minimal surfaces. Software Impacts, 10, 100167.)
The optimisation algorithm involves: 
1) the characterisation of the isovalue-relative density relationship of the structure;
2) the mechanical characterisation of the structural stiffness via mechanical testing, FEM analysis, or data found in the literature;
3) the fitting of the relative density-mechanical property (e.g. stiffness) relationship using the Gibson-Ashby model; 
4) the imposition of the desired optimisation relationship and functional grading across space; 
5) the derivation of the inverse solution of the optimised isovalue as a function of space.
