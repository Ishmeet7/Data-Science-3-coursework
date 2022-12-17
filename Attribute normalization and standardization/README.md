### Dataset

Here we use Pima Indians Diabetes csv file.This data-set is originally
from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to
predict based on diagnostic measurements whether a patient has diabetes. Several constraints
were placed on the selection of these instances from a larger database. In particular, all patients
here are females with at least 21 years old of Pima Indian heritage. It contains following 9
attributes.

pregs: Number of times pregnant

plas: Plasma glucose concentration 2 hours in an oral glucose tolerance test

pres: Diastolic blood pressure (mm Hg)

skin: Triceps skin fold thickness (mm)

test: 2-Hour serum insulin (mu U/mL)

BMI: Body mass index (weight in kg/(height in m)^2)

pedi: Diabetes pedigree function

Age: Age (years)

class: Class variable (0 or 1)

### Task
Write a python program (with pandas)to read the given data and do the following:

1. Consider only first eight attributes (i.e., excluding class) for the analysis. Replace the
outliers (if at all any) in any attribute with the median of the respective attributes and do
the following on outlier corrected data:

a. Do the Min-Max normalization of the outlier corrected data to scale the attribute
values in the range 5 to 12. Find the minimum and maximum values before and
after performing the Min-Max normalization of the attributes.

b. Find the mean and standard deviation of the attributes of the outlier corrected
data. Standardize each selected attribute using the relation 𝑥̂n= (xn − μ)/σ where μ
is mean and σ is standard deviation of that attribute. Compare the mean and
standard deviations before and after the standardization.
