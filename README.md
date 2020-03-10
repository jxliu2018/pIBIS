# pIBIS - parallel Integrated Biosphere Simulator

This is the parallel IBIS program that runs on Argonne ALCF Theta.
IBIS core FORTRAN code is used to generate a library file (libibis.a).
IBIS parallel program (pibis_p_cray) is written in C, which calls the ibis library.

Parameter files include:
paramsx.can, paramsx.crp, paramsx.dis, paramsx.ghg, paramsx.luc,
paramsx.map, paramsx.scl, paramsx.soi, paramsx.veg

The IBIS version (2.5) Foley (1996) is archived in https://daac.ornl.gov/cgi-bin/dsviewer.pl?ds_id=808.
For model equations, check journal publications:

1. Foley JA, Colin PI, Ramankutty N, Levis S, Pollard D, Sitch S, Haxeltine A. An integrated biosphere model of land surface processes, terrestrial carbon balance, and vegetation dynamics. Global Biogeochem Cycles. 1996;10:603–28.

2. Kucharik CJ, Foley JA, Délire C, Fisher VA, Coe MT, Lenters JD, Young-Moiling C, Ramankutty N, Norman JM, Gower ST. Testing the performance of a dynamic global ecosystem model: Water balance, carbon balance, and vegetation structure Global Biogeochemical Cycles. 14: 795-825. DOI: 10.1029/1999GB001138

3. Liu J, Price DT, Chen J. Nitrogen controls on ecosystem carbon sequestration: a model implementation and application to Saskatchewan, Canada. Ecol Model. 2005;186:178–95.

--For questions, please send Email to jxliu@usgs.gov--
