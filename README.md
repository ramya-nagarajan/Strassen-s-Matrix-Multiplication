# Strassen-s-Matrix-Multiplication
Parallel version of Strassen's matrix multiplication 

Can be run from command line with the gcc compiler. The number of OpenMP threads(OMP_NUM_THREADS) can be set beforehand. 

Utilized the qsub command to get the node from Big Red II supercomputer(Indiana University's supercomputer).

`gcc strassen_omp.c -o strassen_omp`

