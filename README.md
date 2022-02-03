# Calculate-Pi
Joma Tech Favorite Coding Interview Question(Solution in Python)

Made this code from Joma Tech's video about his favorite interview question.

How it works:
First, it takes in a number of points. The higher it is, the more accurate PI will be.
It executes the following code the number of points times.

Generates 2 random numbers as (x, y) coordinates
Checks if the distance from the origin is less than 1.
If it is less than 1, the point is part of both the circle and the square. If greater, it is only part of the square.
The ratio of points in the circle divided by points in the square should be equal to the ratio of the area of the circle divided by 4(since it's only 1 quadrant) all divided by the area of the square.
Since the radius is 1, and the square has an area of 1, the formula becomes:
Ratio of Points in the Circle/Ratio of Points in the Square = pi/4
With algebra, this becomes:
(Ratio of Points in the Circle/Ratio of Points in the Square)*4 = pi
https://www.youtube.com/watch?v=pvimAM_SLic <-- Joma Tech Video
I only watched the first part about the method, I did not use his code.
