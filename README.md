## SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Name : Sudhit Soni
Roll No. : 102017137
Sub-Group: 3CS6

## Dataset

Dataset:-
[https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)


## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1       | 0.88          | Poly        | 5.82    | 4.35         |
| 2       | 0.95          | Linear      | 5.13    | 0.30         |
| 3       | 0.96          | Linear      | 3.13    | 6.32         |
| 4       | 0.96          | Poly        | 1.49    | 3.26         |
| 5       | 0.91          | Linear      | 3.52    | 7.34         |
| 6       | 0.83          | RBF         | 5.60    | 3.14         |
| 7       | 0.95          | Poly        | 0.29    | 7.71         |
| 8       | 0.95          | Poly        | 4.87    | 5.57         |
| 9       | 0.97          | Poly        | 1.27    | 6.87         |
| 10      | 0.92          | Poly        | 0.34    | 5.50         |

## Convergence Graph
![graph](https://user-images.githubusercontent.com/72306997/233000047-3bbc6cf2-8ec0-4276-8519-17da7da2fb25.png)

## Conclusion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.Sample 9 has the best accuracy of 0.97 having kernel = Poly, Nu = 1.27 and Epsilon = 6.87.

