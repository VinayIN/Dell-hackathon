# Hackathon project

**Abstract:**
Created a theoritical & working model and implemented it using ML/DL techniques
to predict the size of apparel(specifically-Shirt) in fashion Industry and thereby removing speculation whether the size fits or not.<br>
Thereby ,Model trying to tackle the realtime issue of fitting issue.

## ML/DL Technique used:
<ul>
  <li>Classification</li>
  <li>Regression</li>
  <li>AR (to be implemented)</li>
  <li>UI/UX (On hold)</li>
</ul><br>

[View Presentation](https://drive.google.com/file/d/0B23sJif2_HCnZE5IQmVlZ0Y2LUU/view?usp=sharing)<hr>

### Implementation Overview
Image dataset and Body measurement dataset was prepared manually for the hackathon.
Body measurement dataset [(BODY_dataset.pickle)](BODY_dataset.pickle) is pickled using this script [(Body_data_resize.ipynb)](Body_data_resize.ipynb), Also a complete CSV file is also attached [(MLD.csv)](MLD.csv) for the same.<br>
Shirt classification dataset [(IMAGE_data.pickle)](IMAGE_data.pickle) is picked using this script [(image_resize.ipynb)](image_resize.ipynb).

Note: The script **[image_resize.pickle](image_resize.pickle)** won't run because its raw Image dataset is not attached to this repository, however **[Body_data_resize.ipynb](Body_data_resize.ipynb)** will do fine.<hr>

<ul>
  <li>First, <b>Classification</b> is done for object detection and classification of apparel.
  <li>Second, <b>Regression</b> is done to estimate the chest circumference.
<ul>
  <li>using tensorflow framework.
  <li>using scikit-learn library.
</ul>
</ul><hr>

Find the jupyter notebook here:

**Classification Script** [(Image_classify.ipynb)](Image_classify.ipynb)<br>
**Regression Script** [(Regression_1_2_sklearn.ipynb)](Regression_1_2_sklearn.ipynb) and [(Regression_tensorflow.ipynb)](Regression_tensorflow.ipynb)
