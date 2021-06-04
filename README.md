# Machine-Learning-Project
Machine Learning training, testing, and deployment of HDMA data.

The attached Project_Final.ipynb file is executable in Jupyter Notebook, running Python 3. 

The raw data set to which this code was applied is too large to be uploaded to GibHub, and subsequently can be found here:
https://ffiec.cfpb.gov/data-browser/data/2019?category=nationwide&leis=KB1H1DSPRFMYMCUFXT09,B4TYDEB6GKMZO031MB27,E57ODZWZ7FF32TWEFA76,7H6GLXDRUGQFU57RNE97,549300XCVBRR56D08F03
by clicking the download link. To enable this file to be edited as per the intended program - please save this raw downloaded data as 'bankdata.csv'.

The .ipynb file pre-processes this data and outputs a smaller file for observation as 'applications_cleaned.csv'.

Two tests are undertaken in the form of a Two sample Z-test, and a Chi Squared test with testable and interpretable outcomes displayed. 

Additionally, this code goes through the process of tuning, training, and testing a Machine Learning model able of predicting mortgage loan application approval or denial on the given data at an accuracy of ~81%.

For information please contact the Author:
Liam Peart
@ liam.peart@hotmail.com or s3540465@student.rmit.edu.au

Some functions/parts of this code have been adapted from previous Scikit learn investigations and tutorials provided by Dr. Vural Aksakalli:
https://github.com/vaksakalli
