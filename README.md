# StructuresTPMS
An algorithm implemented in a MATLAB script to optimize via the functional grading the mechanical properties of TPMS structures (e.g. stiffness). 
Structures are generated through TPMS Designer toolbox (ref. Jones, A., Leary, M., Bateman, S., &amp; Easton, M. 2021. TPMS designer: A tool for generating and analyzing triply periodic minimal surfaces. Software Impacts, 10, 100167.)

The optimisation algorithm involves: 
1) the characterisation of the isovalue-relative density relationship of the structure;
2) the mechanical characterisation of the structural stiffness via mechanical testing, FEM analysis, or data found in the literature;
3) the fitting of the relative density-mechanical property (e.g. stiffness) relationship using the Gibson-Ashby model; 
4) the imposition of the desired optimisation relationship and functional grading across space; 
5) the derivation of the inverse solution of the optimised isovalue as a function of space.

In the Case A, a TPMS structure analysed and described in the literature was optimised (see the description file TPMS_structures_StiffnessGrading_20260209.pdf) (date 09-02-2026).

In the Case B, the optimisation was performed considering a femoral prosthesis as a possible application. Specifically, the generated structure has a relative density of 26% at the initial extremity, corresponding to the porosity of the internal trabecular bone tissue, and a relative density of 85% at the final extremity, corresponding to the porosity of the external cortical bone tissue. Subsequently, using the developed algorithm, the stiffness was optimised by imposing a linear variation between the two extremities, controlling the isovalue and the relative density (see the description file TPMS_structures_StiffnessGradingOpt_20260410.pdf) (date 10-04-2026).

DOI
https://doi.org/10.5281/zenodo.20114451
