# RiceLeaf-Disease
Problem Statement  Task 1:-Prepare a complete data analysis report on the given data.  Task 2:-Create a model which can classify the three major attacking diseases of rice plants leaf blast, bacterial blight, and brown spot.  Task 3:- Analyze various techniques like Data Augmentation, etc, and create a report on that.


Challenges Faced and Other Observations
How to Do Data Exploration for Image Segmentation and Object Detection (Things I Had to Learn the Hard Way)

"I’ve been working with object detection and image segmentation problems for many years. An important realization I made is that people don’t put the same amount of effort and emphasis on data exploration and results analysis as they would normally in any other non-image machine learning project.

Why? People don’t understand object detection and image segmentation models in depth and treat them as black boxes, in that case they don’t even know what to look at and what the assumptions are. It can be quite tedious from a technical point of view as we don’t have good image data exploration tools.

Data exploration is key to a lot of machine learning processes. That said, when it comes to object detection and image segmentation datasets there is no straightforward way to systematically do data exploration."

Even though the author is talking about image segmentation, the observations also hold for working image classification problems in general.

General Observations
Leaf Smut has 39 vs 40 images, two of which are tagged incorrectly (I removed the tags/personal information)

DSC_0514.jpg DSC_0515.jpg

A visual inspection of the data shows that brown spot and leaf smut diseases are similar and that might be the reason for the incorrect tag. This is one of the issues with image classification. Computers cannot "see" and we might need to perform a manual inspection (spot check) of the data for these types of ML problems.

Sources
How to Do Data Exploration for Image Segmentation and Object Detection (Things I Had to Learn the Hard Way) https://neptune.ai/blog/data-exploration-for-image-segmentation-and-object-detection

Using Exploratory Data Analysis to Discover Patterns https://youtu.be/GIVK0-SNUgU
