Rotational Symmetry Detection Image Data Set
============================================

Purpose
-------

This data set can be used to evaluate rotational symmetry detection
algorithms. It was first presented at VISAP 2013 and is used and
described in the paper

>  C. Dalitz, R. Pohle-Froehlich, T. Bolten:
>  "Detection of Symmetry Points in Images."
>  International Conference on Computer Vision Theory and Applications
>  (VISAPP), pp. 577-585, 2013
>  https://doi.org/10.5220/0004179405770585


Contents
--------

The data set consists of 159 images of size 600×400, containing 
27 different subjects. Each subject is shown in different perspectives 
and both in context and in detail. For each image *xyz.png*, there
are three corresponding ground truth files:

 - *xyz.type*

   Contains two lines:
    o first line is 'normal' or 'detail', where 'detail' images mainly
	  show only the symmetric object, while 'normal' images also show
	  an embedding scenery.
	o second line is 'front', 'light skew', or 'strong skew', indicating
	  the degree of proportional skew in the top symmetry.

 - *xyz.symmetries*

    All "obvious" rotational symmetries as a bracketed nested list
    of tuples. Each tuple is of the following format:

        ((center_x, center_y), (diag_1, diag_2), angle)

    where angle is the rotation angle of the ellipse long axis.

  - *xyz.axial_rotational*

    Lists for some points with point reflection symmetries
    whether they are axial symmetries ('a') or rotational symmetries ('r').


Copyright and Where to Get It
-----------------------------

Copyright 2013 by
Tobias Bolten and Christoph Dalitz
Institute for Pattern Recognition
Niederrhein Unversity of Applied Sciences
47805 Krefeld, Germany

The second author can be contacted by email over
christoph (dot) dalitz (at) hsnr (dot) de

The latest version of this data set is available from:
 - https://github.com/cdalitz/symmetry-visapp13/
 - https://lionel.kr.hs-niederrhein.de/~dalitz/data/visapp13/

All images in this data set are copyrighted by Tobias Bolten.
Permission is granted to use them freely for research purposes
and to include individual images into publicatons, provided
you give reference to the following paper:

>  C. Dalitz, R. Pohle-Froehlich, T. Bolten:
>  "Detection of Symmetry Points in Images."
>  International Conference on Computer Vision Theory and Applications
>  (VISAPP), pp. 577-585, 2013

