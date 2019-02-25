# RBF Neural Network
## Radial Basis Function Network
##### Author & Date: Sameer Kumar, 02/24/2019
- This code is for building a Radial Basis Kernel (RBF) neural network. RBF network has many applications like pattern recognition, function approximation and interpolation, classification problem etc. In this code I have implemented RBF network on a classification problem. 
- Input Samples variable indicates total no. of points present in both Positive and Negative Classes
Gaussian Standard Deviation is a free variable used in the Gaussian Kernel
Grid Size is controls the number of points to be searched on 1x1 grid to generate decision boundaries
- First part of the problem is to generate cluster centers using K-means algorithm. These centers acts as the RBF kernel centers. Half of the total center belong to one class and another half to other class. 
- Using these centers and signum activation function we can build a single layer perceptron to find the optimal weights which will then give us the decision boundary. Which ever points on the grid gives us zero output in our trained RBF network it will acts as the boundary, similar to Kernel SVM. 
- Postive Class is also represented by C_1 and Negative Class is also represented C_-1
- Note: I have also attached results.
