# HW7 of Machine Learning - Unsupervised Learning
* Ranked 4 place in class

Task : Use **autoencoder** and **PCA** to reduce dimension of images, then use **Kmeans** to separate two groups of images without label

Dataset : 40K 32 * 32 * 3 images come from CelebA & cifar10

train_model.py : Train autoencoder model

cluster.py : Use **PCA** to reduce dimension of figure, then use **Kmeans** to separate two groups of images

pca.py : Personally program PCA code and draw eigenface, reconstruct images

compare_images.py : Compare_images before and after autoencoder

**NOTE: Different random seed of PCA might affect result significantly !!!**
<br><br>


Usage of Scripts:

(1) Run pca.sh:

    bash ./pca.sh $1 $2 $3

    $1 <images path>  Aberdeen/
    $2 <input image> 87.jpg
    $3 <reconstruct image> 87_reconstruct.jpg
    
    
(2) Run cluster.sh:

    bash ./cluster.sh $1 $2 $3
    
    $1 <images path> images/
    $2 <test_case.csv path> test_case.csv
    $3 <prediction file path> ans.csv
