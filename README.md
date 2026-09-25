# xim_ardra0709
The repository contains the simulation data generated and analysed for the Gorgon-XIM study.

Each folder corresponds to the heavy-ion species indicated by its name. The data are stored in HDF5 format. The X-ray emission data are stored in files named `x00_pPx1-XXXXX.h5`, where `XXXXX` represents the simulation time in seconds. The X-ray emission variable, `Px`, is stored as a cell-centred scalar field on a three-dimensional Cartesian grid with dimensions (121, 121, 121). The three dimensions correspond to the grid indices in the \(X\), \(Y\), and \(Z\) directions, respectively, with each dimension ordered from negative to positive coordinates.
