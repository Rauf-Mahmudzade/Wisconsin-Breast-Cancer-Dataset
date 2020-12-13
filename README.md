# Wisconsin-Breast-Cancer-Dataset
Cancer is the second leading cause of death globally, accounted for an estimated 9.6 million deaths, or one in six deaths according to the World Health Organization (WHO) in 2018. According to the GLOBOCAN 2018 data, one of every four cancer cases diagnosed in women worldwide is breast cancer, and it ranks fifth among the causes of death worldwide.
Despite the increase in the number of medical studies and technological developments that contribute to the treatment of cancer, there are still some problems in the diagnosis of cancer. It is important to make an accurate diagnosis of tumors. Most tumors are the result of benign (non-cancerous) changes within the breast, but if a malignant tumor is diagnosed as benign it will cause serious problems. Early detection of breast cancer and getting modern cancer treatment are the most important strategies to prevent deaths from breast cancer. It is easy to treat early, small, and non-spreading breast cancer successfully. The most reliable way to find breast cancer early is by having regular screening tests.
In this study, public data about breast cancer tumors from University of Wisconsin Hospital were taken and used for data visualization, classification, and machine learning algorithms, which included logistic regression, random forest, and k-nearest neighbor classification algorithms. 

# Dataset
In this study, Wisconsin Breast Cancer (Diagnostic) dataset is used. The dataset is obtainable from UCI machine learning repository. 
. Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
The initial two columns indicate attribute information:
1) ID number
2) Diagnosis (M = malignant, B = benign)

Ten real-valued features are computed for each cell nucleus:
1) radius (mean of distances from center to points on the perimeter)
2) texture (standard deviation of gray-scale values)
3) perimeter
4) area
5) smoothness (local variation in radius lengths)
6) compactness (perimeter2 / area - 1.0)
7) concavity (severity of concave portions of the contour)
8) concave points (number of concave portions of the contour)
9) symmetry
10) fractal dimension ("coastline approximation" - 1)
Ten real-valued features are computed for each cell nucleus:
The mean, standard error, and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.
There are also important conclusions we can draw by just simply analyzing the table:
1) Attribute ID is no use for our classification algorithms.
2) Diagnosis Column indicates the labels of our tumors.
3) Unnamed32 Column only has NaN values, hence will be removed.


