# AME-NUBASE viewer
Retrieves and displays AME2020 and NUBASE2020 data entries. 

AME-NUBASE viewer is part of the [ENSDF Analysis and Utility Programs](https://nds.iaea.org/public/ensdf_pgm/).

Please address any feedback to Jun Chen chenj@frib.msu.edu

## Change history

#### 2024-02
Bug fix

#### 2023-10
Added a feature for calculating proton and neutron pairing-gap energies, e.g.,type
251MD:DP3:DP4 for Dp(3) and Dp(4) of 251Md calculated using mass-excess by default. Type
251MD:DP3-SP and 251MD:DP3-BE for calculations using S(p) and binding energy, respectively.

#### 2023-05
Added a new feature for calculating mass difference using an input mass-excess value, e.g.,
77CO=-21910(234.5)-75NI-2*n for Q(B-2N) of 77Co using an input mass-excess -21910(234.5) for 77Co.

#### 2023-04
Bug fix

#### 2022-11
Use updated NUBASE2020 file from Filip Kondev with a few typos in the previous file being fixed.  

#### 2022-06
New features are added, like doing a simple arithmetic calculation based on an input expression, e.g., 77CO-75NI-2*n for Q(B-2N) of 77Co. See the updated instruction (in the program window) for details. 

#### 2021-10
A simple instruction is included in the program and can be popped out by clicking on the "?" mark on the program window

## Disclaimer

Neither the author nor anybody else makes any warranty, express or implied, or assumes any legal liability or responsibility for the accuracy, completeness or usefulness of any information disclosed, or represents that its use would not infringe privately owned rights.
