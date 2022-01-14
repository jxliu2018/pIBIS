# pIBIS - parallel Integrated Biosphere Simulator

The parallel IBIS program can run on PCs and super computers (e.g. Argonne ALCF Mira/Theta). IBIS FORTRAN code is used to generate a library file (libibis.a). IBIS parallel program (pibis) is written in C, which calls the libibis.a.

The "pibis_CA_package.011322.tar.gz" in the data folder a real 1-km California data/model set with a step-by-step guide. You can run it on a Linux laptop with 4 physical CPUs if you choose very coarse spatial sampling. Pre- and post-prossessing programs are also included so you can analyze your results in many ways. And, You can publish your study with this model/dataset! 

1-km California map is  1261 rows by 747 columns. Run pibis with coarse spatial sampling (e.g. 37km by 37km) on a laptop with 4 cpus will finish in an hour. The output map is 30 row by 20 col. Of course if you want to do a 1km California simulation, you need to run the model on a super computer. The code here can use 100,000 cores on ALCF Theta

The IBIS version (2.5) Foley (1996) is archived in https://daac.ornl.gov/cgi-bin/dsviewer.pl?ds_id=808.
For model equations, check journal publications:

1. Foley JA, Colin PI, Ramankutty N, Levis S, Pollard D, Sitch S, Haxeltine A. An integrated biosphere model of land surface processes, terrestrial carbon balance, and vegetation dynamics. Global Biogeochem Cycles. 1996;10:603–28.

2. Kucharik CJ, Foley JA, Délire C, Fisher VA, Coe MT, Lenters JD, Young-Moiling C, Ramankutty N, Norman JM, Gower ST. Testing the performance of a dynamic global ecosystem model: Water balance, carbon balance, and vegetation structure Global Biogeochemical Cycles. 14: 795-825. DOI: 10.1029/1999GB001138

3. Liu J, Price DT, Chen J. Nitrogen controls on ecosystem carbon sequestration: a model implementation and application to Saskatchewan, Canada. Ecol Model. 2005;186:178–95.

--For questions on pIBIS package, please send Email to jxliu@usgs.gov--
