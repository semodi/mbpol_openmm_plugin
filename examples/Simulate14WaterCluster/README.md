Cluster of 14 water molecules
=============================

Example simulation in C++ of a cluster of 3 or 14 water molecules 
using the MBPol force field

The example performs the following operations:

* sets up a system of either 3 or 14 water molecules cluster
* creates and configures all MBPol force field components
* computes the initial state of the system
* runs energy minimization and simulation at constant energy 

## How to compile

* first install OpenMM with the MBPol plugin
* create a `build/` folder under the `Simulate14WaterCluster` folder
* check that `CMakeLists.txt` points to the right `OpenMM` installation folder (the default `/usr/local/openmm` should work unless you installed `OpenMM` in a custom folder)
* run `cmake` in order to setup the `Makefile`:

        cmake ..

* build with running `make` 

## How to run

Execute:

    ./Simulate14WaterCluster
