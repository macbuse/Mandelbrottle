
# The Mandelbrottle

This is a shameless ripoff of an idea of Gabriel and Bernat 
at the [ICERM](https://icerm.brown.edu/programs/sp-f19/)
Illustrating Math program.

They worked out how to use [chimera](https://www.cgl.ucsf.edu/chimera/)
to get an STL file from a multi image TIFF by stacking layers of voxels.
Below we build a TIFF for importing in Chimera.

Each level set is a Julia set with the corresponding $c$
in $f_c(z) = z^2 + c$ on a circle passing through 0.


![finished](https://github.com/macbuse/Mandelbrottle/blob/master/mandelbrottle.jpg)


---


## Technical notes


1. If you have have Anaconda and you shouldn't need to install anything except maybe svgpathtools


1. Download the *json* files that contain the profile curve for a bottle
and put them on your Desktop.

1. Download Chimera. Theoretically we can use Chimera directly from a notebook
with [this package](https://pypi.org/project/pychimera/0.1.11/)
but it only works with python 2.7 and I'm tired of building environments.

1. If you just want the TIFFs, don't want to have all the fun and/or pain, and know some skimage you can extract the layers from this GIF probably ;) 

![slices](https://github.com/macbuse/Mandelbrottle/blob/master/pp.gif)



