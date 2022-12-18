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

---
### Task

1. Generate 2-dimensional synthetic data of 1000 samples and let it be denoted as data
matrix D of size 2x1000. Each sample is independently and identically distributed with
bi-variate Gaussian distribution with user entered mean values, μ = [0, 0]T
and covariance
matrix, Σ = [[13 −3 ][−3 5]]

     Perform the following.   

     a. Draw a scatter plot of the data samples.

     b. Compute the eigenvalues and eigenvectors of the covariance matrix and plot the
  Eigen directions (with arrows/lines) onto the scatter plot of data

     c. Project the data on to the first and second Eigen direction individually and draw
  both the scatter plots superimposed on Eigen vectors

     d. Reconstruct the data samples using both eigenvectors, say it 𝐃̂. Estimate
  the reconstruction error between 𝐃̂ and D using Euclidean distance.

2. Data frame used for PCA include only first 8 attributes (class attribute is excluded).
Perform principal component analysis (PCA) on outlier corrected standardized data and do the followings:

      a. Reduce the multidimensional (d = 8) data into lower dimensions (l = 2). Print the
      variance of the projected data along the two directions and compare with the
      eigenvalues of the two directions of projection. Also show the scatter plot of
      reduced dimensional data.

      b. Plot all the eigenvalues in the descending order.

      c. Plot the reconstruction errors in terms of Euclidean distance considering the
      different values of l (=1, 2, ..., 8). The x-axis is the l and y-axis is reconstruction
      error in Euclidean distance. Print the covariance matrix of each of the l dimensional representations (l = 2, 3, ..., 8).

      d. Give the covariance matrix for the original data (8-dimensional). Compare the
      covariance matrix for the original data (8-dimensional) with that of the covariance
      matrix for 8-dimensional representation obtained using PCA with l = 8.
