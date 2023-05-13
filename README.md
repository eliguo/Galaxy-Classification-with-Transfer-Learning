# Galaxy-Classification-with-Transfer-Learning

### Description
Galaxies have always been an enigmatic and broad concept for our understanding. Typically, they comprise a bright radiant central point surrounded by millions of tiny stars, which makes it highly difficult to differentiate one galaxy from another with human vision. However, machine learning can aid us in this regard. By employing a convolution neural network (CNN) model trained on a large collection of galaxy images from the “Galaxy10 DECals Dataset,” we can classify galaxy images with high precision, achieving an accuracy rate of 0.74.

### Galaxy10 DECals Datasetß
[Galaxy10 DECals Dataset](https://astronn.readthedocs.io/en/latest/galaxy10.html) is an enhanced version of the original Galaxy10 dataset released by the Galaxy Zoo project. The Galaxy10 dataset was created through the contribution of volunteers who classified around 270,000 images of SDSS galaxies, from which 22,000 were selected and categorized into 10 broad classes based on their shape, using the volunteers’ votes. The Galaxy10 DECals dataset, on the other hand, employs images from the DESI Legacy Imaging Surveys, which offer significantly improved resolution and image quality. The dataset includes 10 broad classes of galaxies that were selected using volunteer votes with more stringent filtering criteria. The DECals dataset represents a more robust and improved version of the Galaxy10 dataset and follows the Hubble Sequence for galaxy classification.

The data has the following subfolders:

```
Galaxy10 dataset (17736 images)
├── Class 0 (1081 images): Disturbed Galaxies
├── Class 1 (1853 images): Merging Galaxies
├── Class 2 (2645 images): Round Smooth Galaxies
├── Class 3 (2027 images): In-between Round Smooth Galaxies
├── Class 4 ( 334 images): Cigar Shaped Smooth Galaxies
├── Class 5 (2043 images): Barred Spiral Galaxies
├── Class 6 (1829 images): Unbarred Tight Spiral Galaxies
├── Class 7 (2628 images): Unbarred Loose Spiral Galaxies
├── Class 8 (1423 images): Edge-on Galaxies without Bulge
└── Class 9 (1873 images): Edge-on Galaxies with Bulge
```
