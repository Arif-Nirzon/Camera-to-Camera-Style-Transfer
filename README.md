# Camera-to-Camera-Style-Transfer
An attempt on creating a model that transfroms an image taken from camera A to what it would have looked like if it was taken on camera B.  
_**A part of our EEE 402 - AIML (Artifical Intelligence and Machine Learning) Laboratory final project**_
## Dataset Used
**Primary Dataset:** IEEE SP Cup 2018 Camera Model Identification Dataset- https://www.kaggle.com/competitions/sp-society-camera-model-identification/overview  
multiple 256x256 patches were taken from each photo to create a dataset of 55,000 images.
### Sample images from the dataset
<img width="718" height="714" alt="image" src="https://github.com/user-attachments/assets/ab40410a-e011-406a-8036-4527eb2c7645" />

## Model Used
StarGAN v2 (https://arxiv.org/abs/1912.01865)  
the code initial code taken from: https://www.kaggle.com/code/kimjiyeop/stargan-v2

## Results
### Single source to many reference
<img width="3078" height="1547" alt="image" src="https://github.com/user-attachments/assets/75f4b42f-65c1-4fe3-9b9e-91d8d70bbd2e" />
### Many source to single reference
<img width="1989" height="483" alt="Untitled" src="https://github.com/user-attachments/assets/d8f09b69-6769-4e0c-b744-b64978afe944" />
<img width="1989" height="483" alt="Untitled-1" src="https://github.com/user-attachments/assets/cb4be330-71c6-4659-9174-4c16ad1dba9e" />
### Loss plot (till 28 epochs)
<img width="928" height="452" alt="image" src="https://github.com/user-attachments/assets/b136a27c-2dac-4052-ad2d-77fd37c40073" />
### tSNE of stlye vectors from style encoder
<img width="983" height="790" alt="Untitled" src="https://github.com/user-attachments/assets/ab06ca51-3e5a-40b0-84bd-aa1733b9d7fe" />






