# Machine Learning Assignment 3 / Option 2 -- Clustering Artwork Using Unsupervised Learning

## Summary 

Using [KMeans](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) to cluster a set of images **on their metadata.** 

#### The images

This set of images represents more than 400 works of fine art from museum collections and galleries across several countries, curated and analyzed for inspiration and information on effective ways to visually communicate uncertainty, ambiguity, and vulnerability. The selected artworks were chosen for their unique ability to convey ***uncertainty*** using a range of approaches and techniques. The images are being used to inspire better design of visual representations of uncertainty in data, because [traditional methods and techniques aren't working very well](https://hbr.org/2016/11/why-its-so-hard-for-us-to-visualize-uncertainty). 


### Transformation of datatypes & Choosing the proper number of clusters: 

* We chose four features to cluster our data on:
1. "va" - the various degrees between white and black.
2. "or" - various orientations, ranging from the vertical to the horizontal in a distinct direction.
3. "reflection" - indicates the work contains an image given back by a reflecting surface, or an image seen in a mirror or shiny surface.
4. "has_text" - indicator that the work contains text

* We segmented our data based on the curve below, and chose 6:
 
![alt text](https://github.com/leeallennyc/visualizedata-ml/blob/master/ML_assignment_3/option_2/process/Cluster_number.png "Cluster Number")

### Final Analysis: 

* Final results are in the [cluster_final.ipynb File] (https://github.com/leeallennyc/visualizedata-ml/blob/master/ML_assignment_3/option_2/cluster_final.ipynb)
* Some of the results for clustering can be seen below:

![alt text](https://github.com/leeallennyc/visualizedata-ml/blob/master/ML_assignment_3/option_2/process/Clustered_images_1-6.png "Clustered Images")

### Process

* Included is a [Pdf] (https://github.com/leeallennyc/visualizedata-ml/blob/master/ML_assignment_3/option_2/process/Process_for_clustering_artworks.pdf) to illustrate some steps in the process.
