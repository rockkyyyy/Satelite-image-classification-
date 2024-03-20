# Satelite-image-classification-
Satelite image classification  using CNN Algotrithm

  ![image](https://github.com/rockkyyyy/Satelite-image-classification-/assets/119515066/79bb2287-c09e-4026-ba1b-da5eb30f7b0b)


Above dataset images are available inside ‘Dataset’

![image](https://github.com/rockkyyyy/Satelite-image-classification-/assets/119515066/3417c5bc-54a4-4589-9e37-1430204430e9)


In above screen click on ‘Upload Satellite Images dataset’ button to upload dataset
![image](https://github.com/rockkyyyy/Satelite-image-classification-/assets/119515066/62c03622-80cb-4203-9de4-7adf3ec561a6)

In above screen selecting and uploading ‘Dataset’ folder and then click on ‘Select Folder’ button to load dataset and to get below screen

In above screen dataset loaded and now click on ‘Extract Features from Images” to read images and then resize and extract pixels from each image and then generate training data

In above screen we can see dataset contains total 705 images and now click on ‘Train CNN Algorithm’ button to train CNN with above images
![image](https://github.com/rockkyyyy/Satelite-image-classification-/assets/119515066/5c082b62-3844-43a1-97d5-fc73e5972eb3)

In above screen CNN training is completed and we got its accuracy as 91% and below screen showing all layer details of CNN

In above screen we can see CNN is using different layers with different image size to filter images and to build trained model with better accuracy and in above screen first layer using image size as 62 X 62 and second layer using 31 X 31 and goes on. Now CNN model is ready and now click on ‘Accuracy Graph’ button to get accuracy of CNN model on each iterations or epoch

In above graph x-axis represents epoch and y-axis represents accuracy and to train CNN I took 20 epochs and at each increasing epoch CNN LOSS value decrease and CNN ACCURACY get increase and in above graph green line represents accuracy and blue line represents loss. Now click on ‘Upload Test Image & Classify’ button to upload test image and get below classification result

In above screen I am selecting and uploading ‘10233_sat.jpg’ and then click on ‘Open’ button to get below result

In above screen in green colour text we can see image classified as ‘Agriculture Land’ and all agriculture area is surrounded with red colour bounding boxes. Now upload other image and test
![image](https://github.com/rockkyyyy/Satelite-image-classification-/assets/119515066/3a8ad31f-6e24-4e1b-bbe9-612272608e6c)

For above selected area below is the classification result
![image](https://github.com/rockkyyyy/Satelite-image-classification-/assets/119515066/8fb085ab-2624-433d-84a8-1fa86bfb085b)

In above screen image classified as ‘Forest Land’ and entire forest area is surrounded with red colour bounding boxes. Similarly you can upload and test remaining images.
Note: dataset size is huge with 63 different classes so I took images with 3 classes and application can classify images correctly up to 80%
