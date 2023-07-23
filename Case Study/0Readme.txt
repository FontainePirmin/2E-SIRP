1. Coordinates.txt
First row: Coordinates x and y for central clinic
Remaining rows: x and y coordinates for surrounding clinics

2. Instances
The demand for all products, scenarios, clinics and times is written down in this order one below the other.
The text file can be read in C++ with the following command
            
	    DemandClinics101 >> instancename;
	    for (int p = 0; p < P; p++) {
                for (int omega = 0; omega < Omega; omega++) {
                    for (int c = 0; c < Chat; c++) {
                        for (int t = 0; t < T; t++) {
                                DemandClinics101 >> d[p][c][t][omega];
                        }
                    }
                }
            }