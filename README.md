# machine_vision_prj

This project aims to explore various techniques for image classification. We'll delve into both traditional and modern approaches, comparing their performance on a given image dataset.

Methodology

    Feature Extraction:
        HOG Features: Extract Histogram of Oriented Gradients to capture edge and shape information.
        Color Histograms: Analyze the distribution of colors in an image.
        Local Binary Patterns (LBP): Identify local patterns of pixel intensities.

    Classification:
        Traditional Classifiers:
            K-Nearest Neighbors (KNN): Classify images based on the majority class of their nearest neighbors.
            K-Means Clustering: Group similar images together and assign new images to the closest cluster.
            Support Vector Machines (SVM): Find the optimal hyperplane to separate different image classes.

Implementation:

    Feature Extraction: Utilize OpenCV functions to extract the aforementioned features.
    KNN and K-Means: Implement these algorithms from scratch using Python.
    SVM: Employ the Scikit-learn library for efficient SVM implementation.

Evaluation:

    Dataset: Use a standard image dataset like CIFAR-100 dataset.
    Metrics: Evaluate the performance of each classifier using metrics like accuracy, precision.
