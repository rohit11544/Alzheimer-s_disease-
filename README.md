# Alzheimer's disease Classifier model 
this CNN Model detect's Alzheimer's disease 

### Alzheimer's disease
Alzheimer's disease is a progressive disorder that causes brain cells to waste away (degenerate) and die.
Alzheimer's disease is the most common cause of dementia — a continuous decline in thinking, behavioral and 
social skills that disrupts a person's ability to function independently.

### LIBRARIES
* os
* cv2
* tqdm
* numpy
* pandas
* seaborn
* matplotlib
* sklearn
* pickle

### About the model
This model is built with 5 convolution layers on around 5000 brain images. This model has a accuracy more than 96.88% on test set.

### About the dataset
This dataset is downloaded from kaggle weblsite. The data set can be downloaded from the zip file in this repository. This data set contains 4 classes 
MildDemented, ModerateDemented, NonDemented, VeryMildDemented.This data set contain total of 5121 examples (including training ,validation and testing sets).

## preview of this data set
#### MildDemented
![mildDem1](https://user-images.githubusercontent.com/61901749/86908731-a5107200-c134-11ea-95b2-1dfcbd587244.jpg)
![mildDem2](https://user-images.githubusercontent.com/61901749/86908738-a6419f00-c134-11ea-816e-3bfe0d886432.jpg)
![mildDem3](https://user-images.githubusercontent.com/61901749/86908742-a6da3580-c134-11ea-857e-402188811e21.jpg)
![mildDem8](https://user-images.githubusercontent.com/61901749/86908744-a772cc00-c134-11ea-959f-aa9da5553b4b.jpg)

#### ModerateDemented
![moderateDem2](https://user-images.githubusercontent.com/61901749/86908920-ef91ee80-c134-11ea-8032-126b3f170958.jpg)
![moderateDem4](https://user-images.githubusercontent.com/61901749/86908921-f15bb200-c134-11ea-97e5-800340d9d299.jpg)
![moderateDem6](https://user-images.githubusercontent.com/61901749/86908923-f1f44880-c134-11ea-82f1-fd2ee2a79036.jpg)
![moderateDem7](https://user-images.githubusercontent.com/61901749/86908924-f1f44880-c134-11ea-831f-f29f21ead5f1.jpg)

#### NonDemented
![nonDem1](https://user-images.githubusercontent.com/61901749/86909073-2d8f1280-c135-11ea-8820-baaa556db5ec.jpg)
![nonDem6](https://user-images.githubusercontent.com/61901749/86909077-2ec03f80-c135-11ea-9b19-b7c8e0f45160.jpg)
![nonDem7](https://user-images.githubusercontent.com/61901749/86909081-2f58d600-c135-11ea-8631-0fae53606e0a.jpg)
![nonDem8](https://user-images.githubusercontent.com/61901749/86909086-2ff16c80-c135-11ea-8e7b-dd8baf727ed6.jpg)

#### VeryMildDemented
![verymildDem2](https://user-images.githubusercontent.com/61901749/86909225-5dd6b100-c135-11ea-9dbe-820e09e1045f.jpg)
![verymildDem3](https://user-images.githubusercontent.com/61901749/86909227-5f07de00-c135-11ea-98bf-04e29212b0c8.jpg)
![verymildDem5](https://user-images.githubusercontent.com/61901749/86909228-5fa07480-c135-11ea-8dba-1ab3f89a298d.jpg)
![verymildDem6](https://user-images.githubusercontent.com/61901749/86909230-60390b00-c135-11ea-8aff-309aeaa68e5d.jpg)

## plots
### loss function vs the number of epochs

<img src="https://user-images.githubusercontent.com/61901749/86909689-1997e080-c136-11ea-9ab8-ba25b04946bf.png" width=400>

### accuracy vs the number of epochs

<img src="https://user-images.githubusercontent.com/61901749/86909693-1bfa3a80-c136-11ea-8015-30d36b66c41c.png" width=400>
