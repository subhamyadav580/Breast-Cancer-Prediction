# Breast-Cancer-Prediction
Predict whether the cancer is benign or malignant

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This database is also available through the UW CS ftp server:
ftp ftp.cs.wisc.edu
cd math-prog/cpo-dataset/machine-learn/WDBC/

Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Attribute Information:

<ol type='1'>
  <li>ID number</li>
  <li>Diagnosis (M = malignant, B = benign) 3-32)</li>
</ol>

Ten real-valued features are computed for each cell nucleus:
<ol type='a'>
<li>radius (mean of distances from center to points on the perimeter)</li>
<li>texture (standard deviation of gray-scale values)</li>
<li>perimeter</li>
<li>area</li>
<li>smoothness (local variation in radius lengths)</li>
<li>compactness (perimeter^2 / area - 1.0)</li>
<li>concavity (severity of concave portions of the contour)</li>
<li>concave points (number of concave portions of the contour)</li>
<li>symmetry</li>
<li>fractal dimension ("coastline approximation" - 1)</li>
</ol>

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant
