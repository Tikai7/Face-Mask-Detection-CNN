# Face-Mask-Detection-CNN
  - This CNN represent the architecture of MobileNetV2 CNN's
  - Model Size after training : 36mb
  - Accuracy >= 90%
  - Training time with Ryzen 5 3600, 97minutes
  - ![plot](https://user-images.githubusercontent.com/68500496/147691766-6b31ceb6-4ad3-4d28-9116-5a8c4d882336.png)

# How it works
  - MobileNet Architecture : 
  - ![CNN_architecture](https://user-images.githubusercontent.com/68500496/147691740-c6a0c583-bfcf-40a2-98e5-5a9ac0bfdde5.PNG)
  - MobileNet Block : 
  - ![CNN_block](https://user-images.githubusercontent.com/68500496/147691699-6e17b71c-ff55-416a-9d30-df65e39acdcd.PNG)


# How to use it 
  - download the dataset at this link : https://www.kaggle.com/omkargurav/face-mask-dataset
  - create folder dataset in the root, and name it "dataset"
  - launch "dataload.ipynb" first then 
  - launch "detect_video.ipynb" and enjoy prediction
  - Can only detect faces withtout mask so it say if there is mask or no only on faces without mask.
  - Otherwise, if there is a mask, it does not take into account the number of people.
