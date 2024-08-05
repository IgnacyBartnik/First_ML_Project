# Sports Car or Sedan


## NON-TECHNICAL EXPLANATION 
This repo contains a very quickly made model, which can distuinguish between sport cars and sedan cars. It uses the ResNet50, a convolutional neural network, which was fine tuned on images scraped from the internet.

## DATA
The images for the training and validation set were taken from DuckDuckGo image search, using the queries sports car photo, sports car photo sun, sports car photo shade, and the quivalent with a "sedan car". The test set was made by using the term "fast sports car photo", "fast sports car photo sun", "fast sports car photo shade", and the equivalent with "slow sedan car". 

## MODEL 
The ResNet50 is a large CNN. Its a highly trained image recognition model, which is why it was chosen. It was then fine tuned for this application.



## RESULTS
The model performance was acceptable, but was likely impacted by the messy dataset, with lots of unclear images. 
