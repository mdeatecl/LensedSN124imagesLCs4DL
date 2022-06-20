The LensedSN124imagesLCs4DL repository contains the data accompanying the manuscript "Deep Learning Unresolved Lensed Lightcurves", arXiv:2202.11903 by Mikhail Denissenya & Eric V. Linder.

There are 3 data sets used in Sec. 2 of the paper each containing  10 000 simulated lightcurves in g, r, i bands: 
 
 * T124_gslsne_data.zip   - 1, 2, and 4 image systems;
 * T2_gslsne_data.zip  - 2 image systems;
 * T4_gslsne_data.zip  - 4 image systems. 

The system ID is indicated in the filename after sys_ keyword.  The ASCII files in the zip archives start with a header listing the number of images n_images in the system and time delays relative to the first image for n_images>1. The lightcurve data are stored in columns:

1st col - observation time, days

2nd col - total flux (+noise)

3rd col - total flux measurement errors

4th col - 1st image flux

5th col - 2nd image flux (for n_images>1)

6th col - 3rd image flux (for n_images>2)

7th col - 4th image flux (for n_images>2)

Contact email: mikhail.denissenya@nu.edu.kz
