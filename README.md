**IMPLEMENTATION:**

**Step 1: Load the Pre-Trained YOLOv5 Model **
* Utilize the PyTorch library to load a pre-trained YOLOv5 model that has been trained on a large dataset to recognize various objects. 

**Step 2: Define Preprocessing Functions**
* Prepare image data for object detection by defining preprocessing functions. 
* Tasks include resizing images to a fixed size required by the model, normalizing pixel values to a certain range, and applying any other necessary transformations to enhance model performance. 
These preprocessing steps ensure that the input images are in the correct format and ready for effective processing by the YOLOv5 model. 

**Step 3: Implement Object Detection Algorithms**
* Feed the preprocessed images into the loaded YOLOv5 model to perform inference and detect objects within the images. 
* The model outputs bounding box coordinates, class predictions (e.g., pure or impure dal grains), and confidence scores for each detected object. 

**Step 4: Apply Non-Maximum Suppression (NMS) **
* Refine the detection results using Non-Maximum Suppression (NMS) to eliminate redundant bounding boxes that cover the same object. 

**Step 5: Calculate the Count of Pure and Impure Dal Grains **
* This quantitative data provides insights into the proportion of pure vs. impure grains in a sample, which can be valuable for quality control in food processing and packaging industries.

![Select](https://github.com/meghu03/Grain-Adulteration-Detection-using-Deep-Neural-Network/assets/116013635/2ef5adf7-e547-4ec8-bede-c24176a6a31e)

![input](https://github.com/meghu03/Grain-Adulteration-Detection-using-Deep-Neural-Network/assets/116013635/92a93c30-51ea-43df-b85c-0d6a63d05b47)

![output](https://github.com/meghu03/Grain-Adulteration-Detection-using-Deep-Neural-Network/assets/116013635/abf0a2fb-f6fe-43ae-aec9-12ffda08e662)


