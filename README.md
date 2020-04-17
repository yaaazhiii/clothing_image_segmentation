# SECTION 1 : PROJECT TITLE
### clothing_image_segmentation
<img width="812" alt="welcome" src="https://user-images.githubusercontent.com/48171290/54080819-80836a80-4333-11e9-9f1d-7f21123d454f.png">


# SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
(to fill in)

# SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name | Student ID (MTech Applicable)| Work Items (Who Did What) | Email (Optional) |
| :---: | :---: | :---: | :---: |
| YAM GUI PENG DAVID | A0195315A | Idea generation, dataset generation, model exploration, code formatting and structuring, and project report | e0384946@u.nus.edu |
| ZHAO YAZHI | A0195305E | Idea generation, model exploration, model fine tuning and project report | e0384936@u.nus.edu |


# SECTION 4 : USER GUIDE
[ 1 ] To run the codes in any machine with anaconda 3 installed

$ git clone git@github.com:davidygp/clothing_image_segmentation.git

$ cd ./clothing_image_segmentation

(We were unable to upload the conda environment due to filesize issues, even with GitLFS) 
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
   (so /content/drive/'My Drive'/colab_notebooks/mask_rcnn_envir.zip &
       /content/drive/'My Drive'/colab_notebooks/mask_rcnn_main.ipynb)

2) Open the mask_rcnn_main.ipynb with "Google Colaboratory"


# SECTION 5 : PROJECT REPORT / PAPER
<Github File Link>  https://github.com/davidygp/IRS-MR-2019-01-19-IS1PT-GRP-MRCard/tree/master/ProjectReport/Report.pdf

+ Project Objectives & Success Measurements
+ Project Solution
+ Project Performance & Validation
+ ...
# -clothing_image_segmentation
