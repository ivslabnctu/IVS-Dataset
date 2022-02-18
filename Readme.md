# iVS-Dataset
![dfsfsdf](https://user-images.githubusercontent.com/95270738/154619973-e3c7b2a2-3813-4916-868b-561667f1d9ca.jpg)

For overcoming the limitations in the standard datasets with the data such as wide-variety of scales and data captured in various conditions that are necessary to train the neural networks to yield efficient results in the ADAS applications, this paper presents the self-built open iVS dataset and an open-to-free-use data annotation tool entitled ‘ezLabel’. The iVS dataset comprises of various objects of different scales as seen in and around the real driving environments. The data in iVS dataset are collected employing a camcorder in vehicles driving under different conditions such as light, weather and traffic, and driving scenarios ranging from city traffic in peak and normal hours to freeway traffic in busy and normal conditions. Thus, the collected data are of wide-range and captured all the possible objects in all the various scales as appeared in the real-time. The data collected to build the dataset has to be annotated before used in training the CNNs and this paper presents an open-to-free-use data annotation tool, ezLabel, for the data annotation as well.
## iVS-Dataset Statement
The dataset annotates the four commonly seen object types into four different categories of objects namely:  
1.scooter  
2.vehicle  
3.pedestrian  
4.bicycle   

The iVS dataset consists of 89,002 annotated training images and 6,400 annotated testing images of resolution 1920x1080

## iVS-Dataset Annotation

Class: the object class. I.e. car or person
Bounding box: an axis-aligned rectangle specifying the extent of the object visible in the image
View: ‘frontal’ , ‘rear’, ‘left’ or right
Difficult: an object marked as difficult indicates that the object is considered difficult to recognize without substantial use of context.
Truncated: an object marked as ‘truncated’ indicates that the bounding box specified for the object does not correspond to the full extent of the object.
Occluded: an object marked as ‘occluded’ indicates that a significant portion of the subject image is within the bounding box occluded by another object.
