# SECTION 1 : PROJECT TITLE
<img width="812" alt="welcome" src="https://user-images.githubusercontent.com/31118924/79683065-fad22e00-8259-11ea-9e1c-c2401a3129b1.PNG">


# SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
In this Continuous Assessment (CA), we utilize the Mask RCNN architecture with a ResNet backbone to train and infer image segmentation masks. The initial weights were pre-trained on COCO Images, and transfer learning was done onto images derived from the OpenImagesv5 dataset. The image classes are: Suit, Dress Jeans. The resulting test loss is 2.24 and the Mean Average Precision (mAP) achieved is 0.82. Lastly, 5 scoring images have been provided to showcase the model’s effectiveness in inference.


# SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name | Student ID (MTech Applicable)| Work Items (Who Did What) | Email (Optional) |
| :---: | :---: | :---: | :---: |
| YAM GUI PENG DAVID | A0195315A | Idea generation, dataset generation, model exploration, code formatting and structuring, and project report | e0384946@u.nus.edu |
| ZHAO YAZHI | A0195305E | Idea generation, model exploration, model fine tuning and project report | e0384936@u.nus.edu |


# SECTION 4 : USER GUIDE
[ 1 ] To run the codes in any machine with anaconda 3 installed

$ git clone git@github.com:davidygp/clothing_image_segmentation.git

$ cd ./clothing_image_segmentation

$ conda create --name mask_rcnn_v2 python=3.6.10

$ conda activate mask_rcnn_v2

$ conda install -c anaconda cudatoolkit==9.0 cudnn==7.1.4

$ pip install -r requirements.txt

$ pip install git+https://github.com/philferriere/cocoapi.git#subdirectory=PythonAPI

$ jupyter notebook

In the browser click on the mask_rcnn_main notebook


[ 2 ] To run the codes on google colab

1) Upload the following files:
   (NOTE: put it into a folder called "colab_notebooks" in your "My Drive")  
   mask_rcnn_envir.zip  
   mask_rcnn_main.ipynb   


# SECTION 5 : PROJECT REPORT / PAPER
<Github File Link> https://github.com/davidygp/clothing_image_segmentation/tree/master/report/Report.pdf
