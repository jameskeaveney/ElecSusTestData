# ElecSusTestData

This repository provides example data to be used with ElecSus.
Please see the new (2017) paper for full details.

For all files, the first column is the experimental detuning axis in GHz, the second column is the spectroscopic signal at that detuning.

The data can be read into python using numpy, for example:

> data = np.loadtxt(filename, delimiter=',').T

where the .T on the end is the transpose of the array that is received from np.loadtxt(); the detuning axis will then be data[0], the data axis is data[1].