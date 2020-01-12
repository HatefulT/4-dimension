# 4-dimension
My 4d lab  

Tesseract is 4-dim supercube with 16 points and 32 edges.  

Just read [Wikipedia](https://en.wikipedia.org/wiki/Tesseract#2D_orthographic_projections) to understand what it is.  

To build a tesseract we copy the original 3-dimensional cube in the 4-dimension and connect each vertex of the original cube with the corresponding vertex of the new cube.  

For clarity, I highlighted the original cube in red and its copy in blue.  

# How projection work
First, we project our tesseract on 3-d space. 

Each point is its position vector v in 4-d space.  

To project it on 3-d space we need to divide X, Y, Z values by W value. So simple, right?  

Next, we need to project our 3-d projection on 2-d plane.  

All we need to do is divide x and y by z and multiply by some factor that is responsible for the viewing angle.  


# How rotations work

All rotations are made parallel to the planes. The easiest way to rotate a vector is to create a rotation matrix and multiply the vector by this matrix.

[Wikipedia](https://en.wikipedia.org/wiki/Rotation_matrix) ;)

