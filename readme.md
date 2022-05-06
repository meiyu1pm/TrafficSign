## what I am predicting?
I am predicting a row in the form: id, class,x1,y1,x2,y2 for each image where x1,y1,x2 and y2 are the corner coordinates in pixels of the bounding box of the object to localize.

## Files provided
- train.csv - The training set: A set of image paths and ground truth labels for class and bounding box.
- test.csv - The test set: A set of image paths without ground truth predictions.
- sample.csv - A sample submission file in the correct format. This shows you how your submission file should look.

## Columns
- id - Identification of png image in dataset.
- new_path - Path to png image in dataset.
- class - Number from 0-4 that defines the class of the sign.
- x1 - X coordinate of bounding bottom box corner.
- y1 - Y coordinate of bounding bottom box corner.
- x2 - X coordinate of bounding top box corner.
- y2 - Y coordinate of bounding top box corner.
