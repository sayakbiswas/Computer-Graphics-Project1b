Task 3: We have been told that the curves join with C3 continuity which means they also join with C0, C1 and C2 continuities. Using this information, we get the below equations:
(i) Ci,4 = Ci+1,0
(ii) Ci,4 - Ci,3 = Ci+1,1 - Ci+1,0
(iii) Ci,2 - 2*Ci,3 = Ci+1,3 - 2*Ci+1,2
(iv) Ci,1 - 3*Ci,2 + 3*Ci,3 - Ci,4 = Ci+1,0 - 3*Ci+1,2 + 3*Ci+3,3 - Ci+1,4

Simplifying the above using the equations given in the question, we get:
a = 1/3,
b = 7/12,
c = 1/12

So, we get the below formulas for the control points:
(i) Ci,0 = (Pi-2 + 11*Pi-1 + 11*Pi + Pi+1)/24
(ii) Ci,1 = (8*Pi-1 + 14*Pi + 2*Pi+1)/24
(iii) Ci,2 = (4*Pi-1 + 16*Pi + 4*Pi+1)/24
(iv) Ci,3 = (2*Pi-1 + 14*Pi + 8*Pi+1)/24
(v) Ci,4 = (Pi-1 + 11*Pi + 11*Pi+1 + Pi+2)/24

Task 5: Assuming that the 8 points are uniformly distributed on a circle, the resulting curves can approximate a circle but they cannot perfectly fit a circle. The commonly used approximations impose the following constraints on the curves:
(a) The mid points of the Beziers need to be on the circle, and
(b) Their first derivatives should be continuous.
The only way to get to a true circle would be to use an infinite number of really small (zero-length) bezier curves. This basically means, we would be creating infinite number of points on a circle touching each other.
