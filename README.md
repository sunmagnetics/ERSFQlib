# ERSFQlib
Author: Lieze Schindler
ERSFQ cell library V0.1

This cell library was developed under the IARPA SuperTools/ColdFlux contract via the U.S. Army Research Office grant W911NF-17-1-0120. The aim was to create a generic RSFQ cell library which can be used by circuit designers. 
The libraries were developed using open-source tools - WRspice and XIC. 

The ERSFQ cell library consists of the JTL, DFF, SPLIT, MERGE, NOT, AND2, OR2, XOR and NDRO cells. Each cell is based on the RSFQ equivalent. The bias current is determined through a Josephson Junction with the same critical current as the bias current in the RSFQ equivalent. Feeding JTLs are used to provide voltage and phase stability throughout the circuit. 