The complete CVL Single Digit dataset consists of 10 classes (0-9) with 3,578 samples per class. For the HDR competition, 7,000 digits (700 digits per class) of 67 writers have been selected as training set. The validation set is of equal size with a different set of 60 writers. The validation set may be used for parameter estimation and validation but not for supervised training. The evaluation set consists of 2,178 digits per class resulting in 21,780 evaluation samples of the remaining 176 writers.

Normalization: 
The images are converted to grayscale and size normalized similar to the MNIST database is applied, i.e. scaled to 20x20 by preserving the aspect ratio and then the centroid of the image is placed on the center of a standard plane of size 28x28. Finally, a histogram equalization is applied.

File Naming:
The numbers before the first minus are the respective class labels succeeded by an unique ID.

	* 2-0202-21-04.png is an image that contains a single digit with groundtruth 2
	* 135579-0001-10.png is an image that contains the digit string 135579

