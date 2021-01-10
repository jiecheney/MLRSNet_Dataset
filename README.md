# MLRSNet: A Multi-label High Spatial Resolution Remote Sensing Dataset for Semantic Scene Understanding 

> MLRSNet provides different perspectives of the world captured from satellites. That is, it is composed of high spatial resolution optical satellite images. MLRSNet contains 109,161 remote sensing images that are annotated into 46 categories, and the number of sample images in a category varies from 1,500 to 3,000. The images have a fixed size of 256×256 pixels with various pixel resolutions (~10m to 0.1m). Moreover, each image in the dataset is tagged with several of 60 predefined class labels, and the number of labels associated with each image varies from 1 to 13. The dataset can be used for multi-label based image classification, multi-label based image retrieval, and image segmentation. You could get dataset from https://data.mendeley.com/datasets/7j9bv9vwsx/1 or https://github.com/cugbrs/MLRSNet.git.
> 
> The Dataset includes:
> 1.	Images folder: 46 categories, 109,161 high-spatial resolution remote sensing images.
> 2.	Labels folders: each category has a . csv file.
> 3.	Categories_names. xlsx: Sheet1 lists the names of 46 categories, and the Sheet2 shows the associated multi-label to each category.

### However, there are some problems with the original data labeling,such as label mised and label wrong annotated. The new Labels Folder after modification are shown in the labels folder. For the data set divided into training-validation and test were 1:1.The total number of training tests is 54,588, and the total number of test sets was 54,573. The list divided is in train_val.txt and test.txt respectively.
