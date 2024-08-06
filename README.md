# Sports Car or Sedan

## SETUP
Please [download the model](https://drive.google.com/drive/folders/13BfoikRw271cG6c3vDMCwUhbTszZMTEq?usp=share_link), and make sure it is located in the repo as ```models/model.path```




## NON-TECHNICAL EXPLANATION 
This repo contains a very quickly made model, which can distuinguish between sport cars and sedan cars. It uses the ResNet50, a convolutional neural network, which was fine tuned on images scraped from the internet.

## DATA
The images for the training and validation set were initially taken from DuckDuckGo image search, using the queries sports car photo, sports car photo sun, sports car photo shade, and the quivalent with a "sedan car". The test set was made by using the term "fast sports car photo", "fast sports car photo sun", "fast sports car photo shade", and the equivalent with "slow sedan car". However, it was later realized that adding sun and shade caused lots of sun shade products to be included in datasets, so those variations were removed. Instead, the search terms were "sports car" and "sedan car" for the train/val set, and "fast sports car" and "slow sedan car" for the test set.

## MODEL 
The ResNet50 is a large CNN. Its a highly trained image recognition model, which is why it was chosen. It was then fine tuned for this application.



## RESULTS
The model performance was acceptable, but was likely impacted by the messy dataset, with some unclear images. 
![first_ML_project](https://github.com/user-attachments/assets/1f0e757f-8378-4769-9fca-9f8288a13e4c)
