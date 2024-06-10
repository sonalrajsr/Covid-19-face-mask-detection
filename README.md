# Covid-19 Face Mask Detection System

This project is a machine learning application designed to detect whether a person is wearing a face mask or not. Using a convolutional neural network (CNN) based on the VGG16 architecture, the model is trained to classify images into two categories: "with mask" and "without mask." The goal is to assist in monitoring and ensuring compliance with mask-wearing guidelines, which is crucial during the Covid-19 pandemic.

## Dataset Images
![App Screenshot](https://github.com/sonalrajsr/Covid-19-face-mask-detection/assets/123736054/88aaa7ac-c9af-4e2f-bf49-169a44fa2600)
![App Screenshot](https://github.com/sonalrajsr/Covid-19-face-mask-detection/assets/123736054/00cfff20-d216-4cab-94eb-c9f9119b8de7)

## Dataset Link
https://universe.roboflow.com/pyimagesearch/covid-19-pis/?ref=pyimagesearch

## Labels 
- 0 = Without Mask
- 1 = With Mask
  
## Making Dataset
The dataset link contains two folders. With_mask & Without_mask
- Make an empty list 'data'
```bash
data = []
```
- Loop through each folder and store images in the empty list called 'data' with their labels.
- Shuffle those combined images.
  ```bash
  random.shuffle(data)
  ```
## Output Images
![image](https://github.com/sonalrajsr/Covid-19-face-mask-detection/assets/123736054/c01f69ab-cedd-4c4a-b58a-ea75ecc90b90)
![image](https://github.com/sonalrajsr/Covid-19-face-mask-detection/assets/123736054/8b189a55-0ae7-4379-b209-1013afb82f77)

