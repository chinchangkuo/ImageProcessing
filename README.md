# Introduction:
This is the repository for identifying bubble cluster configurations composed of 3 large and 3 small bubbles. The image processing algorithm "6bubblepreprocess.py" is  used for: 
1. Detect the bubble cluster 
2. Filter the size of bubble clusters composed by different numbers of large and small bubbles
3. Focus on 3 large and 3 small bubble cluster to classify the configurations

For more information about the experiment, please refer to: 
C.-C. K. N. S. C. O. a. M. D. 1. Kai Zhang, "Stable small bubble clusters in two-dimensional," Soft Matter, vol. 13, pp. 4370-4380, 2017. 

# How to use demo images:
Please place "CNN_demo.zip" and "6bubblepreprocess.py" into the same folder. 

Acknowledgement: Nathaniel See for his contribution to the configuration classification 

# Demo of the code:
# The raw image from the experimental setup for bubble cluster automatic generate![Figure_0](https://raw.githubusercontent.com/chinchangkuo/ImageProcessing-bubble_cluster_n3l3s/master/Figure_0.png)
# Filter the cluster composed by 3 large and 3 small bubbles![Figure_1](https://raw.githubusercontent.com/chinchangkuo/ImageProcessing-bubble_cluster_n3l3s/master/Figure_1.png)
# Classify the configuration based on the bubble-bubble bounding(red: l-l; blue: s-s; green l-s)![Figure_3](https://raw.githubusercontent.com/chinchangkuo/ImageProcessing-bubble_cluster_n3l3s/master/Figure_3.png)
# Generate the image for the bubble cluster with configuration labels and the same image size![Figure_4](https://raw.githubusercontent.com/chinchangkuo/ImageProcessing-bubble_cluster_n3l3s/master/Figure_4.png)

