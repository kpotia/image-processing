# Image Processing 
This is a workshop on [Image processing](https://datacarpentry.org/image-processing/)  by data carpentry we will use python, jupyter and scikit image for image processing. 

## 0. Introduction
the first concept I am discovering is the Morphometrics

## 1. Image Basic 
 
- In this part of the course I've been introduced to how an image is represented in colors, coordinates and pixels square. 

- Left hand coordinate system. with the origini in the upper left corner, x-axis running to the right, y-axis running down. 

- Scikit-image images are stored as multi-dimensional NumPy arrays. RGB

- Depending on the camera or sensor, various useful pieces of information may be stored in an image file, in the image metadata.


Format	| Compression |	Metadata |	Advantages |	Disadvantages |
BMP |	None |	None |	Universally viewable, high quality|	Large file sizes
JPEG |	Lossy |	Yes	| Universally viewable, smaller file size |	Detail may be lost
PNG |	Lossless |	Yes	| Universally viewable, open standard, smaller file size |	Metadata less flexible than TIFF, RGB only
TIFF |	None, lossy, or lossless |	Yes |	High quality or smaller file size |	Not universally viewable