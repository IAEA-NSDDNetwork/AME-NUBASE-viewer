# AME-NUBASE viewer
Retrieves and displays AME2020 and NUBASE2020 data entries. 

AME-NUBASE viewer is part of the [ENSDF Analysis and Utility Programs](https://nds.iaea.org/public/ensdf_pgm/).

Please address any feedback to Jun Chen chenj@frib.msu.edu

## Change history

#### 2025-08
Bug fixes and improvements

#### 2025-05
Bug fixes and improvements

#### 2025-03
Bug fixes and improvements

#### 2024-08
Bug fixes and improvements

Added a tool for automatically calculating all related Q-values based on input of one or multiple new mass excesses and existing AME mass excesses of other nuclei. For example, new masses of 65As and 61Ga are available after AME2020 and should be used to update all related Q-values of 65As, such as Q(ec), Q(ecp), Q(a), S(n), S(2p). To open this Q-value updating tool, right click on any blank area of the AME main window and select "open Q-Value updater". 

It can also generate an ENSDF Q record line with the updated Q-values as well as corresponding Q comments about how the updated Q-values are deduced. Click "make Q ENSDF lines" button after making the updates to generate the Q record line and comments, which will be automatically copied into the system clipboard, ready to be pasted into an ENSDF Adopted dataset. 

Simple instruction for using this Q-value updater tool:
1. after the updater window is open, type the nucleus name of interst in the "Input Nuclide" field, like 65As, and press enter. All neighboring nuclei that are relevant to Q-values of 65As will be displayed at their corresponding positions as they are in the chart of nuclide.
2. type the new mass excess value of a nuclide in its corresponding "New M.E." field. If a Q line and comments are needed, click "ref" label by the "New M.E." field to enter the NSR keynumber for the reference of the new mass measurement. That keynumber is needed for making the Q comment.
3. click "calculate" button to calculate and display all Q-values of 65As.
4. click "make Q ENSDF lines" to make a Q record line and relevant Q comments, which will be copied into the system clipboard.
5. open the corresponding ENSDF dataset of Adopted Levels,Gammas in a text editor, remove the old Q record line and comments, and paste new Q line and comments there by "Ctrl+V". 

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
