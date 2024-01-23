# Support-Vector-Machines (SVM)

In this exercise, you will be using support vector machines (SVMs) to build a spam classifier. Before starting on the programming exercise, we strongly recommend watching the video lectures and completing the review questions for the associated topics.

To get started with the exercise, you will need to download the starter code and unzip its contents to the directory where you wish to complete the exercise. If needed, use the cd command in Octave/MATLAB to change to this directory before starting this exercise.

You can also find instructions for installing Octave/MATLAB in the \Environment Setup Instructions" of the course website. Files included in this exercise ex6.m - Octave/MATLAB script for the first half of the exercise:

1. ex6data1.mat - Example Dataset 1
2. ex6data2.mat - Example Dataset 2
3. ex6data3.mat - Example Dataset 3
4. svmTrain.m - SVM training function
5. svmPredict.m - SVM prediction function
6. plotData.m - Plot 2D data
7. visualizeBoundaryLinear.m - Plot linear boundary
8. visualizeBoundary.m - Plot non-linear boundary
9. linearKernel.m - Linear kernel for SVM
10. gaussianKernel.m - Gaussian kernel for SVM
11. dataset3Params.m - Parameters to use for Dataset 3
12. 1ex6 spam.m - Octave/MATLAB script for the second half of the exercise
13. spamTrain.mat - Spam training set
14. spamTest.mat - Spam test set
15. emailSample1.txt - Sample email 1
16. emailSample2.txt - Sample email 2
17. spamSample1.txt - Sample spam 1
18. spamSample2.txt - Sample spam 2
19. vocab.txt - Vocabulary list
20. getVocabList.m - Load vocabulary list
21. porterStemmer.m - Stemming function
22. readFile.m - Reads a file into a character string
23. submit.m - Submission script that sends your solutions to our servers
24. processEmail.m - Email preprocessing
25. emailFeatures.m - Feature extraction from emails
26. indicates files you will need to complete
    
Throughout the exercise, you will be using the script ex6.m. These scriptsset up the dataset for the problems and make calls to functions that you will
write. You are only required to modify functions in other files, by following the instructions in this assignment.
