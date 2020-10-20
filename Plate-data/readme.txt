
"Rectangular Stone Orders.txt" is the real order from stone enterprises. Its data format is as follows:

The first line format:  1,Number of types, 2,number of rectangles
Subsequent line format:  1,Sequence number 2,Length (mm) 3,Width (mm) 4,Quantity level

"Plate A-F.txt" is the real  stone plates that have been labeled manually  with available area and the defects. Its data format is as follows:

The first line format: Polygon count (including plate boundaries and defects)
Subsequent line format（ each Polygon）:  
			the number of Polygon vertices
			type(0：boundaries ， 1：defects))
			coordinates of each Polygon vertices （ X axis (mm) Y axis (mm)）
NOTE:	If it is a boundary, then the position of vertex coordinates is marked counterclockwise。
	If it is a defect, the vertex coordinates are marked clockwise