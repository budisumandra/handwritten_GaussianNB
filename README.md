# Handwritten Digit Prediction with GaussianNB Algorithm
Identification of handwritten digits involves both locating and identifying characters in an image. Here i used Scikit-Learn’s set of preformatted digits, which is built into the library **from sklearn.datasets import load_digits**.

- Shape : (1797,8,8) --> **1797 samples || 8 pixel x 8 pixel as features**.
- The Features can be find by **flatenning out the pixel arrays** so that we have a length-64 array of pixel values representing each digit.
- Use dimensionality reduction (in this case: _Manifold Learning Algorithm called Isomap_) to visualize each point from 64-D into 2-D space according to give us some good intuition into how well various numbers are separated
in the larger 64-dimensional space.
- Classification Modelling with **GaussianNB Model**
- Accuracy score: **82.5%**
- Use confusion matrix to showing the frequency of misclassifications by our classifier

