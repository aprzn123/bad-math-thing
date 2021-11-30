# Unit Square
The unit square is the square of side length 2. This is because its length is greater than 

# On vs In
- Point $p$ is considered to be **on** shape $S$ if p is on the border of $S$.
- Point $p$ is considered to be **in** shape $S$ if p is inside of the border of $S$.

# Center
Given a shape $S$, the center $c$ is an arbirtray point. Often it is within the shape, but not necessarily.

# Circumference
For the purposes of this project, we use circumference as a synonym for perimeter.

# Radius
The radius $r$ of point $p$ on shape $S$ with center $c$ is the distance from $r$ to $c$. If the ray from $p$ to $c$ initially points *into* the shape, $r$ is positive. If the ray initially points *out from* the shape, $r$ is negative.

# Diameter
The diameter $d$ of point $p$ on shape $S$ with center $c$ can be found through the following procedure:
- Cast a ray from $p$ towards $c$
- If the ray points into $S$:
	- The diameter is the distance between $p$ and $q$
- If not:
	- Cast a ray from $p$ directly away from $c$.
	- If this ray points into $S$, then the diameter is the distance between $p$ and $q$.
	- Otherwise, the diameter is undefined at this point.

# Average Radius
The average radius is the the path integral of the radius over the border of the shape, divided by the circumference.