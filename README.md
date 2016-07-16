# State Farm Distracted Driver Detection

## Summary
* Kaggle competition data (jpg file, 79,726 test data, 22,424 train data)
* https://www.kaggle.com/c/state-farm-distracted-driver-detection
* The goal is to classify all test data
* Feature X : 640 * 480 => image processing => 100 * 70
* Target Y : 10 classes
  * c0: safe driving
  * c1: texting - right
  * c2: talking on the phone - right
  * c3: texting - left
  * c4: talking on the phone - left
  * c5: operating the radio
  * c6: drinking
  * c7: reaching behind
  * c8: hair and makeup
  * c9: talking to passenger
  
## Download
* If you want to test my ipython notebook, you need to download imgs.zip in main directory.
* https://www.kaggle.com/c/state-farm-distracted-driver-detection
* Test images of 79,726, Train images of 22,424
* About 4gb data

## image processing
* Python Image Library(PIL)
* image convert to grayscale
* image resize 640 * 480 -> 120 * 90
* I think that it is not necessary the edges of images.
* image cut 120 * 90 -> 100 * 70 


