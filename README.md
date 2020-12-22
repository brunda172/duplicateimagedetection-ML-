# duplicateimagedetection-ML-
Duplicate Image detection using machine learning with SIFT and Hashing algorithm
1.	Image Enhancement:
Histogram equalisation:
The appearance and features of an image depend crucially on the image contrast.
Though primarily determined by the properties of the imaging modality and adjustment
of the imaging system, the displayed contrast can be substantially influenced by applying
simple contrast transforms. Histogram equalisation (HE) is very popular for image
enhancement due to its simplicity and good performance in almost all types of images.

2.	Feature Extraction: 
SIFT:
The scale-invariant feature transform SIFT is a feature detection algorithm in computer vision to detect and describe local features in images. ...
SIFT keypoints of objects are first extracted from a set of reference images and stored in a database.
It locates certain key points and then furnishes them with quantitative information (so-called descriptors) which can for example be used for object recognition.

                                  4.1   Algorithm: 

Step 1: Select the query image which is going to be detect the duplicate image
Step 2: Enhance the query image(original image)
Step 3: Feature are extracted of both query image as well as web image
Step 5: Compare the features of query image and web image
Step 6: Apply Hashing algorithm for all images
Step 7: Duplicate images will be displayed with original image
