NIST Public Data Resource:
Experimental data sets for viscosity and surface tension of binary mixtures at
the temperatures (293.15 to 323.15) K and the pressures (99.325 to 103.325) kPa
Version 1.0.0
DOI: https://doi.org/10.18434/mds2-2962


Contact:
  Andrei F. Kazakov
    andrei.kazakov@nist.gov

Description:

This is a research data set extracted from NIST Standard Reference Database 103b
and contains raw experimental data for viscosity and surface tension of binary
mixtures.

--------------
Data Use Notes
--------------

This data is publicly available according to the NIST statements of
copyright, fair use and licensing; see
https://www.nist.gov/director/copyright-fair-use-and-licensing-statements-srd-data-and-software

You may cite the use of this data as follows:
Andrei F. Kazakov (2022), Experimental data sets for viscosity and surface
tension of binary mixtures at the temperatures (293.15 to 323.15) K and the
pressures (99.325 to 103.325) kPa, Version 1.0.0, National Institute of
Standards and Technology, https://doi.org/10.18434/mds2-2962 (Accessed: [give
download date])

-------------
Data Overview
-------------
The data set contains raw (unevaluated) experimental data collected from the original literature sources
for viscosity and serface tension of binary mixtures at the temperatures (293.15 to 323.15) K and the
pressures (99.325 to 103.325) kPa. The distribution contains 5 files: visc.dat, surften.dat,
compounds.sdf, refs.dat, and this README.

**visc.dat**
Viscosity data are given in a tab-delimited text file visc.dat.
The order of columns is as follows:
ID of compound 1
ID of compound 2
mole fraction of compound 1
temperature (K)
pressure (kPa)
viscosity (Pa*s)
uncertainty (Pa*s)
reference ID

**surften.dat**
Surface tension data are given in a tab-delimited text file surften.dat.
The order of columns is as follows:
ID of compound 1
ID of compound 2
mole fraction of compound 1
temperature (K)
surface tension (N/m)
surface tension uncertainty (N/m)
reference ID

**compounds.sdf**
The compound IDs used in both data files are defined in SDfile compounds.sdf.
For the SDfile format reference, please see 
Dalby A, Nourse JG, Hounshell WD, Gushurst AK, Grier DL, Leland BA, Laufer J. 
Description of several chemical structure file formats used by computer programs 
developed at Molecular Design Limited. J. Chem. Inf. Comp. Sci. (1992) 32(3), 244-55.
IMPORTANT NOTE:
Our compound indexing is designed to accommodate what was actually used in a
given experiment. This includes defined (partially or in-full) stereo features 
(relative or absolute). We do utilize the chiral flag in the mol block
(1 – for absolute, 0 – for relative or “no stereo present or defined”). Ignoring this
when converting to different identifiers may lead to representation collisions.

**refs.dat**
The reference IDs used in both data files are given in a tab-delimited text file refs.dat


---------------
Version History
---------------

1.0.0 (this version)
  initial release


