A:
	encoded identifiers used:
		double average(double *n1,double &n2)
		{
			..........
		}
		---------->  Z7averagePdRd (Pd: pointer double; Rd: reference double)
		
		double average(int n1,float n2)
		{
			..........
		}	
		---------->	 Z7averageif (i: integer; f: float)

B:
	execution result:
	1 8
	4 8
	4 8
	8 8
	
	a character requires 1 byte in memory, 4 byte for an integer number, 4 byte for a float number, 8 byte for a double number.

	But as a pointer, it only varies as the type of computer changes. For instance, 64-bit computers consists of 8 byte, so when we execute the program, the size of a pointer is 8 byte, no matter what kind of pointer it is. 

