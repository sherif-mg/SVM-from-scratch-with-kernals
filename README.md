# SVM-from-scratch-with-kernals
Introduction to Support Vector Machines
Support Vector Machines aim to find the optimal hyperplane that separates data points of different classes with the maximum margin. The margin is the distance between the hyperplane and the nearest data points from each class, known as support vectors. The goal is to maximize this margin, which helps in achieving better generalization on unseen data.

**Hard Margin SVM**<br />
Hard Margin SVM is used when the data is perfectly linearly separable. It seeks to find a hyperplane that not only separates the classes but does so with the maximum margin, ensuring no data points are misclassified. 

**Soft Margin SVM**<br />
In real-world scenarios, data is often not perfectly linearly separable. Soft Margin SVM introduces slack variables to allow some misclassifications and find a balance between maximizing the margin and minimizing the classification error

**Kernel Tricks**<br />
One of the most powerful features of SVMs is their ability to perform classification in higher-dimensional spaces using kernel tricks. A kernel function computes the inner products in this higher-dimensional space without explicitly mapping the data to that space, making the computation more efficient.

Common kernel functions include:
-Linear Kernel<br />
-Polynomial Kernel<br />
-Radial Basis Function (RBF) Kernel<br />

**Kernel SVM**<br />
Kernel SVMs use kernel functions to transform input data into a higher-dimensional space where a linear hyperplane can effectively separate the data. This allows SVMs to classify data that is not linearly separable in the original input space.

**Classifying Non-Linear Data**<br />
Kernel SVMs are particularly useful for classifying non-linear data. By using kernel functions, SVMs can create non-linear decision boundaries that separate classes in the original input space. This is achieved without explicitly mapping the data to the higher-dimensional space, making the computation efficient and practical for real-world applications.
